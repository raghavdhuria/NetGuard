[![GitHub issues](https://img.shields.io/github/issues/skavngr/netguard.svg?color=red)](https://github.com/skavngr/netguard/issues)
[![GitHub issues closed](https://img.shields.io/github/issues-closed/skavngr/netguard.svg?color=green)](https://github.com/skavngr/netguard/issues)
[![GitHub forks](https://img.shields.io/github/forks/skavngr/netguard.svg?color=yellow)](https://github.com/skavngr/netguard/network)
[![GitHub stars](https://img.shields.io/github/stars/skavngr/netguard.svg?color=orange)](https://github.com/skavngr/netguard/stargazers)
[![GitHub license](https://img.shields.io/github/license/skavngr/netguard.svg?color=blue)](https://github.com/skavngr/netguard/blob/master/LICENSE)

# 🛡️ NetGuard v1.2 — _Unified Web Vulnerability Scanner_

**NetGuard** is an automated security scanner that performs intelligent, multi-tool vulnerability assessments on web targets.  
_Python 3 is now fully supported in version 1.2 — legacy Python 2.7 users may refer to v1.1 (archived)._

---

## 🚀 Why NetGuard?

Security professionals often juggle multiple tools manually to run web reconnaissance and vulnerability checks. This is time-consuming and error-prone. **NetGuard** streamlines this process by coordinating several established tools into a single workflow, helping detect vulnerabilities faster and with better context.

Whether you're auditing a single app or performing a quick recon, **NetGuard** helps you focus on what matters: the results.

---

## ⚙️ Key Capabilities

- 📦 **Effortless setup** — Clone and run.
- 🤖 **Runs numerous security scanners behind the scenes**, along with custom scripts for extended checks.
- 🔧 Combines tools like `nmap`, `dnsrecon`, `wafw00f`, `sslyze`, `theHarvester`, `amass`, `nikto`, and more.
- 🧠 **Cross-validates results** using different tools to minimize false positives.
- ⚡ **Lightweight**, non-blocking, and resource-efficient.
- ⏱️ Clear **indicators for time-heavy scans** — skip or interrupt when needed.
- 🛡️ Categorizes vulnerabilities by **severity**: Critical, High, Medium, Low, Informational.
- 📚 Includes **descriptions, risk impacts, and remediation tips** for each finding.
- 📝 **Summary reporting** to get a high-level view of your scan.
- 🧩 **Smart scanning triggers**: e.g., auto-runs `wpscan` if WordPress is detected. (_coming soon_)
- 📄 Generates **comprehensive reports** in PDF format. (_coming soon_)
- 🎯 Integrates **Metasploit modules** for deeper scanning. (_coming soon_)

---

## 🔍 Tests Performed

- ✔️ Detection of Load Balancers & WAFs
- ✔️ CMS Fingerprinting (WordPress, Joomla, Drupal)
- ✔️ SSL/TLS Vulnerabilities: HEARTBLEED, POODLE, FREAK, CCS, LOGJAM, etc.
- ✔️ Port Scanning & Open Service Checks
- ✔️ DNS Zone Transfers (`Fierce`, `DNSRecon`, etc.)
- ✔️ Subdomain Enumeration (`amass`, `nikto`, etc.)
- ✔️ Directory/File Brute-Forcing
- ✔️ Web App Vulns: XSS, SQLi, LFI/RFI, RCE, and more
- ✔️ Basic DoS Simulation (e.g., Slowloris)

_> Additional vulnerability modules in progress._

---

## 🖥️ System Requirements

- **Python 3**
- Recommended OS: **Kali Linux** (pre-bundled tools)
- Also tested on **Parrot OS** and **Ubuntu**
