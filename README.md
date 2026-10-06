# Bhulok 🌍

Bhulok is a Linux web exploitation CTF machine built around a vulnerable Laravel web application.

The challenge focuses on web enumeration, SQL injection, Local File Inclusion (LFI), credential discovery, SSH access, scheduled-task abuse, and Linux privilege escalation.

## 🎯 Objectives

- Enumerate the web application
- Identify the vulnerable Laravel endpoints
- Exploit SQL Injection
- Discover administrative credentials
- Exploit Local File Inclusion
- Discover SSH credentials/keys
- Obtain a user shell
- Abuse scheduled tasks
- Escalate privileges to root
- Capture the user and root flags

## 🛠️ Attack Chain

```text
Web Enumeration
      ↓
Laravel Application
      ↓
SQL Injection
      ↓
Admin Credentials
      ↓
Local File Inclusion (LFI)
      ↓
Credential / SSH Key Discovery
      ↓
User Access
      ↓
Scheduled Task Abuse
      ↓
patallok
      ↓
Sudo Privilege Escalation
      ↓
Root
