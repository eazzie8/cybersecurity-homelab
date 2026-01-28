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


---

## Day 2 – Basic Router Connectivity & Troubleshooting

### Focus
Understanding how devices communicate through a router and how to troubleshoot connectivity issues using Cisco Packet Tracer and Kali Linux.

### What I Did
- Built a simple network topology in Cisco Packet Tracer
- Connected a PC to a router and verified link status
- Assigned IP addresses and brought router interfaces up
- Tested connectivity using `ping`
- Troubleshot failed pings caused by unconfigured interfaces

### Key Observations
- A green link light does not always mean connectivity is working
- Router interfaces are down by default and must be enabled
- Connectivity issues are often configuration problems, not cable issues

### Tools Used
- Kali Linux
- Cisco Packet Tracer
- Basic Cisco IOS commands (`show ip interface brief`, `ping`)

### What I’m Learning
Networking makes more sense when you actually break things and fix them. Even when the steps aren’t fully clear yet, repetition and troubleshooting help concepts stick.
