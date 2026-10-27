# Task 6 The Importance of Patch Management

## Objective

 To explain the importance of patch management in cybersecurity, examine the risks associated with unpatched systems, and explore how organisations can implement an effective patch management strategy to identify, prioritise, apply and verify security updates to reduce vulnerabilities and prevent cyberattacks.
 
## Tech Stack / Tools
- Markdown (for the report)
- GitHub (for submission)

## Introduction to Patch Management

Patch management is the process of identifying, prioritizing, acquiring, testing, deploying, and verifying software patches, updates and upgrades across an organization's systems and applications. According to NIST SP 800-40 Rev. 4: *Guide to Enterprise Patch Management Planning*, enterprise patch management involves identifying, prioritizing, acquiring, installing and verifying patches throughout an organization to reduce security risk and maintain system reliability.

Patch management plays a critical role in the vulnerability lifecycle. A vulnerability is first discovered and assigned a unique identifier through the Common Vulnerabilities and Exposures (CVE) program. The vulnerability is then analyzed and assigned a severity score using the Common Vulnerability Scoring System (CVSS), which helps organizations determine remediation priorities. Vendors subsequently release security patches, and organizations are expected to deploy these patches to eliminate the vulnerability before attackers can exploit it.

Patch management is a form of preventive maintenance that helps organizations prevent compromises, data breaches, operational disruptions and other cybersecurity incidents. Without a structured patch management program, known vulnerabilities can remain exposed for extended periods, creating opportunities for attackers to gain unauthorized access to systems and data.

*NIST — Guide to Enterprise Patch Management Planning: Preventive Maintenance for Technology*. https://www.nist.gov/publications/guide-enterprise-patch-management-planning-preventive-maintenance-technology

The importance of patch management is demonstrated by major cyber incidents such as the WannaCry ransomware outbreak in May 2017. WannaCry exploited the CVE-2017-0144 vulnerability, commonly known as EternalBlue, in Microsoft's SMBv1 protocol. Although Microsoft had already released security update MS17-010 to address the vulnerability, many organizations had not applied the patch, allowing the ransomware to spread rapidly across thousands of unpatched systems worldwide.

*Wikipedia — EternalBlue*. https://en.wikipedia.org/wiki/EternalBlue

In modern cybersecurity, patch management is widely regarded as one of the most effective defenses against cyberattacks because it reduces the attack surface presented by known vulnerabilities. Organizations that implement timely and well-structured patch management programs significantly reduce the risk of exploitation, malware infections, ransomware outbreaks and data breaches.

## References

1. National Institute of Standards and Technology (NIST). *Guide to Enterprise Patch Management Planning: Preventive Maintenance for Technology (SP 800-40 Rev. 4).* [https://csrc.nist.gov/pubs/sp/800/40/r4/final](https://csrc.nist.gov/pubs/sp/800/40/r4/final)

2. National Institute of Standards and Technology (NIST). *National Vulnerability Database (NVD) - Common Vulnerability Scoring System (CVSS).* [https://nvd.nist.gov/vuln-metrics/cvss](https://nvd.nist.gov/vuln-metrics/cvss)

3. National Vulnerability Database (NVD). *CVE-2017-0144 Vulnerability Detail.* [https://nvd.nist.gov/vuln/detail/CVE-2017-0144](https://nvd.nist.gov/vuln/detail/CVE-2017-0144)

4. Microsoft. *Microsoft Security Bulletin MS17-010 - Critical.* [https://learn.microsoft.com/en-us/security-updates/Securitybulletins/2017/ms17-010](https://learn.microsoft.com/en-us/security-updates/Securitybulletins/2017/ms17-010)

5. Microsoft Support. *MS17-010: Security Update for Windows SMB Server.* [https://support.microsoft.com/en-us/servicing/os/windows-server/2017/03/ms17-010-security-update-for-windows-smb-server-march-14-2017](https://support.microsoft.com/en-us/servicing/os/windows-server/2017/03/ms17-010-security-update-for-windows-smb-server-march-14-2017)

6. Cybersecurity and Infrastructure Security Agency (CISA). *Patch Smarter, Not Harder.* [https://www.cisa.gov/news-events/news/patch-smarter-not-harder](https://www.cisa.gov/news-events/news/patch-smarter-not-harder)
