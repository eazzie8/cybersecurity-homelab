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


## Day 9 – Log Analysis & SIEM Mindset

### Logs Explored
- /var/log/auth.log
- /var/log/syslog

### Observations
- Identified authentication and sudo activity
- Observed system and process-level events
- Noted timestamps and event structure

### SIEM Perspective
- Logs provide context that packet captures cannot
- Events are correlated by time, user, and action
- SIEM tools automate aggregation and alert


## Day 10 – Linux Host Investigation

- Verified user identity and group membership
- Reviewed system directory permissions
- Practiced file permission management (chmod 600)
- Investigated running processes and identified ssh-agent vs ssh service
- Reviewed active services using systemctl
- Checked listening ports using ss
- Accessed system logs using journalctl
- Confirmed no exposed services on host
