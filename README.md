# Sharon's Cloud Project

This project displays the *public IP address* of an AWS *EC2 instance* using a simple HTML page.  
It’s part of my Cloud & DevOps learning journey, focusing on deploying and automating web applications with *AWS EC2* and *Ansible*.

---

## Overview

*Goals:*
- Launch EC2 instances (AWS Free Tier)  
- Host a simple HTML page that shows the instance’s IP address  
- Automate setup and deployment with *Ansible*

---

## Tools & Technologies

- *AWS EC2*
- *Ansible*
- *Linux (Ubuntu)*
- *HTML / CSS*
- *Git & GitHub*

---

## How It Works

1. The HTML page is deployed to the EC2 web directory.  
2. Ansible replaces a variable placeholder ({{ ansible_host }}) with the instance’s actual public IP.  
3. When opened in a browser, the page displays the live IP — confirming a successful deployment.

---

## What I Explored

- How to launch and manage AWS EC2 instances  
- Basic configuration management using Ansible  
- Automating deployments and integrating dynamic data into a web page  

---

## Author

*Sharon Ugah*  
Cloud & DevOps Engineer 
