# Portfolio Activity C3M4 — Web Server Brute Force and Malware Analysis

## 📘 Project Overview

In this cybersecurity investigation, I analyzed a web server compromise involving a brute force attack and malware injection on the website `yummyrecipesforme.com`. A former employee gained unauthorized access through default credentials, embedded malicious JavaScript, and redirected users to a fake site distributing malware. This project demonstrates skills in protocol analysis, incident reporting, and recommending security measures.

## 🔍 Scenario Summary

A former employee executed a brute force attack using known default passwords to access the admin panel of the `yummyrecipesforme.com` website. They embedded JavaScript prompting users to download a malicious executable file. The file redirected users to a fake website, `greatrecipesforme.com`, leading to system compromise. Multiple customers reported abnormal behavior, prompting an investigation.

## 🧪 Investigation & Analysis

I was provided with a captured `tcpdump` log in PDF format to analyze network traffic associated with the malware incident. From the log, I observed the following traffic pattern:

- DNS request and response for `yummyrecipesforme.com`
- HTTP GET request to the legitimate site
- Initiation and execution of a file download
- DNS and HTTP requests to `greatrecipesforme.com` following execution

**Identified Protocols:**

- **DNS (port 53):** For domain name resolution
- **HTTP (port 80):** For web traffic and redirection

## 📝 Incident Report Summary

Key findings include:

- Default password enabled brute force access
- JavaScript malware embedded in web source code
- Redirect to fake site distributing malicious software
- Malware induced performance issues on customer systems

**Remediation Recommendation:**
To mitigate brute force attacks in the future, I recommend **enforcing two-factor authentication (2FA)** for all administrative accounts. 2FA adds a second layer of security beyond the password, reducing the effectiveness of brute force attempts and improving access control.

## 📁 Included Files

- `Tcpdump-log.pdf`: Captured network traffic showing protocol sequence
- `Web-server-brute-force-and-malware-analysis-incident-report.pdf`: Detailed incident report, findings, and recommendation

---

This project strengthens my practical understanding of network-based attacks, log analysis, and real-world mitigation techniques. You can explore the full analysis and report in this repository.
