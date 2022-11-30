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
- best practices
- used to:
    - improve code quality
    - save time
    - eliminate mistakes
    - make collaborative projects easier

___

## Code documentation
- function docs comments
    - used for generating wiki
    - code is more understandable by other people
    - almost mandatory for open-source projects
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

- Prettier, Linters
- code formatting useful in collaborative projects
1) **catching bugs** - Linters
    - no unused, undeclared variables
    - no class reassigning
    - force return in class getter
2) **code formatting** - Prettier
    - normalized number of spaces
    - limit characters in one line
    - keyword spacing
</div>

<div style="position: absolute; right: 45px; top: 25px;">
    <img width="400" src="https://www.arbystools.eu/storage/uploaded/7deb.png">
</div>

___

## Code testing

- expecting designated result for each case that can happen
- example - ?

___

## Docker



___

## Git CI

- Continuous Integration