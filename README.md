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

While building this project, I understood how attackers first check whether a host is alive before performing deeper scans. Initially, I was confused when some IPs showed as unreachable, but later I learned that ICMP can be blocked by firewalls and unreachable does not always mean the host is down.

Working on this project helped me gain confidence in using Python with system commands on Kali Linux. I also learned how small reconnaissance scripts form the base of larger network scanning tools.
