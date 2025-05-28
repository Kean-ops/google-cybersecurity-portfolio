# Portfolio Activity C3M3a — Analyze Network Attack

## 🧩 Project Overview

This project simulates a real-world cybersecurity incident involving a suspected denial of service (DoS) attack on a travel agency’s web server. As a security analyst, you are tasked with analyzing captured network traffic to identify the type of attack and assess its impact on the organization.

## 📄 Scenario Summary

An automated alert flagged abnormal traffic behavior targeting the company’s website. Upon attempting to access the site, users received a connection timeout error. Initial packet analysis revealed a surge of TCP SYN requests from an unfamiliar IP address, overwhelming the server. You used a packet sniffer to capture and inspect network traffic to diagnose the issue.

The server was taken offline to recover, and a temporary firewall rule was implemented to block the suspicious IP address.

## 🔧 Your Role

As a security analyst, your tasks included:

- Reviewing a Wireshark-generated `.csv` log of network traffic.
- Identifying patterns consistent with common network-based attacks.
- Determining the type of attack based on packet behavior.
- Preparing a report summarizing findings and recommended mitigations.

## 📁 Files Included

- `Wireshark-TCP_HTTP-log.csv` – Captured network traffic showing signs of attack.
- `Analyst-network-attacks-incident-report.pdf` – Completed incident report describing the type of attack, its symptoms, impact, and recommended next steps.

## 🛠️ Skills Demonstrated

- Network traffic analysis using Wireshark logs
- Identification of SYN flood/DoS attacks
- Cybersecurity incident response
- Technical report writing
- Understanding of TCP/IP and HTTP behavior in attack contexts

---

📌 **Note:** This activity highlights the importance of real-time traffic monitoring and proactive firewall configuration to respond to and prevent network-layer attacks.
