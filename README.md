# IP Reachability Checker

## Description
A Python script to check whether an IP address or hostname is reachable using ICMP ping.

## How it works
The script sends one ICMP echo request to the target and checks the response.

## Why attackers use this
Attackers use reachability checks during reconnaissance to identify live hosts before scanning ports.

## Defensive Insight
- ICMP can be blocked by firewalls
- Unreachable does not always mean the host is down

## Environment
- OS: Kali Linux
- Language: Python 3

## My Learning Experience

## My Learning Experience

While working on this project, I learned that attackers first check whether a system is alive before doing further scanning. At first, I was confused when some IP addresses showed as unreachable, but later I understood that firewalls can block ICMP requests, so unreachable does not always mean the system is down.

This project helped me become more comfortable using Python with system commands on Kali Linux. I also realized that small scripts like this are the foundation of bigger network scanning and security tools.
