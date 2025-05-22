# Yay
My journey begins!
# Welcome to My Cybersecurity Journey

This repository is a living record of everything I'm learning as I train for a career in ethical hacking, penetration testing, and cybersecurity. I'm documenting tools, protocols, hands-on labs, concepts, and everything else along the way.

## Current Progress

### Networking & Protocol Fundamentals

* Learned the **OSI Model** (7 layers) and the **TCP/IP model** (4 layers)
* Understand **TCP vs UDP** and their roles in web traffic
* Memorized and explained the **3-way handshake** (SYN → SYN/ACK → ACK)
* Learned key packet headers: source/destination IPs and ports, TTL, checksum, flags
* Studied and memorized common **port numbers**:

  * `21` FTP
  * `22` SSH
  * `80` HTTP
  * `443` HTTPS
  * `445` SMB
  * `3389` RDP

### Tools I've Used and Studied

* **Nmap**

  * Port scanning, version detection (`-sV`), OS detection (`-O`), and timing flags (`-T1`–`T5`)
* **GoBuster**

  * Brute-forcing directories using wordlists to find hidden paths on web servers
* **Burp Suite**

  * Proxy setup, Intercept ON/OFF behavior
  * Editing requests and understanding headers, cookies, and POST data
  * Target Site Map and Inspector panel
  * Repeater tool for manually resending and editing HTTP requests
  * Learned Pretty, Raw, Hex, and Render views for interpreting responses

### Web Exploitation Concepts

* Identified hidden directories using GoBuster
* Understood how to manipulate URLs and inputs to trigger `404` vs `500` errors
* Analyzed HTTP headers, body parameters, and cookies with Burp
* Learned how to modify form values to bypass restrictions

### SQL Injection (SQLi)

* **In-Band SQLi**: Classic `OR 1=1 --` injections
* **Blind SQLi - Boolean Based**: Using true/false logic to extract data
* **Blind SQLi - Time-Based**: Measuring server response delays to leak information
* **Out-of-Band SQLi**: Advanced techniques using DNS/HTTP callbacks

## What I'm Working on Now

* Finishing Burp Suite labs on TryHackMe (Repeater, Inspector, challenges)
* Deep-diving into SQL Injection and preparing for Vulnversity's Extra Mile

## Why I'm Doing This

I'm aiming to build a strong portfolio for entry-level cybersecurity roles, including:

* SOC Analyst
* Junior Pentester
* Web Application Security Tester

