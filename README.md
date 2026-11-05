# Network Security Lab

## Overview
A hands-on cybersecurity learning project focused on network discovery, TCP port scanning, and basic domain information gathering using Nmap and WHOIS.

The exercises were performed on macOS in a local lab environment to develop practical networking and security assessment skills.

## Tools and Environment
- macOS (Apple Silicon)
- Nmap 7.98
- WHOIS
- Terminal
- Homebrew

## Objectives
- Understand basic network discovery techniques.
- Identify active hosts within a local network.
- Perform basic TCP port scanning.
- Interpret open and closed port states.
- Explore publicly available domain registration information.
- Practise responsible security documentation.

## Methodology

### 1. Network Discovery
Nmap host discovery was used to identify active devices within an authorised private network.

Results:
- 256 IP addresses checked
- 5 active hosts discovered
- Scan duration: 21.62 seconds

### 2. TCP Port Scanning
A targeted TCP connect scan was performed against an authorised local router.

| Port | State | Service |
|------|-------|---------|
| 21 | Closed | FTP |
| 22 | Closed | SSH |
| 53 | Open | DNS |
| 80 | Open | HTTP |
| 443 | Open | HTTPS |
| 8080 | Closed | HTTP Proxy |

Service labels represent standard Nmap port associations and were not independently verified.

### 3. WHOIS Lookup
A WHOIS lookup was performed on a publicly registered domain to explore domain registration information.

## Key Learnings
- How to use Nmap for host discovery and TCP port scanning.
- How to interpret basic network scan results.
- The difference between open and closed TCP ports.
- How WHOIS provides publicly available domain information.
- The importance of protecting network information when sharing security findings.

## Results
See the anonymised reports in network-discovery.txt and port-scan.txt.

## Ethical Considerations
All local network scans were conducted for educational purposes on an authorised network. Internal IP addresses and device identifiers have been excluded from the public reports.

## Disclaimer
This project is intended for educational and portfolio purposes only. It does not constitute a penetration test or vulnerability assessment.
