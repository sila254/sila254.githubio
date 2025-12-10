---
title: "Cybersecurity Labs & Writeups"
layout: single
permalink: /labs/
toc: true
toc_label: "Lab Navigation"
---

# 🔐 Cybersecurity Labs & CTF Writeups

This section contains well-documented lab challenges, penetration testing exercises, and security assessments.  
Each entry includes:  
✔ Problem statement  
✔ Tools used  
✔ Methodology  
✔ Screenshots  
✔ Key lessons learned  

---

# 🧪 Lab 1: SQL Injection – DVWA

### **Problem Statement**
Identify and exploit a SQL injection vulnerability in DVWA to extract user credential information.

### **Tools Used**
- DVWA  
- Burp Suite  
- SQLMap  
- Kali Linux  

### **Approach**
1. Enumerated vulnerable parameters.  
2. Tested union-based payloads.  
3. Extracted database names, tables, and user accounts.  
4. Used improved payloads to obtain the missing username field.

### **Key Lessons**
- Manual SQL injection provides deeper understanding than automation.  
- Poor input validation leads to full system compromise.  

---

# 🧪 Lab 2: Network Reconnaissance – Nmap & Gobuster

### **Problem Statement**
Perform active and passive reconnaissance on a target machine.

### **Tools Used**
- Nmap  
- Gobuster  
- Netcat  

### **Approach**
- Conducted SYN, version, and script scans  
- Enumerated open ports and services  
- Bruteforced directories with common wordlists  

### **Key Lessons**
- Reconnaissance determines the entire attack strategy.  

---

# 🧪 Lab 3: Password Cracking – John the Ripper

### **Problem Statement**
Crack Linux user password hashes extracted from `/etc/shadow`.

### **Tools Used**
- John the Ripper  
- Hashcat  
- Rockyou wordlist  

### **Approach**
- Identified hash type  
- Ran dictionary attacks  
- Compared performance between JtR and Hashcat  

### **Lessons Learned**
- Weak password policies lead to rapid compromise.  

---

More labs will be added regularly as I advance my cybersecurity practice.
