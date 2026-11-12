# Hi, I'm Sakthi 👋

**Computer Engineering @ University of Maryland · Cybersecurity Specialization**

🔐 Security: threat modeling, firewall policy and packet-level troubleshooting, SSRF and prompt-injection defense

🐧 Systems: Linux, networking, AWS, Azure, Terraform, Kubernetes, and CI/CD pipelines

🤖 AI/ML: RAG agents, LLM-powered triage, and keeping models safe from untrusted input

🚀 Featured Projects
🧪 NukeSandbox · Security × Cloud × AI

A URL triage service that opens suspicious links in disposable, locked-down containers and turns what happens into plain-English risk reports with Gemini.

Runs each link in a capability-dropped, read-only container, with SSRF defenses like DNS pinning and per-hop redirect checks
Ships through GitHub Actions with pytest, Semgrep, and Trivy gates, then deploys to Azure Container Apps via Terraform and OIDC with no stored credentials
An alternate Kubernetes path adds Cosign signing, SPDX SBOMs, and Prometheus/Grafana monitoring
🧪 Homelab · Linux × Networking

Two RHEL 10 VMs where one server is the other's entire network: router, firewall, DHCP, DNS, and NAT. Each challenge breaks one piece on purpose, then traces the failure with packet captures and logs.

Traced where packets stopped when forwarding and NAT were removed, and why one failed instantly while the other timed out
Measured TCP slowing ~230× at 10% packet loss, with most of the time spent waiting on retransmission timeouts
Fixed a path MTU black hole that broke TLS handshakes, cutting a failing upload from a 15 s timeout to 0.19 s
🔐 cryptX · Hardware × Web × AI

A hardware crypto wallet and dashboard built at Bitcamp 2026 (Best Capital One Hack). Team project; my contributions are listed in the repo.

Arduino-based wallet that keeps private keys on-chip and requires a physical button press for every transaction
Next.js dashboard connected over WebSockets, with device authentication via challenge-response
Gemini + MongoDB pipeline that flags suspicious device activity and maps it to MITRE ATT&CK

## 💼 Currently
**DevOps Engineer @ MITRE** (via UMD App Dev Club): containerizing and designing AWS infrastructure for SCOUT, a cyber-policy platform for State Department missions, and building a RAG agent that maps global cyber policies by country and category.


---

## 🛠️ Tech Stack

| Category | Tools |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![Java](https://img.shields.io/badge/-Java-ED8B00?logo=openjdk&logoColor=white) ![C++](https://img.shields.io/badge/-C%2B%2B-00599C?logo=c%2B%2B&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/-Bash-4EAA25?logo=gnubash&logoColor=white) ![PowerShell](https://img.shields.io/badge/-PowerShell-5391FE?logo=powershell&logoColor=white) |
| **Cloud & DevOps** | ![AWS](https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0089D6?logo=microsoft-azure&logoColor=white) ![Terraform](https://img.shields.io/badge/-Terraform-844FBA?logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?logo=kubernetes&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black) |
| **Security** | ![Wireshark](https://img.shields.io/badge/-Wireshark-1679A7?logo=wireshark&logoColor=white) ![Ghidra](https://img.shields.io/badge/-Ghidra-C8102E) ![Kali Linux](https://img.shields.io/badge/-Kali_Linux-557C94?logo=kalilinux&logoColor=white) ![Semgrep](https://img.shields.io/badge/-Semgrep-2D3748?logo=semgrep&logoColor=white) ![Trivy](https://img.shields.io/badge/-Trivy-1904DA) ![MITRE ATT&CK](https://img.shields.io/badge/-MITRE_ATT%26CK-B22222) |
| **Web & AI** | ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/-Next.js-000000?logo=nextdotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white) ![Gemini API](https://img.shields.io/badge/-Gemini_API-8E75B2?logo=googlegemini&logoColor=white) ![Arduino](https://img.shields.io/badge/-Arduino-00878F?logo=arduino&logoColor=white) |

---

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=SakthiS-oss&layout=compact&theme=dracula&count_private=true&hide_progress=false" alt="Top Languages" />
</p>

## 📫 Connect
<p align="center">
  <a href="https://linkedin.com/in/sakthi-sadayappan">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:sakthi.sadayappan1@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=SakthiS-oss&layout=compact&theme=dracula&count_private=true&hide_progress=false" alt="Top Languages" />
</p>

## 📫 Connect
<p align="center">
  <a href="https://linkedin.com/in/sakthi-sadayappan">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:sakthi.sadayappan1@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>
