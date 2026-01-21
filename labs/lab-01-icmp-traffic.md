# Lab 01 — ICMP Traffic Analysis

## Objective
Analyze ICMP traffic to verify host connectivity and understand basic packet exchange.

## Environment
- Kali Linux (traffic capture)
- Metasploitable (target)
- Network: Isolated host-only network

## Tools Used
- ping
- tcpdump
- Wireshark

## Commands Used
```bash
ip a
ping -c 4 <TARGET_IP>
sudo tcpdump -i <INTERFACE> icmp


## Evidence

### Ping Connectivity
![Ping ICMP](screenshots/icmp-ping-success.png)

### tcpdump ICMP Capture
![tcpdump ICMP](screenshots/icmp-tcpdump-capture.png)

### Wireshark ICMP Analysis
![Wireshark ICMP](screenshots/icmp-wireshark-view.png)
