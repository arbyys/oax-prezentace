---
marp: true
theme: gaia
paginate: true
_class: lead
color: black
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---

## Useful technologies in software projects

Adam Petříček

___

## Introduction

- not mandatory, but useful
- any software project
- enhancing best practices
- used to:
    - improve code quality
    - save time
    - eliminate mistakes
    - make collaborative projects easier

___

## Code documentation
- function docs comments
    - can be used for generating wiki
    - code is more understandable by other people
    - necessity for great open-source projects
<br>
- API endpoint documentation &mdash; **Swagger**
    - code formatted as YAML / JSON
    - generates nicely looking API structure
    - endpoints can be tested

<div style="position: absolute; right: 25px; top: 25px;">
    <img width="560" src="https://www.arbystools.eu/storage/uploaded/9f04.png">
</div>

___

<div style="display: flex; align-items: center; justify-content: center;">
    <img width="1250" src="https://www.arbystools.eu/storage/uploaded/bf5b.png">
</div>

___

## Static code analysis

<div style="font-size: 1.9rem">

- Prettier, Linters (language-specified)
1) **catching bugs** - Linters
    - no unused, undeclared variables
    - no class reassigning
    - force return in class getter
2) **code formatting** - Prettier
    - normalized number of spaces
    - limit characters in one line
    - keyword spacing
- code formatting useful in collaborative projects
</div>

<div style="position: absolute; right: 45px; top: 25px;">
    <img width="400" src="https://www.arbystools.eu/storage/uploaded/7deb.png">
</div>

___

## Code testing

<div style="font-size: 1.82rem">

- writing program that expects designated result for each case that can happen in your code
- example - **testing a function that moves robot by some distance forward**
    - 1. case: `distance = 10`
        - you expect robot to move by 10 units
    - 2. case: `distance = "hello"`
        - you expect program to throw exception
    - 3. case: `distance = 0`
        - you expect robot to stay in place
- if all cases match the expectations, tests succeed
- rewriting tests everytime you change your code
</div>

___

#### Generated code coverage

<div style="display: flex; align-items: baseline; justify-content: center;">
    <img width="1155" src="https://res.cloudinary.com/practicaldev/image/fetch/s--TO30MJ07--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/o18xsiqnukxrvryncsji.png">
</div>


___

## Docker

<div style="font-size: 1.9rem">

- OS-level virtualization (OS not virtualized)
- isolates software to containers - **containerization**
- used for having the same working environment for software on different machines
<br>
1. you create **dockerfile** (set of instructions) for the app where you specify all the needed files, libraries, etc.
2. on different machine, you create **docker container** from the dockerfile where your app will be running
3. you don't have to worry about mismatched versions of libraries, etc.
</div>

___

<div style="display: flex; align-items: baseline; justify-content: left;">
    <img width="700" src="https://www.arbystools.eu/storage/uploaded/54f6.png
">
</div>


___

### Git CI

<div style="font-size: 2rem">

- Continuous Integration
- GitHub and GitLab each with their own implementation
- way to automate routine tasks like testing, builds or deployment with every **push**
- CI can be set to do different tasks depending on commit tag
- you can generate **artifacts** for download - results of CI (code coverage)
- previously mentioned technologies can be automated using CI

<div>

___

### Git CI - practice example

<div style="font-size: 2rem">

- *setup*:

1. creating tests, static code analysis, containerization
2. adding these tasks to the CI
- *when you push to Git*:
1. if static code analysis or tests fail, commit gets rejected
2. when everything passes, app build starts (Docker)
3. after app is built, you can deploy it to production server automatically

<div>   

___

<div style="display: flex; justify-content: center; align-items: center;">

# Any questions?

</div>

___

# Questions

1. Which of the mentioned technologies seems the most useful to you? Why?

2. What other practices / technologies do you use for improving your software projects?

3. Do you believe that well written code needs comments? Why?

4. How would you describe some of your biggest bad habits while writing code? What can you do to get rid of them?

___

<div style="display: flex; justify-content: center; align-items: center;">

# Thanks for you attention

</div>