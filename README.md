# Cybersecurity
Day-1


Network Scanning and Analysis using Nmap & Wireshark
Overview:
This project demonstrates basic to intermediate-level network scanning using Nmap, along with packet analysis using Wireshark, and identification of potential security risks in a local network environment.

Tools Used:
Nmap – Network scanner for host discovery and port scanning.
Wireshark – Packet analysis tool for monitoring and interpreting network traffic.
Operating System – Windows 10 / Linux (Ubuntu)

Tasks Performed

Installation & Setup
Installed Nmap from the official site.
Verified installation using:
nmap --version

Local Network Discovery
Identified local IP and subnet using:
ipconfig (Windows)
ifconfig/ip a (Linux)
Defined the target range: 192.168.1.0/24.

TCP SYN Scan (Stealth Scan)
Scanned the local network to discover active hosts and open ports:
nmap -sS 192.168.1.0/24

Packet Analysis with Wireshark
Captured and analyzed TCP SYN packets during the scan.
tcp.flags.syn == 1 && tcp.flags.ack == 0

Port and Service Enumeration
Identified common services and ports using:
nmap -sV
Researched services like SSH (22), HTTP (80), RDP (3389), and others.

Risk Analysis
Evaluated each open port for potential security threats.
Recommended actions (e.g., disabling Telnet, enforcing SSH keys, restricting RDP).
