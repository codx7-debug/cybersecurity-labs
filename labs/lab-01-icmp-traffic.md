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
