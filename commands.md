# Network Security Lab - Commands

## Environment
- macOS (Apple Silicon)
- Nmap 7.98
- Terminal
- Homebrew

## 1. Nmap Installation

brew install nmap

Installs Nmap using Homebrew.

## 2. Verify Nmap Installation

nmap --version

Displays the installed Nmap version.

## 3. Network Configuration

route -n get default | grep gateway

Identifies the default network gateway.

ipconfig getpacket en0

Retrieves DHCP network configuration information.

## 4. Network Discovery

nmap -sn <authorised-network-range>

Discovers active hosts without performing a port scan.

## 5. TCP Port Scanning

nmap -sT -p 21,22,53,80,443,8080 --max-retries 1 <authorised-router-IP>

Performs a TCP connect scan on six selected ports.

## 6. WHOIS Lookup

whois google.com

Retrieves publicly available domain registration information.

## Security and Privacy

- All local network testing was performed for educational purposes.
- Internal IP addresses and device identifiers are omitted.
- Network scanning should only be performed on systems you own or are authorised to assess.
