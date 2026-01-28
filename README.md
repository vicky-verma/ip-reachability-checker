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
# ip-reachability-checker
