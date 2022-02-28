---
marp: true
theme: gaia
paginate: true
_class: lead
color: black
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---

# Cybercrime 1

<br><br>

Adam Petříček, Radek Mocek

---

# Cybercrime

- crime which includes network and a computer
    - is performed with computer or against computer
    - could be performed by individuals or organized groups
- some of the most common threats are **phishing**, **ransomware**, **DoS**, **botnet**, **keylogger**, **SQL injection**
- **malware** is a generic term for describing any software designed to cause trouble

___

# Phishing

- social engineering technique, consists of fraudulent message
- message is trying to get sensitive user information by pretending to look like official message from some service
    - user is redirected to fake website which looks exactly like the real one
    - if user inputs their credentials, the attacker will gain access to them, they could be then used to steal victim's account

**HOW TO AVOID:**
URL in message could have typo in it (e.g. youutube.com)
___


<div style="display: flex; align-items: center; justify-content: center;">
    <img width="1000" src="https://www.imperva.com/learn/wp-content/uploads/sites/13/2019/01/phishing-attack-email-example.png">
</div>

___

# Ransomware
- attacker blocks and encrypts user's data
- then he blackmails user and demands money for decrypting data
    - attacker can also threaten to publish data (if they're sensitive)
- typically spreads using trojan horse in some malicious software downloaded by user
- payment required by attacker is usually using cryptocurrencies (to avoid being tracked)

**HOW TO AVOID:**
do not download content from suspicious sources
___

<div style="display: flex; align-items: center; justify-content: center;">
    <img width="1200" src="https://spinbackup.com/wp-content/uploads/2020/01/petya-ransomware.png">
</div>

___

# DoS / DDoS
- Denial of Service / Distributed Denial of Service
- attack aimed at servers, trying to make them unavailable for users
    - the goal is not to take control over the service
- performed via sending huge amount of data to the server and overwhelming it
- DDoS is organized DoS using lots of computers all sending data to one target

**HOW TO AVOID:**
using DDoS protection on your server to check incoming requests

___

<div style="display: flex; align-items: center; justify-content: center;">
    <img width="950" src="https://www.researchgate.net/profile/Pericherla-Suryateja/publication/324562008/figure/fig2/AS:616337260945411@1523957662750/Denial-of-Service-DoS-attack-A-DDoS-Distributed-Denial-of-Service-attack-as-shown-in.png">
</div>

___

# Botnet
- lots of inficated computers (zombies) are controlled from one device to perform different cybercrimes (most often DDoS)
- users typically do not have a clue about their computer being infected
- bot master has to limit number of requests to avoid being caught by ISP

**HOW TO AVOID:**
you can check your network traffic to find some suspicious requests
___

<div style="display: flex; align-items: center; justify-content: center;">
    <img width="850" src="https://managementmania.com/uploads/article_image/image/5472/ddos-attack-basic-scheme.jpg">
</div>

___

# Keylogger

- malware which records keys you press and sends them to the attacker
- attacker can gain your credentials using this method
- hardware keyloggers can be harder to detect than software
- your antivirus should usually detect the keylogger before it installs

**HOW TO AVOID:**
by deleting it if you identify keylogger in your running tasks

___


<div style="display: flex; align-items: center; justify-content: center;">
    <img width="950" src="https://upload.wikimedia.org/wikipedia/commons/c/c4/Keylogger-software-logfile-example.jpg">
</div>

___

# SQL injection

- SQL is language used to manage databases
- this attack targets poorly secured forms on websites
- by typing part of the SQL query directly into the form input, the query would execute and cause trouble in database
- attacker can either try to remove data from database or to gain access to secured data like passwords

**HOW TO AVOID:**
by securing your SQL query or database

___

<div style="display: flex; align-items: center; justify-content: center;">
    <img width="1110" src="https://www.researchgate.net/profile/Muhammad-Iqbal-274/publication/322250414/figure/fig3/AS:579066325864448@1515071578177/A-SQL-injection-attack.png">
</div>

___

# Encryption
<div style="margin-top: 35px;">
- process of securing data by encoding them using various algorithms

**Hash**
- data are encrypted using complex mathematical functions
- there is no way to get original data back (used to store passwords)

**Cypher**
- data are encrypted using algorithm with decryption key
- this key is secure and can be used to decrypt data back
</div>

___

# Questions

**1)** Have you ever been a victim of some cybercrime?

**2)** What protection are you using to prevent downloading malware?

**3)** How do you make your password secure?

**4)** How do you identify that message is phishing?

___

# Phrases

- SQL query (Structured Query Language)
- URL (Universal Resource Locator)
- ISP (Internet Service Provider)
- hash
- cryptocurrencies
- log file