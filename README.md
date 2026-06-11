# 🛡️ eLearn Junior Penetration Tester (eJPT) 

<p align="center">

  <img src="EJPT_CERT.png" alt="eJPT Certificate" width="600">
</p>

Welcome to my official repository documenting my methodologies, toolset, and practical notes for the **eLearnSecurity Junior Penetration Tester (eJPT)** certification. 

This repository serves as a structured knowledge base for foundational penetration testing, encompassing network reconnaissance, vulnerability assessment, exploitation, and post-exploitation techniques.

> ⏱️ **Exam Overview:** The eJPT certification is a rigorous, 100% practical, hands-on assessment. I successfully completed this dynamic penetration testing exam over the course of a continuous **12-hour** session.

---

## 🎯 Core Competencies & Exam Domains

### 💥 Host and Network Penetration Testing (35%)
Focuses on the active exploitation phase, demonstrating the ability to compromise target systems and navigate through internal networks.
*   **Exploit Modification:** 🛠️ Identifying, analyzing, and modifying public exploits to function within specific target environments.
*   **Metasploit Framework:** 🧰 Conducting comprehensive exploitation, managing sessions, and utilizing auxiliary modules via `msfconsole`.
*   **Network Pivoting:** 🔀 Demonstrating lateral movement by adding internal routes and executing port forwarding to access isolated subnets.
*   **Credential Attacks:** 🔐 Conducting online brute-force password attacks (e.g., Hydra) and offline hash cracking (e.g., John the Ripper, Hashcat).

### 🔍 Assessment Methodologies (25%)
Covers the critical intelligence-gathering and reconnaissance phases required before launching an attack.
*   **Network Discovery:** 📡 Locating live endpoints and mapping out network architectures.
*   **Service Enumeration:** 🚪 Identifying open ports, running services, and specific versions on target machines.
*   **OS Fingerprinting:** 💻 Utilizing scanning techniques to determine the underlying operating systems of target hosts.
*   **OSINT (Open-Source Intelligence):** 🕵️‍♂️ Extracting critical company information, gathering employee email addresses, and compiling technical footprints from public sources.
*   **Vulnerability Identification:** 🚨 Identifying weaknesses in running services and evaluating the criticality, risk, and potential impact of those vulnerabilities.

### 📋 Host and Networking Auditing (25%)
Details the post-exploitation steps necessary to gather intelligence from compromised machines.
*   **Data Compilation:** 📄 Searching for and compiling sensitive information from files located on the target system.
*   **Network Auditing:** 🌐 Enumerating internal network configurations, routing tables, and ARP caches from local files.
*   **System Enumeration:** ⚙️ Gathering deep system information, including architecture, running processes, and installed software.
*   **Account Discovery:** 👤 Gathering local user account information, groups, and privileges on the target.
*   **File Transfers:** 🔄 Establishing reliable methods to securely transfer files to and from the target machine (e.g., Python web servers, FTP, SCP).
*   **Credential Harvesting:** 🔑 Dumping and gathering local password hashes and credential information from the compromised host.

### 🌐 Web Application Penetration Testing (15%)
Addresses the foundational assessment of web-based targets and services.
*   **Vulnerability Identification:** 🕷️ Identifying common web application flaws and misconfigurations.
*   **Directory Fuzzing:** 📂 Locating hidden files, backup archives, and unlinked directories using automated enumeration tools.
*   **Authentication Attacks:** 🔓 Conducting brute-force and dictionary attacks against web login portals.
*   **Web Reconnaissance:** 🔎 Conducting thorough footprinting of web applications to understand their underlying technologies and attack surface.

---
