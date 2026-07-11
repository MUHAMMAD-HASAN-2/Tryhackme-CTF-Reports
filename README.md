# 🚩 CTF Write-ups & Reports

Welcome to my repository of Capture The Flag (CTF) write-ups and security reports. This repository serves as a documentation of my methodology, tool utilization, and thought process across various cybersecurity platforms and challenges.

## 🛠️ Skills & Frameworks Demonstrated
*   **Web Penetration Testing:** SQL Injection (SQLi), CSRF, BAC, Authentication Flaws
*   **Privilege Escalation:** Linux/Windows local privilege escalation, misconfigured cron jobs, SUID binaries
*   **Reconnaissance & Enumeration:** Nmap, Gobuster, Metasploit, Burp Suite
*   **OS/Environment Familiarity:** Linux (Debian/Ubuntu), Windows Fundamentals

---

## 📂 Repository Structure

The repository is organized by platform and machine name for easy navigation:

```text
├── TryHackMe/
│   ├── Pickle-Rick/
│   │   ├── README.md          # Detailed write-up
                               # Screenshots and payloads


🏆 Featured Write-ups
Date	Platform	Challenge/Machine	Difficulty	Key Concepts / Vulnerabilities Exploited	Link
June 2026	TryHackMe	Pickle Rick	Easy	Web Enumeration, Command Injection, Linux PrivEsc	View Report
June 2026	TryHackMe	Advanced SQLi	Medium	WAF Bypass, Filter Evasion, Blind SQLi	View Report
📝 General Methodology

Every report in this repository follows a structured, professional penetration testing format:

    Reconnaissance & Port Scanning: Identifying open ports, services, and versions.

    Enumeration: Diving deeper into web directories, hidden parameters, or network shares.

    Initial Foothold: Exploiting identified vulnerabilities to gain user access.

    Privilege Escalation: Enumerating the internal environment to elevate privileges to root or NT AUTHORITY\SYSTEM.

    Remediation: Key takeaways and defensive recommendations to patch the exploited flaws.

🧰 Tools Regularly Used

    Scanners: nmap, nikto, gobuster, dirbuster

    Interception & Proxies: Burp Suite Community Edition

    Exploitation: sqlmap, custom Python scripts, msfvenom

    Post-Exploitation: LinPEAS, WinPEAS



Disclaimer: All write-ups published here are for educational purposes only. I only perform security testing on environments I own, or platforms where I have explicit permission to do so.
