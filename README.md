## Wazuh-Installation

# README.md

Project Overview
What is Wazuh?
Objectives
Lab Environment
Prerequisites
Wazuh Installation
Installation Commands

## Project Overview

This project documents the installation and basic setup of **Wazuh**, an open-source security monitoring and SIEM/XDR platform, on an Ubuntu Linux environment.
The objective of this project is to build a security monitoring lab where system logs, security events, vulnerabilities, file integrity, and other activities can be monitored through the Wazuh Dashboard.
The project covers the installation process, configuration, dashboard access, and basic verification of the Wazuh environment.

## What is Wazuh?

**Wazuh** is an open-source security platform used for **Security Information and Event Management (SIEM)** and **Extended Detection and Response (XDR)**.
It helps security teams monitor endpoints, collect and analyze security events, detect suspicious activities, identify vulnerabilities, monitor file integrity, and investigate security incidents.
Wazuh consists of components such as the **Wazuh Manager, Wazuh Indexer, Wazuh Dashboard, and Wazuh Agents**. Agents are installed on monitored endpoints and send security-related data to the Wazuh Manager for analysis and visualization.

### Key Features

* Security event monitoring
* Log collection and analysis
* Vulnerability detection
* File Integrity Monitoring (FIM)
* Security configuration assessment
* Malware and threat detection
* Endpoint monitoring
* Alert generation and visualization
* Centralized security monitoring through a web dashboard

# Lab Environment

1. Install ubuntu operating system 
2. Open tarminl type This command
3. 
4. curl -sO https://packages.wazuh.com/4.14/wazuh-install.sh && sudo bash ./wazuh-install.sh -a

   
6. <img width="855" height="646" alt="image" src="https://github.com/user-attachments/assets/18d72f80-2172-4f63-b293-7ffcb4c459d5" />

And then Wait for 20 to 25 min for installation 


<img width="905" height="652" alt="wazuh 2" src="https://github.com/user-attachments/assets/521e40da-65e2-4a35-a9aa-0062df496b40" />

<img width="957" height="682" alt="wazu installtion" src="https://github.com/user-attachments/assets/6abdfac0-557a-41da-ae36-c65955fabdc1" />

After complete installation Open your google chrome type ubuntu system Ip address like this...
Https://192.168.5.132

<img width="1917" height="781" alt="image" src="https://github.com/user-attachments/assets/332ce34e-76b7-46cf-8287-195b33688f3e" />

After click on Adopction

<img width="1917" height="781" alt="image" src="https://github.com/user-attachments/assets/ecb68a31-2490-4e7d-b7e6-adc449b711aa" />


Then type user id and password and login it..
User Name - Admin 
Password  - The password could be anything.

<img width="1917" height="1031" alt="image" src="https://github.com/user-attachments/assets/d08e7a85-3ede-410a-924b-d0996ba97526" />

<img width="1917" height="1017" alt="image" src="https://github.com/user-attachments/assets/90a88f27-6493-4bdc-b539-cfe010cda94f" />


