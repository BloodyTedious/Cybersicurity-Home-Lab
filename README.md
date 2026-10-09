# Cybersecurity Home Lab

An isolated virtual lab for practicing ethical hacking, built with VirtualBox. It contains a Kali Linux attacker machine and a Metasploitable 2 target, connected through a private internal network.

**Full report:** [homelab_report_EN.pdf](homelab_report_EN.pdf)

## What the report covers
- Lab setup and network design (NAT + internal network `labnet`, target isolated from the internet)
- Metasploitable 2 import and static IP configuration
- Connectivity check with ping
- First Nmap port scan: 23 open ports found on the target

## Tools
VirtualBox · Kali Linux · Metasploitable 2 · Nmap 7.95

## Next steps
- Scan with service version detection and default scripts (`nmap -sV -sC`)
- FTP anonymous login test, SSH brute force with Hydra, web application enumeration
- Metasploit Framework
- A writeup for each step, added to this repository

*Educational project, carried out on virtual machines owned by the author in an isolated environment.*
