# souley393.github.io
HomeLab-V2
My Cybersecurity Home Lab
I started rebuilding my home lab because I wanted more hands-on experience with the things I'd been studying for Security+.
My goal is to build a small Windows domain environment, collect security logs, and practice investigating suspicious activity the way a SOC analyst would.
I'm using VMware Workstation, Windows Server 2022, a Windows client, Ubuntu Server, and Kali Linux.
The first part of the project focuses on networking. I configured a host-only network to keep the lab separated from my home network, assigned a static IP address to my Windows Server, and used PowerShell to verify connectivity.
I also ran into connectivity issues along the way. Rather than leave those out, I'm documenting what went wrong and how I fixed it.
This project is still in progress, and I'll update it as I complete each stage.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Hi there, I'm Souley 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&style=flat-square)](https://linkedin.com)
[![TikTok](https://img.shields.io/badge/TikTok-@zozobe48-black?logo=tiktok&style=flat-square)](https://www.tiktok.com/@zozobe48)
[![Security+](https://img.shields.io/badge/CompTIA-Security%2B-red?logo=comptia&style=flat-square)](https://www.credly.com)

**Cybersecurity Practitioner & SOC Analyst / Detection Engineering Enthusiast**

I specialize in building isolated enterprise lab environments, configuring detection telemetry, and analyzing simulated adversarial techniques. My focus is practical, verifiable technical execution—bridging the gap between foundational theory and hands-on detection engineering.

---

### 🛡️ Core Competencies & Tooling

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Virtualization & Systems** | VMware Workstation Pro, Ubuntu Server, Kali Linux, Windows Server & Active Directory |
| **Defensive & Monitoring** | Wazuh SIEM, Sysmon, Windows Event Forwarding (WEF), Group Policy Hardening |
| **Networking & Identity** | Isolated VMnet Architecture, Subnetting, Static IP Design, AD DS & Domain Hardening |
| **Security Standards** | MITRE ATT&CK Mapping, Incident Triage, SOC Alert Analysis |

---

### 🔬 Featured Projects & Lab Environments

#### 1. [Enterprise Active Directory & Hardened Domain Environment](https://github.com/souley393)
* **Architecture:** VMware isolated network with dedicated DC (Windows Server), domain-joined clients, and Kali attack node.
* **Key Tasks:** Implemented GPO baseline hardening, account privilege separation, and centralized DNS/DHCP infrastructure.
* **Artifacts:** Complete network topology diagrams and configuration walkthroughs.

#### 2. [Centralized SIEM & Telemetry Pipeline (Wazuh & Sysmon)](https://github.com/souley393)
* **Architecture:** Ubuntu Server running Wazuh Manager/Indexer/Dashboard collecting telemetry across Windows endpoints.
* **Key Tasks:** Custom Sysmon XML configuration tailored to detect privilege escalation, lateral movement, and suspicious process executions.
* **Validation:** Verified log ingestion and alert firing against simulated attacker techniques mapped to the MITRE ATT&CK framework.

---

### 📈 Proof of Work & Documentation
I believe in documenting every build and attack/defense scenario:
* 📝 **Technical Write-Ups:** Detailed step-by-step documentation and configuration manifests available in my repository tabs.
* 🎥 **Hands-on Proof:** Short walkthroughs and build verifications available on [TikTok (@zozobe48)](https://www.tiktok.com/@zozobe48).

---

### 📬 Connect With Me
* **LinkedIn:** [linkedin.com/in/your-profile](https://linkedin.com)
* **Portfolio / Site:** [souley393.github.io](https://souley393.github.io)
