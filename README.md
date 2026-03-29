# Cybersecurity Homelab

This repository documents my hands-on cybersecurity learning journey, with a strong focus on practical labs, traffic analysis, and real-world security concepts rather than pure theory.

The goal is to build solid foundational skills aligned with SOC and Blue Team workflows: understanding how traffic behaves, how controls affect it, and how detection systems reason about behavior.

---

## Week 1 – Networking & Traffic Analysis

**Focus:** Networking fundamentals, Packet Tracer labs, and packet inspection.

- **Day 1:** Networking lab setup and DNS troubleshooting  
- **Day 2:** IP addressing and Packet Tracer connectivity testing  
- **Day 3:** Packet flow observation (hands-on focus, no written notes)  
- **Day 4:** DNS fundamentals (conceptual understanding)  
- **Day 5:** DNS traffic analysis and observations  
- **Day 6:** Wireshark packet capture and inspection  
- **Day 7:** Traffic pattern review and baseline understanding  

Notes and lab work for this week are stored in the `week-1-networking` directory.

---

## Week 2 – Firewall Behavior & IDS Mindset

**Focus:** Transition from passive traffic observation to active traffic control and detection thinking.

- **Day 8:** Firewall behavior analysis using UFW and iptables  
  - Observed default firewall policies  
  - Applied targeted traffic blocking (HTTP)  
  - Tested protocol-specific impact (HTTP vs ICMP)  
  - Developed IDS-style thinking based on traffic patterns and repetition  

This week emphasizes understanding how security controls behave underneath and how SOC analysts reason about alerts, baselines, and anomalies.

Work and notes are stored alongside the existing lab structure and will be expanded as the week progresses.


---


# OverTheWire Bandit: Levels 1–33

This repository chronicles my journey through **OverTheWire Bandit**, levels 1–33—a hands-on wargame designed to teach Linux command-line mastery, system navigation, and foundational cybersecurity skills.

---

## Journey Overview

I began Bandit with only basic Linux knowledge. Over 33 levels, I progressed from simple navigation to **advanced challenges involving restricted shells, SSH keys, and multi-step file decoding**.  

Key learning areas:
- File system navigation and hidden file discovery
- Compression, encoding, and multi-layered decoding
- Restricted shell handling and SSH troubleshooting
- Combining commands to analyze program behavior

---

## Challenges Overcome

- Escaping **restricted shells and pagers**
- Multi-step decoding of files
- Handling **SSH and localhost restrictions** requiring meticulous attention

---

## Skills Gained

- Analytical thinking and problem-solving in constrained environments
- Confidence in Linux environments, command-line operations, and SSH workflows
- Cybersecurity mindset: observe, analyze, act deliberately
- Creative command-line problem solving

---

## Level-by-Level Highlights

| Levels | Focus / Skills | Key Takeaways |
|--------|----------------|---------------|
| 1–10   | Basic navigation, file reading, permissions | Foundation in Linux commands |
| 11–20  | Compression, encoding, hidden files | Handling complex files and pipelines |
| 21–30  | SSH keys, restricted shells, multi-step decoding | Problem-solving, logical analysis |
| 31–33  | Advanced restricted shells, environment limits | Creativity, patience, advanced troubleshooting |


---

## Next Steps

- Apply these skills in **Linux administration and penetration testing labs**
- Maintain this repository as a **learning resource and reference**
