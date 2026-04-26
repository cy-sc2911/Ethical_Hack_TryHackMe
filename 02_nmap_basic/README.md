## 📚 Overview

This module covers the fundamentals of **Nmap**, one of the most essential tools for network reconnaissance and security auditing. Nmap is used to discover hosts and services on a network, thereby mapping the network and identifying potential security vulnerabilities.

**Prerequisites:** Basic understanding of networks, TCP/IP, and Linux command line

---

## 🎯 Learning Objectives
- Understand what Nmap is and its use cases in ethical hacking
- Install and configure Nmap on your system
- Perform basic network scans and interpret the results
- Use various scan techniques (TCP, UDP, SYN, etc.)
- Identify open ports, services, and operating systems
- Implement scanning best practices and avoid detection
- Create custom Nmap commands for specific reconnaissance tasks
---

## 🔧 Tools Required

- **Nmap** - Network mapper and port scanner ([Download](https://nmap.org/download.html))
- **Linux Terminal** or Command Prompt
- **VPN Connection** (for TryHackMe labs)
- Text editor for taking notes

### Installation

**Linux:**
```bash
sudo apt update
sudo apt install nmap
```

**Verify Installation:**
```bash
nmap --version
```

---

## 💻 Common Nmap Commands

```bash
# Basic host scan
nmap scanme.nmap.org

# OS detection
sudo nmap -O scanme.nmap.org

```

---

## ⚠️ Ethical Considerations

- **Only scan networks you own or have explicit permission to scan**
- Unauthorized network scanning is illegal in most jurisdictions
- Always use Nmap responsibly and ethically
- Respect the terms of service of TryHackMe labs
- Document your activities for educational purposes
---

## 📚 Additional Resources

- [Official Nmap Documentation](https://nmap.org/docs/)
- [TryHackMe - Nmap](https://tryhackme.com/)
- [OWASP Reconnaissance](https://owasp.org/www-project-web-security-testing-guide/)
