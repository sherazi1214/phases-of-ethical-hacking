# phases-of-ethical-hacking

 the phases of ethical hacking. Below are the 5 main phases, explained in detail:

## 1. Reconnaissance (Information Gathering)
Purpose: To collect as much information as possible about the target.

### Types:

Passive Reconnaissance: Gathering information without directly interacting with the target (e.g., WHOIS, social media, Google dorking).

Active Reconnaissance: Directly engaging with the target (e.g., pinging, port scanning).

Data Collected:

Domain names

IP addresses

Open ports

Technologies used

Employee emails or contacts

### Tools: Nmap, Maltego, Recon-ng, Google Dork, Shodan

## 2. Scanning
Purpose: To discover live hosts, open ports, services, and vulnerabilities.

### Types:

Network Scanning: Finds active devices and their IP addresses.

Port Scanning: Identifies open ports on a host.

Vulnerability Scanning: Detects known vulnerabilities in systems or software.

### Tools: Nmap, Nessus, OpenVAS, Nikto, Acunetix

## 3. Gaining Access
Purpose: To exploit identified vulnerabilities and access the system.

### Common Techniques:

Password cracking

SQL injection

Buffer overflow

Exploiting software vulnerabilities

Man-in-the-Middle (MitM) attacks

### Tools: Metasploit, Hydra, John the Ripper, SQLmap

## 4. Maintaining Access
Purpose: To retain control over the compromised system for further exploitation.

### Methods:

Installing backdoors

Creating new user accounts

Using rootkits or Trojans

### Tools: Netcat, Meterpreter, Backdoor tools

Note: In ethical hacking, this step is only simulated, not actually implemented in a harmful way.

## 5. Covering Tracks
Purpose: To erase any evidence of hacking activity.

### Actions:

Clearing logs

Deleting uploaded tools

Modifying timestamps

### Tools: Timestomp, Log Cleaner Scripts

Important: Ethical hackers do not perform this step in real-world jobs, but they understand how attackers use it, to help organizations defend against such tactics.

## Reporting (Bonus Phase)
After completing the ethical hacking process, a detailed report is prepared with:

All discovered vulnerabilities

Methods used for testing

Suggestions to fix the issues (mitigation steps)

Risk levels (e.g., High, Medium, Low)

