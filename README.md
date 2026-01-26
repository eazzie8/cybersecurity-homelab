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


