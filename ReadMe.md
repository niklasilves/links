# 📚 Resources & Useful Links

###### 📋 Table of Contents

- [🔐 Identity & Authentication](#-identity--authentication)
- [🌐 PKI & Certificates](#-pki--certificates)
- [☁️ Cloud & Hybrid](#️-cloud--hybrid)
- [🛡️ Security & Hardening](#️-security--hardening)
- [🖥️ Windows Infrastructure](#️-windows-infrastructure)
- [🐧 Linux](#-linux)
- [💾 Backup & Recovery](#-backup--recovery)
- [⚙️ Tools & Utilities](#️-tools--utilities)
- [📜 Scripts & Automation](#-scripts--automation)
- [🎓 Learning & References](#-learning--references)

---

# 🔐 Identity & Authentication

- 🛡️ **Kerberos clients allow IPv4 and IPv6 address hostnames in Service Principal Names (SPNs)**
  https://learn.microsoft.com/en-us/windows-server/security/kerberos/configuring-kerberos-over-ip
  *Kerberos clients can be configured to support IPv4 and IPv6 hostnames in SPNs.*
  `kerberos` `Authentication` `ADDS` `SPN`

- 🛡️ **Using Authentication Mechanism Assurance (AMA)**
  https://www.gradenegger.eu/en/using-authentication-mechanism-assurance-ama-to-secure-the-login-of-administrative-accounts/
  *Securing administrative accounts using AMA.*
  `AMA` `Authentication` `Security`

- 📜 **Detecting weak passwords in Active Directory**
  https://michaelwaterman.nl/2025/04/10/detecting-weak-passwords-in-active-directory/
  *Detect weak passwords using AD snapshots and DSInternals.*
  `Passwords` `ADDS` `Security`

- 📜 **Deep Dive: Active Directory LDAPS Certificate Selection**
  https://michaelwaterman.nl/2026/02/03/deep-dive-active-directory-ldaps-certificate-selection/
  *Detailed explanation of LDAPS certificate selection behavior.*
  `LDAPS` `Certificates`

- 📜 **Build HA LDAPS**
  https://michaelwaterman.nl/2026/01/31/building-high-available-ldaps-architectures/
  *How to build highly available LDAPS architectures.*
  `LDAPS` `HighAvailability`

- 🔒 **Protecting Tier 0: The Modern Way**
  https://techcommunity.microsoft.com/blog/coreinfrastructureandsecurityblog/protecting-tier-0-the-modern-way/4052851
  *Official Microsoft guidance for protecting Tier 0 assets.*
  `Tier0` `Security`

- 🔑 **On-Prem Conditional Access**
  https://michaelwaterman.nl/2026/04/17/on-prem-conditional-access-you-never-knew-you-had/
  *Hidden on-prem conditional access capabilities.*
  `ConditionalAccess` `Authentication`

- 🛡️ **ADSecurity.org**
  https://adsecurity.org/
  *Classic resource for Active Directory security.*
  `ADDS` `Security`

- 🛡️ **Step-by-Step Guide to Windows Event Forwarding and NTLMv1 Monitoring**
  https://michaelwaterman.nl/2024/06/29/step-by-step-guide-to-windows-event-forwarding-and-ntlmv1-monitoring/
  *Monitory legacy NTLM activity in active directoyr.*
  `ADDS` `Security` `Audit` `ntlm`

[▲ Back to Top](#-table-of-contents)

---

# 🌐 PKI & Certificates

- 📄 **AWindows PKI Documentation Reference and Library**
  https://aka.ms/pkilibrary
  *Microsoft documentation on PKI and ADCS.*
  `abuse` `PKI` `ADCS` `ESC` 

- 📄 **Abusing Active Directory Certificate Services**
  https://specterops.io/wp-content/uploads/sites/3/2022/06/Certified_Pre-Owned.pdf
  *Vulnerability descibed and how to manage them.*
  `abuse` `PKI` `ADCS` `ESC` 

- 📄 **Active Directory - Certificate ESC Attacks**
  https://swisskyrepo.github.io/InternalAllTheThings/active-directory/ad-adcs-esc/
  *Vulnerability descibed and how to manage them.*
  `abuse` `PKI` `ADCS` `ESC` 

- 📄 **Breaking ADCS: ESC1 to ESC16 Attack Techniques**
  https://xbz0n.sh/blog/adcs-complete-attack-reference
  *Vulnerability descibed and how to manage them.*
  `abuse` `PKI` `ADCS` `ESC` 

- 📄 **Configuring the Trusted Platform Module (TPM)**
  https://www.gradenegger.eu/en/configuring-the-trusted-platform-module-tpm-key-attestation/
  *Private keys for certificates are protected with a - if available - Trusted Platform Module (TPM).*
  `TPM` `PKI` `Key Attestation` 

- 📄 **Moving Online Responder (OCSP) to Custom Web URL**
  https://www.sysadmins.lv/blog-en/moving-online-responder-ocsp-to-custom-web-url.aspx
  *Configure OCSP responder with custom web URL.*
  `OCSP` `PKI`

- 📄 **CodeSigning Timestamping Guide**
  https://www.ssltrust.ca/help/setup-guides/program-signing-and-timestamping-with-signtool
  *Program signing and timestamping using SignTool.*
  `CodeSigning` `SignTool`

- 📄 **SignTool Documentation**
  https://learn.microsoft.com/en-us/windows/win32/seccrypto/signtool
  *Microsoft SignTool documentation.*
  `CodeSigning`

- 📄 **CodeSigning and AppLocker**
  https://learn.microsoft.com/en-us/answers/questions/2154666/applocker-rules
  *AppLocker behavior with signed applications.*
  `CodeSigning` `AppLocker`

- 📄 **CodeSigning Timestamping**
  https://www.signfiles.com/timestamping/
  *Timestamping services and recommendations.*
  `Timestamping`

- 📄 **Constraints — What They Are and How They're Used**
  https://techcommunity.microsoft.com/blog/coreinfrastructureandsecurityblog/constraints-what-they-are-and-how-they8217re-used/1129048
  *Explains CAPolicy.inf constraints.*
  `CAPolicy.inf`

- 📄 **The Microsoft Root Certificate Program**
  https://michaelwaterman.nl/2022/11/17/the-microsoft-root-certificate-program/
  *Overview of the Microsoft Root Certificate Program.*
  `RootCA`

- 🏛️ **Securing Public Key Infrastructure (PKI) - TechNet**
  https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn786423(v=ws.11)
  *Fundamental PKI security guidance.*
  `PKI` `Security`

- 🔑 **Certificate Lifetime From a Risk Based Approach**
  https://michaelwaterman.nl/2026/02/23/pki-certificate-lifetimes-from-a-risk-based-approach/
  *Certificate lifetime considerations.*
  `Certificates`

- 📘 **Securing Public Key Infrastructure (PKI) Whitepaper**
  https://download.microsoft.com/download/0/F/A/0FA8C3B6-4792-43B2-8437-51C69F199701/Securing%20Public%20Key%20Infrastructure%20(PKI).docx
  *Official Microsoft PKI whitepaper.*
  `Whitepaper`

- 🧼 **Removing Old CA Certificates**
  https://www.gradenegger.eu/en/removing-old-certification-authority-certificates-from-the-configuration-of-a-certification-authority/
  *Remove old CA certificates safely.*
  `CA` `Cleanup`

- 📋 **CRL Publishing Strategies**
  https://www.sysadmins.lv/retired-msft-blogs/xdot509/pki-design-considerations-certificate-revocation-and-crl-publishing-strategies.aspx
  *PKI design considerations for CRLs.*
  `CRL`

- 📋 **CRYPT_E_REVOCATION_OFFLINE**
  https://www.gradenegger.eu/en/the-certification-authority-service-does-not-start-and-throws-the-error-message-0x80092013-2146885613-crypt_e_revocation_offline/
  *Troubleshooting CA revocation failures.*
  `CRL` `Troubleshooting`

- 📰 **Why Let's Encrypt Retired OCSP**
  https://www.linkedin.com/pulse/why-lets-encrypt-finally-retired-ocspand-whats-next-webpki-mallaya-99crc/
  *Why OCSP is disappearing from modern PKI.*
  `OCSP`

- 📊 **Monitor PKI**
  https://aka.ms/monitorpki
  *Microsoft PKI monitoring guidance.*
  `Monitoring`

- 🛡️ **Securing PKI**
  https://aka.ms/securingpki
  *Microsoft PKI hardening guidance.*
  `Security`

- 🥾 **Preparing VMware VMs for 2026 Secure Boot Expiration**
  https://www.matthewschacherbauer.com/wp/2026/02/preparing-vmware-vms-for-the-2026-microsoft-secure-boot-certificate-expiration/
  *Handling Secure Boot certificate expiration.*
  `SecureBoot`

- 🎞️ **TLS Handshake Deep Dive**
  https://www.youtube.com/watch?v=25_ftpJ-2ME&t
  *TLS handshake explained with Wireshark.*
  `TLS`

- 🎞️ **What Happens When a Client Connects?**
  https://youtu.be/C4Gtq5anlyc?si=pGrIfeUhyCTFJZIU
  *TLS connection process explained.*
  `TLS`

- 🎞️ **Configuring NDES for SCEP Certificate Deployment**
  https://www.youtube.com/watch?v=4EZRszjsZJs
  *In this series of videos, the gang will dive deep into ways to deploy certificates via Intune.*
  `TLS`

[▲ Back to Top](#-table-of-contents)

---

# ☁️ Cloud & Hybrid

- 📄 **Intune MDM Certificate Renewal Failure: The Hidden UPN Issue**
  https://patchmypc.com/blog/intune-mdm-device-certificate-renewal-upn-issue/?utm_campaign=brand-awareness-blog-2026&utm_source=linkedin&utm_medium=social&utm_content=blog&utm_term=intune-mdm-device-certificate
  *What really happens when the Intune MDM device certificate fails to renew.*
  `MDM` `Ìntune` `PKI` `Certificate`

- 📄 **Azure Region Abbreviations**
  https://www.jlaundry.nz/2022/azure_region_abbreviations/
  *Quick Azure region reference.*
  `Azure`

- 🔒 **Identifying & Abusing Azure Arc**
  https://www.ibm.com/think/x-force/identifying-abusing-azure-arc-for-hybrid-escalation-persistence
  *Azure Arc hybrid escalation research.*
  `AzureArc`

- 🔒 **Azure Arc (Part 2): Cloud to On-Premises Escalation**
  https://www.nsideattacklogic.de/azure-arc-part-2-escalation-from-cloud-to-on-premises/
  *Technical Azure Arc escalation walkthrough.*
  `AzureArc`

- 📄 **Audit Active Directory Certificate Services using Azure Sentinel**
  https://www.linkedin.com/pulse/audit-active-directory-certificate-services-using-azure-j%C3%A4rvemets
  *ADCS monitoring with Sentinel.*
  `Sentinel` `ADCS`

[▲ Back to Top](#-table-of-contents)

---

# 🛡️ Security & Hardening

- 🎞️ **Implementing PAW**
  https://www.youtube.com/watch?v=lYVhwL11pMI
  *Implementing Privileged Access Workstations.*
  `PAW` `Tier0`

- 🎞️ **Demystifying the Windows Firewall**
  https://www.youtube.com/watch?v=InPiE0EOArs
  *Windows Firewall deep dive.*
  `Firewall`

- 🎞️ *KB5005413: Mitigating NTLM Relay Attacks on Active Directory Certificate Services (AD CS)**
  https://support.microsoft.com/en-gb/topic/kb5005413-mitigating-ntlm-relay-attacks-on-active-directory-certificate-services-ad-cs-3612b773-4043-4aa9-b23d-b87910cd3429
  *HoTo prevent NTLM Relay Attacks on networks with NTLM enabled*
  `ADCS` `petitpotem` `hardening` `security` ``

[▲ Back to Top](#-table-of-contents)

---

# 🖥️ Windows Infrastructure

- 📄 **Monitoring Windows Firewall logs with Azure Monitor**
  https://michaelwaterman.nl/2026/04/21/monitoring-windows-firewall-logs-with-azure-monitor/
  *Forward Windows Firewall Logs to Azure.*
  `WinRM`

- 📄 **Automate WinRM on HTTPS**
  https://kb.ilves.se
  *Configure WinRM over HTTPS.*
  `WinRM`

- 🛡️ **DNS Zone Scope**
  https://learn.microsoft.com/en-us/powershell/module/dnsserver/get-dnsserverzonescope?view=windowsserver2025-ps
  *Control DNS responses using scopes.*
  `DNS`

- 📜 **Tool Dsmain**
  https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/cc772168(v=ws.11)
  *Expose AD snapshot data through LDAP.*
  `Backup` `Restore`

- 📜 **Modernizing RDP Certificates**
  https://michaelwaterman.nl/2026/02/08/modernizing-rdp-certificates/
  *Modern RDP certificate handling.*
  `RDP`

[▲ Back to Top](#-table-of-contents)

---

# 🐧 Linux

- ⚠️ **Linux Privilege Escalation (CVE-2026-31431)**
  https://guardsix.com/blog/linux-privilege-escalation-cve-2026-31431-copy-fail-exploit-and-detection
  *Copy Fail exploit and detection techniques.*
  `Linux` `CVE`

[▲ Back to Top](#-table-of-contents)

---

# 💾 Backup & Recovery

- 🧱 **WORM Storage Hardening Guide**
  https://bp.veeam.com/security/Design-and-implementation/Hardening/WORM_Storage_with_Veeam_Hardened_Repository.html
  *Veeam immutable repository guidance.*
  `Veeam`

- ℹ️ **Veeam KB4800**
  https://www.veeam.com/kb4800
  *Troubleshooting and configuration guidance.*
  `Veeam`

[▲ Back to Top](#-table-of-contents)

---

# ⚙️ Tools & Utilities

#### 🛠️ Tools & Downloads

- 🛡️ **WatchGuard Software Downloads**
  https://software.watchguard.com/SoftwareDownloads?current=true&familyId=a2RVr000000bJA9MAM
  *WatchGuard software downloads.*
  `WatchGuard`

- 📂 **Filebrowser Repository**
  https://github.com/filebrowser/filebrowser?tab=readme-ov-file
  *Self-hosted web-based file manager.*
  `FileManager`

- 🔒 **testssl.sh Repository**
  https://github.com/testssl/testssl.sh
  *TLS/SSL testing tool.*
  `TLS`

- 🔒 **Certify**
  https://github.com/GhostPack/Certify
  *Certify is a C# tool to enumerate and abuse misconfigurations in Active Directory Certificate Services (AD CS).*
  `abuse` `ADCS` `tool`

[▲ Back to Top](#-table-of-contents)

---

# 📜 Scripts & Automation

#### PowerShell

- ☁️ **Invoke-UpdateAzureBlobPKIStorage.ps1**
  https://github.com/dstreefkerk/PowerShell/blob/master/Microsoft%20ADCS/Invoke-UpdateAzureBlobPKIStorage.ps1
  *Upload CRLs and PKI files to Azure Blob Storage.*
  `PowerShell` `PKI`

- 🛠️ **TierLevelIsolation Repository**
  https://github.com/Kili69/TierLevelIsolation
  *Tier-level isolation implementation.*
  `Tiering`

- 🚀 **PAWDeploy**
  https://github.com/DeploymentBunny/PAWDeploy/blob/main/README.md
  *Deploy Privileged Access Workstations.*
  `PAW`

- ⚙️ **Build-Tier0-AuthPolicySilo.ps1**
  https://github.com/canix1/T0AuthSilo/blob/main/Build-Tier0-AuthPolicySilo.ps1
  *Build Authentication Policy Silos.*
  `Tier0`

- ⏱️ **Optimize-TCPSettings.ps1**
  https://gist.github.com/asheroto/942db6b331db8f070472990da6e6e1db
  *Optimize Windows TCP settings.*
  `TCP`

- ⏱️ **Set-WindowsTimeZone.ps1**
  https://github.com/MSEndpointMgr/Intune/blob/master/Autopilot/Set-WindowsTimeZone.ps1
  *Automatically configure timezone.*
  `Timezone`

- 🔑 **PassPushPosh (New-Push.md)**
  https://github.com/adamburley/PassPushPosh/blob/main/Docs/New-Push.md
  *Password Pusher PowerShell module.*
  `PasswordPusher`

#### CLI & Applications

- 💻 **pwpush-cli**
  https://github.com/pglombardo/pwpush-cli
  *CLI for secure password sharing.*
  `CLI`

- 𝍂 **Create Custom QR Codes**
  https://rodtrent.substack.com/p/creating-custom-qr-codes-with-logos
  *Generate QR codes with logos.*
  `QRCode`

[▲ Back to Top](#-table-of-contents)

---

# 🎓 Learning & References

- 🎓 **APL-1008 — Administer Active Directory Domain Services**
  https://learn.microsoft.com/en-us/training/paths/administer-active-directory-domain-services/
  *Microsoft Learn path for AD DS.*
  `Training`

- ⌨️ **VS Code Keyboard Shortcuts for macOS (PDF)**
  https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf
  *VS Code cheat sheet for macOS.*
  `VSCode`

- 🎞️ **PetitPotam Strikes Back: From (almost) Zero to Domain Admin**
  https://www.youtube.com/watch?v=aNQ0HGySSGo
  *VS Code cheat sheet for macOS.*
  `petitpotam` `ntlm` `ntlm relay` `ADCS`

[▲ Back to Top](#-table-of-contents)

---