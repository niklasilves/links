# 📚 Resources & Useful Links

#### 📋 Table of Contents

- [☁️ Azure](#️-azure)
- [🔑 Microsoft AD CS](#-microsoft-ad-cs)
- [🏛️ Microsoft AD DS](#️-microsoft-ad-ds)
- [🖥️ Microsoft Windows Server](#️-microsoft-windows-server)
- [🌐 PKI (Public Key Infrastructure)](#-pki-public-key-infrastructure)
- [📋 Zero Trust](#-zero-trust)
- [🐧 Linux - General](#-linux---general)
- [🐧 Linux - RHEL](#-linux---rhel)
- [⚙️ MISC](#️-misc)
- [💾 Veeam](#-veeam)
- [📝 Cheat Sheets](#-cheat-sheets)

---

# ☁️ Azure

#### 📋 Articles & Guides

- 📄 **Azure Region Abbreviations**  
  https://www.jlaundry.nz/2022/azure_region_abbreviations/  
  *Quick reference guide for Azure region abbreviations.*  
  `Azure` `Regions`

- 🔒 **Identifying & Abusing Azure Arc**  
  https://www.ibm.com/think/x-force/identifying-abusing-azure-arc-for-hybrid-escalation-persistence  
  *IBM X-Force research on hybrid escalation and persistence.*  
  `AzureArc` `Security` `Hybrid`

- 🔒 **Azure Arc (Part 2): Cloud to On-Premises Escalation**  
  https://www.nsideattacklogic.de/azure-arc-part-2-escalation-from-cloud-to-on-premises/  
  *Technical deep dive into Azure Arc security.*  
  `AzureArc` `Escalation` `Security`

- 🛡️ **Using Authentication Mechanism Assurance (AMA)**  
  https://www.gradenegger.eu/en/using-authentication-mechanism-assurance-ama-to-secure-the-login-of-administrative-accounts/  
  *Securing administrative accounts using AMA.*  
  `AMA` `Authentication` `Security`

#### 📜 Scripts

<details>
<summary>View Azure Scripts</summary>

*No scripts saved yet.*

</details>

[▲ Back to Top](#-table-of-contents)

---

# 🔑 Microsoft AD CS

#### 📋 Articles & Guides

- 📄 **Moving Online Responder (OCSP) to Custom Web URL**  
  https://www.sysadmins.lv/blog-en/moving-online-responder-ocsp-to-custom-web-url.aspx  
  *Configure OCSP responder with custom web URL.*  
  `OCSP` `OnlineResponder` `PKI`

- 📄 **CodeSigning Timestamping Guide**  
  https://www.ssltrust.ca/help/setup-guides/program-signing-and-timestamping-with-signtool  
  *Program signing and timestamping using SignTool.*  
  `CodeSigning` `Timestamping` `SignTool`

- 📄 **SignTool Documentation**  
  https://learn.microsoft.com/en-us/windows/win32/seccrypto/signtool  
  *Microsoft SignTool command-line utility documentation.*  
  `CodeSigning` `SignTool` `Microsoft`

- 📄 **CodeSigning and AppLocker**  
  https://learn.microsoft.com/en-us/answers/questions/2154666/applocker-rules  
  *AppLocker behavior with code signing validation.*  
  `AppLocker` `CodeSigning` `Security`

- 📄 **CodeSigning Timestamping**  
  https://www.signfiles.com/timestamping/  
  *Timestamping services such as SignServer from Keyfactor.*  
  `Timestamping` `CodeSigning`

- 📄 **Constraints — What They Are and How They're Used**  
  https://techcommunity.microsoft.com/blog/coreinfrastructureandsecurityblog/constraints-what-they-are-and-how-they8217re-used/1129048  
  *Explains CAPolicy.inf constraints.*  
  `CAPolicy.inf` `Constraints` `PKI`

- 📄 **The Microsoft Root Certificate Program**  
  https://michaelwaterman.nl/2022/11/17/the-microsoft-root-certificate-program/  
  *Overview of the Microsoft Root Certificate Program.*  
  `RootCA` `Certificates` `Microsoft`

- 🏛️ **Securing Public Key Infrastructure (PKI) - TechNet**  
  https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn786423(v=ws.11)  
  *Legacy but fundamental PKI security documentation.*  
  `PKI` `Security` `Microsoft`

- 🔑 **Certificate Lifetime From a Risk Based Approach**  
  https://michaelwaterman.nl/2026/02/23/pki-certificate-lifetimes-from-a-risk-based-approach/  
  *What determines certificate lifetimes.*  
  `Certificates` `PKI` `Risk`

- 📘 **Securing Public Key Infrastructure (PKI) Whitepaper**  
  https://download.microsoft.com/download/0/F/A/0FA8C3B6-4792-43B2-8437-51C69F199701/Securing%20Public%20Key%20Infrastructure%20(PKI).docx  
  *Official Microsoft Word document for securing PKI.*  
  `Whitepaper` `PKI` `Security`

- 🧼 **Removing Old CA Certificates**  
  https://www.gradenegger.eu/en/removing-old-certification-authority-certificates-from-the-configuration-of-a-certification-authority/  
  *Remove old CA certificates from Certification Authority configuration.*  
  `Certificates` `Cleanup` `CA`

- 📋 **CRL Publishing Strategies**  
  https://www.sysadmins.lv/retired-msft-blogs/xdot509/pki-design-considerations-certificate-revocation-and-crl-publishing-strategies.aspx  
  *PKI design considerations for CRL publishing.*  
  `CRL` `Revocation` `PKI`

- 📋 **CRYPT_E_REVOCATION_OFFLINE**  
  https://www.gradenegger.eu/en/the-certification-authority-service-does-not-start-and-throws-the-error-message-0x80092013-2146885613-crypt_e_revocation_offline/  
  *Troubleshooting CA startup issues caused by revocation failures.*  
  `CRL` `Troubleshooting` `ADCS`

- 📋 **CodeSigning with Timestamp**  
  https://www.signfiles.com/timestamping/  
  *Application and services for timestamping in ADCS environments.*  
  `CodeSigning` `Timestamping` `ADCS`

#### 📜 Scripts

- ☁️ **Invoke-UpdateAzureBlobPKIStorage.ps1**  
  https://github.com/dstreefkerk/PowerShell/blob/master/Microsoft%20ADCS/Invoke-UpdateAzureBlobPKIStorage.ps1  
  *Upload ADCS files such as CRLs to Azure Blob Storage.*  
  `AzureBlob` `CRL` `PowerShell`

[▲ Back to Top](#-table-of-contents)

---

# 🏛️ Microsoft AD DS

#### 📋 Articles & Guides

- 📜 **Deep Dive: Active Directory LDAPS Certificate Selection**  
  https://michaelwaterman.nl/2026/02/03/deep-dive-active-directory-ldaps-certificate-selection/  
  *Detailed explanation of LDAPS certificate selection behavior.*  
  `LDAPS` `Certificates` `ADDS`

- 📜 **Build HA LDAPS**  
  https://michaelwaterman.nl/2026/01/31/building-high-available-ldaps-architectures/  
  *How to build highly available LDAPS architectures.*  
  `LDAPS` `HighAvailability` `ADDS`

- 🛡️ **DNS Zone Scope**  
  https://learn.microsoft.com/en-us/powershell/module/dnsserver/get-dnsserverzonescope?view=windowsserver2025-ps  
  *Create DNS rules controlling client DNS responses.*  
  `DNS` `ZoneScope` `PowerShell`

- 🛡️ **ADSecurity.org**  
  https://adsecurity.org/  
  *Classic go-to resource for Active Directory security.*  
  `ActiveDirectory` `Security`

- 📜 **Modernizing RDP Certificates**  
  https://michaelwaterman.nl/2026/02/08/modernizing-rdp-certificates/  
  *Modern approaches for RDP certificate management.*  
  `RDP` `Certificates` `Security`

- 🔒 **Protecting Tier 0: The Modern Way**  
  https://techcommunity.microsoft.com/blog/coreinfrastructureandsecurityblog/protecting-tier-0-the-modern-way/4052851  
  *Official Microsoft guidance for protecting Tier 0 assets.*  
  `Tier0` `Security` `Identity`

- 🔑 **On-Prem Conditional Access**  
  https://michaelwaterman.nl/2026/04/17/on-prem-conditional-access-you-never-knew-you-had/  
  *Hidden on-prem conditional access capabilities.*  
  `ConditionalAccess` `Authentication` `ADDS`

- 🎓 **APL-1008 — Administer Active Directory Domain Services**  
  https://learn.microsoft.com/en-us/training/paths/administer-active-directory-domain-services/  
  *Microsoft Learn path for AD DS administration.*  
  `Training` `ADDS` `MicrosoftLearn`

#### 📜 Scripts

- 🛠️ **TierLevelIsolation Repository**  
  https://github.com/Kili69/TierLevelIsolation  
  *Tier-level isolation implementation repository.*  
  `Tiering` `Security`

- 🚀 **PAWDeploy**  
  https://github.com/DeploymentBunny/PAWDeploy/blob/main/README.md  
  *Deployment and implementation of Privileged Access Workstations.*  
  `PAW` `Tier0` `Security`

- ⚙️ **Build-Tier0-AuthPolicySilo.ps1**  
  https://github.com/canix1/T0AuthSilo/blob/main/Build-Tier0-AuthPolicySilo.ps1  
  *Build Authentication Policy Silos for Tier 0.*  
  `Tier0` `PowerShell` `Authentication`

[▲ Back to Top](#-table-of-contents)

---

# 🖥️ Microsoft Windows Server

#### 📋 Articles & Guides

- 📄 **Automate WinRM on HTTPS**  
  https://kb.ilves.se  
  *Guide for configuring WinRM over HTTPS.*  
  `WinRM` `HTTPS` `PowerShell`

- 🎞️ **Demystifying the Windows Firewall**  
  https://www.youtube.com/watch?v=InPiE0EOArs  
  *Learn how to irritate attackers without crippling usability.*  
  `Firewall` `Security` `Windows`

#### 📜 Scripts

- ⏱️ **Optimize-TCPSettings.ps1**  
  https://gist.github.com/asheroto/942db6b331db8f070472990da6e6e1db  
  *Network performance optimization script for Windows.*  
  `TCP` `Performance` `PowerShell`

- ⏱️ **Set-WindowsTimeZone.ps1**  
  https://github.com/MSEndpointMgr/Intune/blob/master/Autopilot/Set-WindowsTimeZone.ps1  
  *Automatically set the Windows time zone based on location.*  
  `Timezone` `Windows` `Intune`

[▲ Back to Top](#-table-of-contents)

---

# 🌐 PKI (Public Key Infrastructure)

#### 📋 Articles & Guides

- 📰 **Why Let's Encrypt Retired OCSP**  
  https://www.linkedin.com/pulse/why-lets-encrypt-finally-retired-ocspand-whats-next-webpki-mallaya-99crc/  
  *Explains the retirement of OCSP and future WebPKI direction.*  
  `OCSP` `LetsEncrypt` `PKI`

- 📊 **Monitor PKI (aka.ms/monitorpki)**  
  https://aka.ms/monitorpki  
  *Microsoft shortcut link for PKI monitoring.*  
  `PKI` `Monitoring`

- 🛡️ **Securing PKI (aka.ms/securingpki)**  
  https://aka.ms/securingpki  
  *Microsoft shortcut link for PKI security recommendations.*  
  `PKI` `Security`

- 🥾 **Preparing VMware VMs for 2026 Secure Boot Expiration**  
  https://www.matthewschacherbauer.com/wp/2026/02/preparing-vmware-vms-for-the-2026-microsoft-secure-boot-certificate-expiration/  
  *Handling expired Secure Boot certificates on VMware VMs.*  
  `SecureBoot` `VMware` `Certificates`

- 🎞️ **TLS Handshake Deep Dive and Decryption with Wireshark**  
  https://www.youtube.com/watch?v=25_ftpJ-2ME&t  
  *TLS handshake explained in depth.*  
  `TLS` `Wireshark` `Encryption`

- 🎞️ **What Happens When a Client Connects?**  
  https://youtu.be/C4Gtq5anlyc?si=pGrIfeUhyCTFJZIU  
  *TLS connection process explained.*  
  `TLS` `Networking` `Encryption`

#### 📜 Scripts

- 🔒 **testssl.sh Repository**  
  https://github.com/testssl/testssl.sh  
  *Command-line tool to test TLS/SSL encryption on any port.*  
  `TLS` `SSL` `Security`

[▲ Back to Top](#-table-of-contents)

---

# 📋 Zero Trust

#### 📋 Articles & Guides

- 🎞️ **Implementing PAW**  
  https://www.youtube.com/watch?v=lYVhwL11pMI  
  *Implementing Privileged Access Workstations by Sami Laiho.*  
  `PAW` `Tier0` `Security`

[▲ Back to Top](#-table-of-contents)

---

# 🐧 Linux - General

#### 📋 Articles & Guides

- ⚠️ **Linux Privilege Escalation (CVE-2026-31431)**  
  https://guardsix.com/blog/linux-privilege-escalation-cve-2026-31431-copy-fail-exploit-and-detection  
  *Copy Fail exploit and detection techniques.*  
  `Linux` `PrivilegeEscalation` `CVE`

#### 📜 Scripts

<details>
<summary>View Linux Scripts</summary>

*No scripts saved yet.*

</details>

[▲ Back to Top](#-table-of-contents)

---

# 🐧 Linux - RHEL

#### 📜 Scripts

<details>
<summary>View RHEL Scripts</summary>

*No scripts saved yet.*

</details>

[▲ Back to Top](#-table-of-contents)

---

# ⚙️ MISC

#### 🛠️ Tools & Downloads

- 🛡️ **WatchGuard Software Downloads**  
  https://software.watchguard.com/SoftwareDownloads?current=true&familyId=a2RVr000000bJA9MAM  
  *Quick link to WatchGuard software updates.*  
  `WatchGuard` `Firewall` `Downloads`

#### 📜 Scripts & Applications

- 𝍂 **Create Custom QR Codes**  
  https://rodtrent.substack.com/p/creating-custom-qr-codes-with-logos  
  *QR code generator with optional logo support.*  
  `QRCode` `Tools`

- 🔑 **PassPushPosh (New-Push.md)**  
  https://github.com/adamburley/PassPushPosh/blob/main/Docs/New-Push.md  
  *PowerShell module for interacting with Password Pusher APIs.*  
  `PasswordPusher` `PowerShell`

- 💻 **pwpush-cli**  
  https://github.com/pglombardo/pwpush-cli  
  *CLI tool for securely sending passwords from terminal.*  
  `PasswordPusher` `CLI`

- 📂 **Filebrowser Repository**  
  https://github.com/filebrowser/filebrowser?tab=readme-ov-file  
  *Self-hosted web-based file manager interface.*  
  `FileManager` `SelfHosted`

[▲ Back to Top](#-table-of-contents)

---

# 💾 Veeam

#### 📋 Articles & Guides

- 🧱 **WORM Storage Hardening Guide**  
  https://bp.veeam.com/security/Design-and-implementation/Hardening/WORM_Storage_with_Veeam_Hardened_Repository.html  
  *Veeam best practices for hardened immutable repositories.*  
  `Veeam` `Immutable` `Backup`

- ℹ️ **Veeam KB4800**  
  https://www.veeam.com/kb4800  
  *Knowledge Base article for troubleshooting and configuration guidance.*  
  `Veeam` `KB` `Troubleshooting`

#### 📜 Scripts

<details>
<summary>View Veeam Scripts</summary>

*No scripts saved yet.*

</details>

[▲ Back to Top](#-table-of-contents)

---

# 📝 Cheat Sheets

- ⌨️ **VS Code Keyboard Shortcuts for macOS (PDF)**  
  https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf  
  *Official VS Code keyboard shortcut cheat sheet for macOS.*  
  `VSCode` `CheatSheet` `macOS`

[▲ Back to Top](#-table-of-contents)

