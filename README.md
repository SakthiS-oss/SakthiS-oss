# Hi, I'm Sakthi 👋

**Computer Engineering @ University of Maryland · Cybersecurity Specialization**

I build systems where security, cloud, hardware, and AI work together, from private keys that never leave a microcontroller to sandboxes that let an LLM read hostile web content safely.

- 🔐 **Security:** threat modeling, SSRF and prompt-injection defense, detection mapped to MITRE ATT&CK
- ☁️ **Cloud:** AWS, Azure, Terraform, Kubernetes, and CI/CD pipelines that sign what they ship
- 📟 **Hardware:** embedded C++ and how hardware draws trust boundaries
- 🤖 **AI/ML:** RAG agents, LLM-powered triage, and keeping models safe from untrusted input
- 🛠️ **Software:** full-stack apps with TypeScript, React, and Python

---

## 🚀 Featured Projects

### 🧪 [NukeSandbox](https://github.com/SakthiS-oss/NukeSandbox) · Security × Cloud × AI
A URL triage service that analyzes links in disposable, capability-dropped, read-only containers and turns the telemetry into plain-English reports with Gemini.
- Blocks SSRF with DNS pinning and per-hop redirect checks against private and cloud-metadata addresses
- Fences hostile page content off from the LLM to prevent prompt injection
- Ships through GitHub Actions with Semgrep, Trivy, SBOMs, and Cosign signing, then deploys to Azure Container Apps via Terraform with OIDC and no stored secrets

### 🔐 [cryptX](https://github.com/SakthiS-oss/cryptX) · Hardware × Security × AI
A hardware crypto wallet built around a compromised-host threat model.
🏆 **Best Capital One Financial Hack + 2nd in App Dev, Bitcamp 2026**
- Generates BIP-39 seeds and stores private keys on the microcontroller, so key material never touches the host
- Authenticates devices with a SipHash challenge-response and requires physical on-device confirmation for every transaction
- Flags potentially compromised devices with a Gemini + MongoDB anomaly detection pipeline mapped to MITRE ATT&CK

---

## 💼 Currently
**DevOps Engineer @ MITRE** (via UMD App Dev Club): containerizing and designing AWS infrastructure for SCOUT, a cyber-policy platform for State Department missions, and building a RAG agent that maps global cyber policies by country and category.


## 🛠️ Tech Stack

| Category | Tools |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![C++](https://img.shields.io/badge/-C%2B%2B-00599C?logo=c%2B%2B&logoColor=white) ![Java](https://img.shields.io/badge/-Java-ED8B00?logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/-Bash-4EAA25?logo=gnubash&logoColor=white) ![PowerShell](https://img.shields.io/badge/-PowerShell-5391FE?logo=powershell&logoColor=white) |
| **Security** | ![Wireshark](https://img.shields.io/badge/-Wireshark-1679A7?logo=wireshark&logoColor=white) ![Burp Suite](https://img.shields.io/badge/-Burp_Suite-FF6633?logo=burpsuite&logoColor=white) ![Ghidra](https://img.shields.io/badge/-Ghidra-C8102E) ![Kali Linux](https://img.shields.io/badge/-Kali_Linux-557C94?logo=kalilinux&logoColor=white) ![Semgrep](https://img.shields.io/badge/-Semgrep-2D3748?logo=semgrep&logoColor=white) ![Trivy](https://img.shields.io/badge/-Trivy-1904DA) ![MITRE ATT&CK](https://img.shields.io/badge/-MITRE_ATT%26CK-B22222) |
| **Cloud & DevSecOps** | ![AWS](https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0089D6?logo=microsoft-azure&logoColor=white) ![Terraform](https://img.shields.io/badge/-Terraform-844FBA?logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?logo=kubernetes&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black) |
| **AI/ML** | ![Gemini API](https://img.shields.io/badge/-Gemini_API-8E75B2?logo=googlegemini&logoColor=white) ![RAG](https://img.shields.io/badge/-RAG_Agents-4B5563) ![Vector DB](https://img.shields.io/badge/-Vector_Databases-4B5563) |
| **Hardware & Software** | ![Arduino](https://img.shields.io/badge/-Arduino-00878F?logo=arduino&logoColor=white) ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/-Next.js-000000?logo=nextdotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white) |

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
