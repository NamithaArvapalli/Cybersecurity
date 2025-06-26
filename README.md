# Cybersecurity Internship
Task-1


Network Scanning and Analysis using Nmap & Wireshark

📌 Overview
It demonstrates basic to intermediate-level network scanning using Nmap, along with packet analysis using Wireshark, and identification of potential security risks in a local network environment.

🔧 Tools Used

Nmap – Network scanner for host discovery and port scanning.

Wireshark – Packet analysis tool for monitoring and interpreting network traffic.

Operating System – Windows 10 / Linux (Ubuntu)

📂 Tasks Performed

✅ 1. Installation & Setup
Installed Nmap from the official site.
nmap --version

✅ 2. Local Network Discovery
Identified local IP and subnet using:
ipconfig   (Windows)
ifconfig/ip a   (Linux)
Defined the target range

✅ 3. TCP SYN Scan (Stealth Scan)
Scanned the local network to discover active hosts and open ports:
nmap -sS <target-ip>

✅ 4. Packet Analysis with Wireshark
Captured and analyzed TCP SYN packets during the scan.

✅ 5. Port and Service Enumeration
Identified common services and ports using:
nmap -sV <target-ip>
Researched services like SSH (22), HTTP (80), TCP, and others.

✅ 6. Risk Analysis
Evaluated each open port for potential security threats.






