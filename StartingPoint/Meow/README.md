# HTB - Meow (Starting Point)

## Objective
Practice basic enumeration and service identification.

## Skills Learned
- VPN connection to Hack The Box
- Service enumeration using Nmap
- Identifying Telnet service
- Basic Linux enumeration

## Tools Used
- Nmap
- Telnet
- Kali Linux

## Methodology

### 1. Enumeration
```bash
nmap -sV -sC TARGET_IP
```

Discovered:
- Port 23 open (Telnet)

### 2. Service Interaction
Connected to Telnet service:

```bash
telnet TARGET_IP
```

### 3. Lessons Learned
- Always enumerate first
- Check for weak/default credentials in beginner labs
- Understand exposed services before exploitation

## Achievement
Completed the HTB Starting Point machine: Meow

Achievement Link:
https://labs.hackthebox.com/achievement/machine/2304405/394
