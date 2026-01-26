# Week 1 – Networking Lab (Day 1)

## Overview
This lab documents Day 1 of my hands-on cybersecurity journey.
The focus was on networking fundamentals and DNS troubleshooting
using Kali Linux in a VMware virtual machine.

## Objectives
- Verify network connectivity
- Understand DNS resolution issues
- Learn how `/etc/resolv.conf` works
- Use NetworkManager (`nmcli`) for DNS configuration
- Document findings for reproducibility

## Lab Environment
- Host OS: Windows
- Virtualization: VMware Workstation
- Guest OS: Kali Linux
- Network Mode: NAT

## Steps Performed

### 1. Test IP Connectivity
```bash
ping -c 3 8.8.8.8
2. Test DNS Resolution
ping -c 3 google.com
3. Check DNS Configuration
cat /etc/resolv.conf
4. Configure DNS Using NetworkManager
sudo nmcli connection modify "Wired connection 1" ipv4.ignore-auto-dns yes
sudo nmcli connection modify "Wired connection 1" ipv4.dns "8.8.8.8 1.1.1.1"
sudo nmcli connection down "Wired connection 1"
sudo nmcli connection up "Wired connection 1"
5. Verify DNS Resolution
ping -c 3 google.com
Lessons Learned
IP connectivity does not guarantee DNS functionality

/etc/resolv.conf is auto-generated and may override manual edits

NetworkManager is the correct place for persistent DNS configuration

Hands-on troubleshooting reinforces theory effectively

Notes
Detailed terminal outputs and observations are documented in notes.md.

