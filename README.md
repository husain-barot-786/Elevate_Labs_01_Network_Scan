# Elevate_Labs_01_Network_Scan
Port scanning and packet analysis of a local network using Nmap and Wireshark.

# Internship Task 1: Local Network Port Scanning & Packet Analysis

This task involves scanning a local network to identify open ports and analyzing the packet-level behavior of those scans. This project demonstrates basic network reconnaissance using Nmap and Wireshark.

## Task Description

**Objective**: Discover open ports and analyze network traffic using Nmap and Wireshark.  

**Platform**: Kali Linux  

Tools Used:  
- **Nmap**: For scanning open TCP ports on devices in the local network.  
- **Wireshark**: For capturing and filtering SYN packets during the scan.

## Repository Structure

```
internship-task-1-network-scan/
├── scan_results.txt                  # Nmap scan output
├── nmap_scan_capture.pcapng          # Wireshark capture file
├── Network_Scan_Report.txt           # Full professional report
├── README.md                         # This file
```

## Concepts Covered
- Port Scanning (TCP SYN)
- Subnet Discovery
- Packet Analysis with Wireshark
- Open Port Enumeration
- Network Security Recommendations

## Report Highlights

- Used `nmap -sS` for stealth SYN scanning.
- Analyzed TCP SYN packets using Wireshark with `tcp.flags.syn == 1 && tcp.flags.ack == 0`.
- Interpreted open ports and identified potential risks.
- Saved and documented everything professionally.
