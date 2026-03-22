# Internal Network Security Assessment (Windows & Linux)

## Overview
Simulated a real internal network attack in a controlled lab environment using Kali Linux against Windows and Linux machines.

## Environment
- Attacker: Kali Linux
- Targets: Windows 10 & Ubuntu 16.04
- Network: Internal VirtualBox lab

## Key Activities
- Network discovery and full port scanning (Nmap)
- Web enumeration and vulnerability discovery (Gobuster, Nikto, WPScan)
- Credential discovery through exposed configuration files
- Brute-force attack against WordPress login
- Reverse shell exploitation and system access
- Privilege escalation to root (Linux)

## Key Findings
- Exposed credentials in configuration files
- Outdated WordPress version with multiple weaknesses
- Anonymous FTP access enabled
- Directory listing enabled on web server
- Weak authentication controls

## Results
- Full compromise of Linux system (root access)
- Partial compromise of Windows system (high-risk vulnerabilities identified)

## Tools Used
- Nmap
- Gobuster
- Nikto
- WPScan
- Hydra
- Metasploit

## Purpose
This project demonstrates real-world internal network attack scenarios and highlights how misconfigurations and weak security controls can lead to full system compromise.

## Mitigation Recommendations
- Disable directory listing
- Enforce strong password policies
- Patch outdated software
- Restrict unnecessary services
