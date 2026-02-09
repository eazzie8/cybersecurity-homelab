# Week 2


## Day 8 – Firewall Behavior & IDS Mindset

### Firewall Observations
- Checked existing iptables rules and UFW status
- Enabled UFW and reviewed default allow/deny policies
- Blocked HTTP traffic (port 80) and observed impact
- Confirmed that ICMP traffic still passed

### Key Takeaways
- Firewalls operate on explicit rules, not assumptions
- Blocking one service does not affect unrelated traffic
- Understanding default policies is critical for troubleshooting

### IDS Perspective
- Repeated ICMP or port scanning patterns would likely trigger alerts
- IDS focuses on behavior patterns, not single packets
- Baseline traffic understanding is required before detection
