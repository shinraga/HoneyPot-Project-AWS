# HoneyPot via AWS & Tpot 

# Overview /Introduction
This project uses a honeypot setup on an AWS EC2 instance to capture and analyze network attacks, utilizing Tpot, an open-source honeypot platform that utilizes 20+ honeypots. T-Pot automates data from various services such as Dionaea, Cowrie, and Suricata, visualized through Kibana. The goal is to observe attack patterns, analyze attacker behaviors, and identify common vulnerabilities.

# Security Warning / Disclaimer
[!WARNING]
Always deploy honeypots in isolated enviroments (such as a dedicated Docker container, virtual machine, or cloud VPS). Running a honeypot on a public-facing production server can expose your infrastructure to collateral risk.

# What does T-Pot collect?
- Real-time Telemetry: Captures source IPs, timestamps, and raw connection durations
- Credential harvesting: Logs every username and password combination attempted by hackers.
- Webhook Integration: Instantly forwards attack alerts to Discord, Slack, or custom endpoints.
- Lightweight Footprint: Low CPU and memory usage, easy to run on a cheap cloud instance.

# Setup Instructions
