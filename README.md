<h1 align="center">Hi, I'm Wenteng 👋</h1>
<p align="center">
  🎓 B.S. Computer Science, University of Central Florida (UCF) · 🌍 Based in Orlando, Florida
  <br/>
  🔐 CompTIA Security+ (SY0-701) · 💻 Interested in: CYBERSECURITY · IT / CLOUD ADMINISTRATION · SOFTWARE DEV
</p>

---

## 📂 Projects

### 🔹 [Microsoft 365 Tenant Deployment — Simulated MSP Client Engagement](https://github.com/WentengLin/m365-tenant-deployment)
**Tools & Skills:** Microsoft 365, Entra ID, Conditional Access, Intune (MDM), Exchange Online, Defender for Office 365, PowerShell, BitLocker

**Key features:**
- Deployed a Microsoft 365 Business Premium tenant for an 11-user simulated SMB client — 13 identities, 8 groups, group-based licensing, and a least-privilege admin model with a monitored break-glass account
- Staged 5 Conditional Access policies in report-only mode before enforcement to validate impact without locking out users
- Enrolled and managed a Windows 11 endpoint in Intune with a 15-setting compliance policy, hardening baseline, and Required app deployment — verifying each control at the endpoint rather than the admin console
- Diagnosed a false-positive BitLocker compliance check where `Get-BitLockerVolume` showed zero key protectors and protection disabled; remediated in PowerShell and escrowed the recovery key to Entra ID
- Executed a timed offboarding procedure — 3:59 to account containment, 11:33 end to end including mailbox conversion, delegation, and automated license reclamation — and authored 6 operational runbooks

---

### 🔹 [Active Directory Lab — Domain Services & Group Policy](https://github.com/WentengLin/Active-Directory-Home-Lab)
**Tools & Skills:** Windows Server 2022, Windows 11, Active Directory, DNS, Group Policy, nslookup / ping / gpupdate

**Key features:**
- Built a Windows Active Directory environment with a Server 2022 domain controller and a domain-joined Windows 11 client
- Configured DNS and user authentication, then created and tested Group Policy Objects against the client
- Troubleshot connectivity, secure channel, and policy application issues using `nslookup`, `ping`, and `gpupdate`

---

### 🔹 [Python Vulnerability Scanner](https://github.com/WentengLin/VulnerabilityScanner)
**Tools & Skills:** Python, Sockets, Networking, Security, JSON/CSV, Argparse

**Key features:**
- Created a Python tool that performs TCP port scanning and banner grabbing using raw sockets
- Implemented CVE lookup via JSON fingerprints to identify vulnerable services
- Added CLI support with argparse and export to JSON/CSV
- Used networking fundamentals like timeouts, socket errors, TCP handshakes, and service probing

---

### 🔹 [Static Malware Analyzer](https://github.com/WentengLin/StaticMalwareAnalyzer)
**Tools & Skills:** Python, Malware Analysis, Static Analysis, pefile, Regex, Security, JSON, Argparse

**Key features:**
- Built a Python-based static malware analysis tool to inspect executable files without execution
- Extracted file metadata and cryptographic hashes (MD5, SHA1, SHA256) for malware identification
- Parsed Windows PE imports using pefile and flagged suspicious API calls commonly used by malware
- Implemented string extraction and regex-based IOC detection (IPs, domains, URLs) with structured JSON output

---

### 🔹 [Password Strength Analyzer and Hashing Tool](https://github.com/WentengLin/PasswordAnalyzer)
**Tools & Skills:** Python, hashlib, SHA-256, Base64

**Key features:**
- Developed a Python-based password analyzer that evaluates strength (length, character types, sequences, repetition) and prints human-readable security recommendations
- Implemented salted SHA-256 hashing and Base64 encoding for secure password storage and verification

---

## 📫 Contact
- ✉️ Email: wenteng9@gmail.com
- 💼 LinkedIn: [Wenteng Lin](https://www.linkedin.com/in/wenteng-lin-a7b974242/)
