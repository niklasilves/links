# 📚 Resources & Useful Links

## 📋 Table of Contents
* [☁️ Azure](#️-azure)
* [🏛️ Microsoft AD DS](#️-microsoft-ad-ds)
* [🔑 Microsoft AD CS](#-microsoft-ad-cs)
* [🖥️ Microsoft Windows Server](#️-microsoft-windows-server)
* [🌐 PKI (Public Key Infrastructure)](#-pki-public-key-infrastructure)
* [🐧 Linux - RHEL](#-linux---rhel)
* [🐧 Linux - General](#-linux---general)
* [💾 Veeam](#-veeam)
* [⚙️ MISC](#️-misc)
* [📝 Cheat Sheets](#-cheat-sheets)

---

## ☁️ Azure

### 📋 Articles and Guides
* 📄 [Azure Region Abbreviations](https://www.jlaundry.nz/2022/azure_region_abbreviations/) – *Quick reference guide for Azure region abbreviations.*
* 🔒 [Identifying & Abusing Azure Arc](https://www.ibm.com/think/x-force/identifying-abusing-azure-arc-for-hybrid-escalation-persistence) – *IBM X-Force research on hybrid escalation and persistence.*
* 🔒 [Azure Arc (Part 2): Cloud to On-Premises Escalation](https://www.nsideattacklogic.de/azure-arc-part-2-escalation-from-cloud-to-on-premises/) – *Technical deep dive into Azure Arc security.*
* 🛡️ [Using Authentication Mechanism Assurance (AMA)](https://www.gradenegger.eu/en/using-authentication-mechanism-assurance-ama-to-secure-the-login-of-administrative-accounts/) – *Securing administrative accounts using AMA.*

### 📜 Scripts
<details>
<summary>View Azure Scripts (Click to expand)</summary>

*No scripts saved yet.*
</details>

[▲ Back to Top](#-table-of-contents)

---

## 🏛️ Microsoft AD DS

### 📋 Articles and Guides
* 🛡️ [ADSecurity.org](https://adsecurity.org/) – *Classic go-to resource for Active Directory security.*
* 📜 [Modernizing RDP Certificates](https://michaelwaterman.nl/2026/02/08/modernizing-rdp-certificates/) – *Michael Waterman on modernizing RDP certificates.*
* 🔒 [Protecting Tier 0: The Modern Way](https://techcommunity.microsoft.com/blog/coreinfrastructureandsecurityblog/protecting-tier-0-the-modern-way/4052851) – *Official Microsoft guide on modern Tier 0 protection.*
* 🔑 [On-Prem Conditional Access](https://michaelwaterman.nl/2026/04/17/on-prem-conditional-access-you-never-knew-you-had/) – *On-premises conditional access features you might not know existed.*

### 📜 Scripts
* 🛠️ [TierLevelIsolation Repository](https://github.com/Kili69/TierLevelIsolation) – *Main repository and root folder for tier-level isolation.*
* 🚀 [PAWDeploy (DeploymentBunny)](https://github.com/DeploymentBunny/PAWDeploy/blob/main/README.md) – *Implementation and deployment of Privileged Access Workstations.*
* ⚙️ [Build-Tier0-AuthPolicySilo.ps1](https://github.com/canix1/T0AuthSilo/blob/main/Build-Tier0-AuthPolicySilo.ps1) – *PowerShell script to build Authentication Policy Silos for Tier 0.*

[▲ Back to Top](#-table-of-contents)

---

## 🔑 Microsoft AD CS

### 📋 Articles and Guides
* 📄 [The Microsoft Root Certificate Program](https://michaelwaterman.nl/2022/11/17/the-microsoft-root-certificate-program/) – *Overview of the Microsoft Root Certificate Program.*
* 🏛️ [Securing Public Key Infrastructure (PKI) - TechNet](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn786423(v=ws.11)) – *Legacy but fundamental documentation for PKI security.*
* 📘 [Securing Public Key Infrastructure (PKI) Whitepaper](https://download.microsoft.com/download/0/F/A/0FA8C3B6-4792-43B2-8437-51C69F199701/Securing%20Public%20Key%20Infrastructure%20(PKI).docx) – *Official Microsoft Word document for securing PKI.*
* 🧼 [Removing Old CA Certificates](https://www.gradenegger.eu/en/removing-old-certification-authority-certificates-from-the-configuration-of-a-certification-authority/) – *How to remove old CA certificates from the Certification Authority configuration.*

### 📜 Scripts
* ☁️ [Invoke-UpdateAzureBlobPKIStorage.ps1](https://github.com/dstreefkerk/PowerShell/blob/master/Microsoft%20ADCS/Invoke-UpdateAzureBlobPKIStorage.ps1) – *Script to upload ADCS files (e.g., CRLs) to Azure Blob Storage.*

[▲ Back to Top](#-table-of-contents)

---

## 🖥️ Microsoft Windows Server

### 📜 Scripts
* ⏱️ [Set-WindowsTimeZone.ps1 (Gist)](https://gist.github.com/asheroto/942db6b331db8f070472990da6e6e1db) – *Gist to automatically set the time zone based on location.*

[▲ Back to Top](#-table-of-contents)

---

## 🌐 PKI (Public Key Infrastructure)

### 📋 Articles and Guides
* 📰 [Why Let's Encrypt Retired OCSP](https://www.linkedin.com/pulse/why-lets-encrypt-finally-retired-ocspand-whats-next-webpki-mallaya-99crc/) – *LinkedIn article explaining the retirement of OCSP and what comes next.*
* 📊 [Monitor PKI (aka.ms/monitorpki)](https://aka.ms/monitorpki) – *Microsoft shortcut link for PKI monitoring.*
* 🛡️ [Securing PKI (aka.ms/securingpki)](https://aka.ms/securingpki) – *Microsoft shortcut link for PKI security recommendations.*
* 🥾 [Preparing VMware VMs for 2026 Secure Boot Expiration](https://www.matthewschacherbauer.com/wp/2026/02/preparing-vmware-vms-for-the-2026-microsoft-secure-boot-certificate-expiration/) – *Guide on handling expired Secure Boot certificates on VMware VMs.*

### 📜 Scripts
* 🔒 [testssl.sh Repository](https://github.com/testssl/testssl.sh) – *Classic command-line tool to test TLS/SSL encryption on any port.*

[▲ Back to Top](#-table-of-contents)

---

## 🐧 Linux - RHEL

### 📜 Scripts
<details>
<summary>View RHEL Scripts (Click to expand)</summary>

*No scripts saved yet.*
</details>

[▲ Back to Top](#-table-of-contents)

---

## 🐧 Linux - General

### 📜 Scripts
<details>
<summary>View Linux Scripts (Click to expand)</summary>

*No scripts saved yet.*
</details>

[▲ Back to Top](#-table-of-contents)

---

## 💾 Veeam

### 📋 Articles and Guides
* 🧱 [WORM Storage Hardening Guide](https://bp.veeam.com/security/Design-and-implementation/Hardening/WORM_Storage_with_Veeam_Hardened_Repository.html) – *Veeam Best Practices for setting up a Hardened Repository (immutability).*
* ℹ️ [Veeam KB4800](https://www.veeam.com/kb4800) – *Knowledge Base article for specific Veeam configurations and troubleshooting.*

### 📜 Scripts
<details>
<summary>View Veeam Scripts (Click to expand)</summary>

*No scripts saved yet.*
</details>

[▲ Back to Top](#-table-of-contents)

---

## ⚙️ MISC

### 📋 Tools & Downloads
* 🛡️ [WatchGuard Software Downloads](https://software.watchguard.com/SoftwareDownloads?current=true&familyId=a2RVr000000bJA9MAM) – *Quick link to WatchGuard software updates.*

### 📜 Scripts & Applications
* 🔑 [PassPushPosh (New-Push.md)](https://github.com/adamburley/PassPushPosh/blob/main/Docs/New-Push.md) – *PowerShell module to interact with Password Pusher via API.*
* 💻 [pwpush-cli](https://github.com/pglombardo/pwpush-cli) – *CLI tool for Password Pusher to safely send passwords from the terminal.*
* 📂 [Filebrowser Repository](https://github.com/filebrowser/filebrowser?tab=readme-ov-file) – *A self-hosted web-based file manager interface.*

[▲ Back to Top](#-table-of-contents)

---

## 📝 Cheat Sheets

* ⌨️ [VS Code Keyboard Shortcuts for macOS (PDF)](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf) – *Official cheat sheet for VS Code shortcuts on Mac.*

[▲ Back to Top](#-table-of-contents)
