# 📚 Resources & Useful Links

## 📋 Table of Contents
* [☁️ Azure](#️-azure)
* [🔑 Microsoft AD CS](#-microsoft-ad-cs)
* [🏛️ Microsoft AD DS](#️-microsoft-ad-ds)
* [🖥️ Microsoft Windows Server](#️-microsoft-windows-server)
* [🌐 PKI (Public Key Infrastructure)](#-pki-public-key-infrastructure)
* [📋 Zero Trust](#-zero-trust)
* [🐧 Linux - General](#-linux---general)
* [🐧 Linux - RHEL](#-linux---rhel)
* [⚙️ MISC](#️-misc)
* [💾 Veeam](#-veeam)
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

## 🔑 Microsoft AD CS
### 📋 Articles and Guides
* 📄 [Constraints what they are and how they're used](https://techcommunity.microsoft.com/blog/coreinfrastructureandsecurityblog/constraints-what-they-are-and-how-they8217re-used/1129048) – *Explains CAPolicy.inf constraints.*
* 📄 [The Microsoft Root Certificate Program](https://michaelwaterman.nl/2022/11/17/the-microsoft-root-certificate-program/) – *Overview of the Microsoft Root Certificate Program.*
* 🏛️ [Securing Public Key Infrastructure (PKI) - TechNet](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn786423(v=ws.11)) – *Legacy but fundamental documentation for PKI security.*
* 🔑 [Certificate Lifetime From a Risk based approache](https://michaelwaterman.nl/2026/02/23/pki-certificate-lifetimes-from-a-risk-based-approach/) – *What determines certificate lifetimes?*
* 📘 [Securing Public Key Infrastructure (PKI) Whitepaper](https://download.microsoft.com/download/0/F/A/0FA8C3B6-4792-43B2-8437-51C69F199701/Securing%20Public%20Key%20Infrastructure%20(PKI).docx) – *Official Microsoft Word document for securing PKI.*
* 🧼 [Removing Old CA Certificates](https://www.gradenegger.eu/en/removing-old-certification-authority-certificates-from-the-configuration-of-a-certification-authority/) – *How to remove old CA certificates from the Certification Authority configuration.*
* 📋 [CRL strategies](https://www.sysadmins.lv/retired-msft-blogs/xdot509/pki-design-considerations-certificate-revocation-and-crl-publishing-strategies.aspx) – *PKI Design Considerations: Certificate Revocation and CRL Publishing Strategies*

### 📜 Scripts
* ☁️ [Invoke-UpdateAzureBlobPKIStorage.ps1](https://github.com/dstreefkerk/PowerShell/blob/master/Microsoft%20ADCS/Invoke-UpdateAzureBlobPKIStorage.ps1) – *Script to upload ADCS files (e.g., CRLs) to Azure Blob Storage.*

[▲ Back to Top](#-table-of-contents)

---

## 🏛️ Microsoft AD DS
### 📋 Articles and Guides
* 📜 [Deep Dive: Active Directory LDAPS Certificate Selection](https://michaelwaterman.nl/2026/02/03/deep-dive-active-directory-ldaps-certificate-selection/) – *Deep Dive: Active Directory LDAPS Certificate Selection*
* 📜 [Build HA LDAPS](https://michaelwaterman.nl/2026/01/31/building-high-available-ldaps-architectures/) – *How to build High available LDAPS architectures*
* 🛡️ [DNS Zone Scope](https://learn.microsoft.com/en-us/powershell/module/dnsserver/get-dnsserverzonescope?view=windowsserver2025-ps) – *Create DNS rule what should answer cliens on DNS requests*
* 🛡️ [ADSecurity.org](https://adsecurity.org/) – *Classic go-to resource for Active Directory security.*
* 📜 [Modernizing RDP Certificates](https://michaelwaterman.nl/2026/02/08/modernizing-rdp-certificates/) – *Michael Waterman on modernizing RDP certificates.*
* 🔒 [Protecting Tier 0: The Modern Way](https://techcommunity.microsoft.com/blog/coreinfrastructureandsecurityblog/protecting-tier-0-the-modern-way/4052851) – *Official Microsoft guide on modern Tier 0 protection.*
* 🔑 [On-Prem Conditional Access](https://michaelwaterman.nl/2026/04/17/on-prem-conditional-access-you-never-knew-you-had/) – *On-premises conditional access features you might not know existed.*
* 🎓 [Prepare you for the APL-1008 Administer Active Directory Domain Services](https://learn.microsoft.com/en-us/training/paths/administer-active-directory-domain-services/) – *Administer Active Directory Domain Services.*

### 📜 Scripts
* 🛠️ [TierLevelIsolation Repository](https://github.com/Kili69/TierLevelIsolation) – *Main repository and root folder for tier-level isolation.*
* 🚀 [PAWDeploy (DeploymentBunny)](https://github.com/DeploymentBunny/PAWDeploy/blob/main/README.md) – *Implementation and deployment of Privileged Access Workstations.*
* ⚙️ [Build-Tier0-AuthPolicySilo.ps1](https://github.com/canix1/T0AuthSilo/blob/main/Build-Tier0-AuthPolicySilo.ps1) – *PowerShell script to build Authentication Policy Silos for Tier 0.*

[▲ Back to Top](#-table-of-contents)

---


## 🖥️ Microsoft Windows Server
### 📋 Articles and Guides
* 📄 [Automate WinRM on HTTPS](https://kb.ilves.se) – *Guide how to configure WinRM over HTTPS.*
* 🎞️ [Demystifying the Windows Firewall](https://www.youtube.com/watch?v=InPiE0EOArs) – *Learn how to irritate attackers without crippli*

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
* 🎞️ [TLS Handshake Deep Dive and decryption with Wireshark](https://www.youtube.com/watch?v=25_ftpJ-2ME&t) – *TLS Explained.*
* 🎞️ [What happens when a client connects?](https://youtu.be/C4Gtq5anlyc?si=pGrIfeUhyCTFJZIU) – *TLS Explained.*

### 📜 Scripts
* 🔒 [testssl.sh Repository](https://github.com/testssl/testssl.sh) – *Classic command-line tool to test TLS/SSL encryption on any port.*

[▲ Back to Top](#-table-of-contents)

---


## 📋 Zero Trust
### 📋 Articles and Guides
* 🎞️ [Implementing PAW](https://www.youtube.com/watch?v=lYVhwL11pMI) – *Implementing Privileged Access Workstations - Sami Laiho*


[▲ Back to Top](#-table-of-contents)

---

## 🐧 Linux - General
* ⚠️ [Linux Privilege Escalation (CVE-2026-31431)](https://guardsix.com/blog/linux-privilege-escalation-cve-2026-31431-copy-fail-exploit-and-detection) - *Copy Fail Exploit and Detection*
### 📜 Scripts
<details>
<summary>View Linux Scripts (Click to expand)</summary>

*No scripts saved yet.*
</details>

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


## ⚙️ MISC
### 📋 Articles and Guides
### 🛠️ Tools & Downloads
* 🛡️ [WatchGuard Software Downloads](https://software.watchguard.com/SoftwareDownloads?current=true&familyId=a2RVr000000bJA9MAM) – *Quick link to WatchGuard software updates.*

### 📜 Scripts & Applications
* 𝍂 [Create custom QR codes](https://rodtrent.substack.com/p/creating-custom-qr-codes-with-logos) – *QR Code Generator with Optional Logo.*
* 🔑 [PassPushPosh (New-Push.md)](https://github.com/adamburley/PassPushPosh/blob/main/Docs/New-Push.md) – *PowerShell module to interact with Password Pusher via API.*
* 💻 [pwpush-cli](https://github.com/pglombardo/pwpush-cli) – *CLI tool for Password Pusher to safely send passwords from the terminal.*
* 📂 [Filebrowser Repository](https://github.com/filebrowser/filebrowser?tab=readme-ov-file) – *A self-hosted web-based file manager interface.*

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


## 📝 Cheat Sheets

* ⌨️ [VS Code Keyboard Shortcuts for macOS (PDF)](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf) – *Official cheat sheet for VS Code shortcuts on Mac.*

[▲ Back to Top](#-table-of-contents)
