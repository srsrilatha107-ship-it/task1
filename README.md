# Network Scanning Project

## Project Title
**Local Network Scanning and Port Analysis**

---

## Tools Used
- **Nmap** – for network discovery and port scanning.  
- **Wireshark** – for capturing and analyzing network traffic.  
- **Python** – optional, for automating network scans.  
- **Git & GitHub** – for version control and submission.  

---

## Project Description
This project focuses on **scanning a local network to discover active devices, open ports, and running services**. Using **Nmap**, the project identifies IP addresses and the services running on them. Optionally, **Wireshark** is used to capture and analyze network traffic to understand communication patterns within the network. The project helps in **assessing potential security risks** and provides hands-on experience in network scanning and analysis in a safe, educational environment.  

---

## Project Objectives
1. **Install and configure Nmap** for network scanning.  
2. **Identify the local IP range** to target for scanning.  
3. **Perform TCP SYN scans** to discover active hosts and open ports.  
4. **Document discovered IP addresses and open ports**.  
5. **Optionally capture and analyze network traffic** using Wireshark.  
6. **Research common services running on open ports**.  
7. **Identify potential security risks** associated with open ports and services.  

---

## Steps / Workflow
1. Install Nmap from the official website.  
2. Find your local IP range using `ipconfig` (Windows) or `ifconfig` (Linux/macOS).  
3. Run TCP scans:  
   ```bash
   nmap -sT 192.168.1.0/24   # TCP Connect Scan
   nmap -sS 192.168.1.0/24   # SYN Scan (half-open)
