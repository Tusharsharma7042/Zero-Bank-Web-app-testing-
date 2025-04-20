# Zero-Bank-Web-app-testing-
🔐 ZeroBank Personal Loans – Vulnerability Assessment Project
Description:
This project documents a comprehensive vulnerability assessment of the ZeroBank web application, specifically targeting the Personal Loans module. The goal was to simulate penetration testing on a realistic banking environment to uncover critical security flaws and demonstrate potential exploitation scenarios.

🛡️ Identified Vulnerabilities:
Cross-Site Scripting (XSS):
Reflected XSS found in the loan application form inputs.
Exploitable via user input without proper sanitization or encoding.
Default Login Credentials:
Application accepted default admin credentials (e.g., admin:admin), indicating poor authentication hygiene.
Unrestricted Open Ports on Server:
Network scanning revealed open ports (e.g., 21, 22, 8080) that could allow attackers lateral movement or brute-force attempts.
Insecure Communication Channel (HTTP):
Application running over HTTP instead of HTTPS, exposing sensitive data (like login credentials) to interception via MITM attacks.
Outdated Components in Use:
Detected use of outdated JavaScript libraries and vulnerable server-side components with known CVEs.
Clickjacking Vulnerability:
No X-Frame-Options header implemented, making the application vulnerable to clickjacking attacks.
Server Version Disclosure:
HTTP headers leaked precise server version (e.g., Apache/2.4.41), aiding potential attackers in crafting version-specific exploits.
🧰 Tools Used:
Burp Suite  • Nmap • Wappalyzer •retire.js• Shodan
📌 Skills Demonstrated:
Web App Pentesting • Reconnaissance • Exploitation • Vulnerability Analysis • OWASP Top 10 • Secure Coding Practices

