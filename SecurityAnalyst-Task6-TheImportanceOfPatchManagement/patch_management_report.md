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

## Why Patches Matter

Software vulnerabilities are weaknesses or flaws in applications, operating systems or network services that can be exploited by attackers to gain unauthorized access, execute malicious code, steal data or disrupt operations. Effective patch management is critical because it enables organizations to fix known vulnerabilities before cybercriminals can exploit them.

## How Vulnerabilities Are Discovered, Reported and Exploited

The vulnerability lifecycle typically follows these stages:

1. **Discovery**

   Security researchers, software vendors, penetration testers or attackers identify a security flaw in a software product.

2. **CVE Assignment**

   Once validated, the vulnerability is assigned a unique identifier through the Common Vulnerabilities and Exposures (CVE) program. CVE identifiers provide a standardized method for tracking and discussing vulnerabilities across the cybersecurity community.

3. **Severity Assessment (CVSS Scoring)**

   The National Vulnerability Database (NVD) provides vulnerability information, including CVSS scores where available. The Common Vulnerability Scoring System (CVSS) assigns a severity score ranging from 0 to 10 and categorizes vulnerabilities as Low, Medium, High or Critical to help organizations prioritize remediation efforts.

4. **Patch Release**

   The software vendor develops and releases a security update or patch to correct the vulnerability. Organizations are expected to test and deploy the patch as quickly as possible.

5. **Exploitation**

   If systems remain unpatched, attackers may exploit the vulnerability to compromise systems, deploy malware, steal sensitive information or disrupt services.

According to NIST SP 800-40 Rev. 4, patch management is a critical component of preventive maintenance because it reduces the likelihood of compromises, operational disruptions and data breaches caused by known vulnerabilities.

[NIST - Guide to Enterprise Patch Management Planning](https://csrc.nist.gov/pubs/sp/800/40/r4/final)

## Real-World Example 1: WannaCry Ransomware (2017)

One of the most significant patch-management failures was the WannaCry ransomware outbreak in May 2017. WannaCry exploited the vulnerability identified as CVE-2017-0144, commonly associated with "EternalBlue", which affected Microsoft's SMBv1 protocol.

Microsoft had already released the security update "MS17-010" on March 14, 2017, approximately two months before the outbreak. However, many organizations failed to install the update, leaving their systems vulnerable.

As a result, WannaCry rapidly spread across hundreds of thousands of computers worldwide, encrypting files and demanding ransom payments. The attack severely disrupted healthcare organizations, businesses and government agencies, demonstrating the consequences of delayed patch deployment.

**References:**

- [Wikipedia - EternalBlue](https://en.wikipedia.org/wiki/EternalBlue)
- [NVD - CVE-2017-0144 Vulnerability Detail](https://nvd.nist.gov/vuln/detail/CVE-2017-0144)
- [Microsoft - Security Bulletin MS17-010](https://learn.microsoft.com/en-us/security-updates/Securitybulletins/2017/ms17-010)

## Real-World Example 2: Equifax Data Breach (2017)

The Equifax data breach is another widely cited example of patch management failure. Attackers exploited a known vulnerability in the Apache Struts web application framework, identified as **CVE-2017-5638**. A patch for the vulnerability had been released before the breach, but Equifax failed to apply it promptly.

As a result, attackers gained access to Equifax systems and exposed the personal information of approximately 147 million individuals, including names, dates of birth, Social Security numbers and other sensitive information. The breach became one of the largest data breaches in history and resulted in significant financial, legal and reputational damage to the company.

## References

1. National Institute of Standards and Technology (NIST). *Guide to Enterprise Patch Management Planning: Preventive Maintenance for Technology (SP 800-40 Rev. 4).*  
   [https://csrc.nist.gov/pubs/sp/800/40/r4/final](https://csrc.nist.gov/pubs/sp/800/40/r4/final)

2. National Institute of Standards and Technology (NIST). *National Vulnerability Database (NVD) - Common Vulnerability Scoring System (CVSS).*  
   [https://nvd.nist.gov/vuln-metrics/cvss](https://nvd.nist.gov/vuln-metrics/cvss)

3. National Vulnerability Database (NVD). *CVE-2017-0144 Vulnerability Detail.*  
   [https://nvd.nist.gov/vuln/detail/CVE-2017-0144](https://nvd.nist.gov/vuln/detail/CVE-2017-0144)

4. Microsoft. *Microsoft Security Bulletin MS17-010 - Critical.*  
   [https://learn.microsoft.com/en-us/security-updates/Securitybulletins/2017/ms17-010](https://learn.microsoft.com/en-us/security-updates/Securitybulletins/2017/ms17-010)

5. Microsoft Support. *MS17-010: Security Update for Windows SMB Server.*  
   [https://support.microsoft.com/en-us/servicing/os/windows-server/2017/03/ms17-010-security-update-for-windows-smb-server-march-14-2017](https://support.microsoft.com/en-us/servicing/os/windows-server/2017/03/ms17-010-security-update-for-windows-smb-server-march-14-2017)

6. Cybersecurity and Infrastructure Security Agency (CISA). *Patch Smarter, Not Harder.*  
   [https://www.cisa.gov/news-events/news/patch-smarter-not-harder](https://www.cisa.gov/news-events/news/patch-smarter-not-harder)

7. MITRE / CVE Program. *Common Vulnerabilities and Exposures (CVE).*  
   [https://www.cve.org/](https://www.cve.org/)

8. Imperva. *CVE and CVSS Vulnerability Overview.*  
   [https://www.imperva.com/learn/application-security/cve-cvss-vulnerability/](https://www.imperva.com/learn/application-security/cve-cvss-vulnerability/)

9. U.S. Government Accountability Office (GAO). *Actions Taken by Equifax and Federal Agencies in Response to the 2017 Breach.*  
   [https://www.gao.gov/products/gao-18-559](https://www.gao.gov/products/gao-18-559)

10. Federal Trade Commission (FTC). *Equifax to Pay $575 Million as Part of Settlement Related to 2017 Data Breach.*  
    [https://www.ftc.gov/news-events/news/press-releases/2019/07/equifax-pay-575-million-part-settlement-ftc-cfpb-states-related-2017-data-breach](https://www.ftc.gov/news-events/news/press-releases/2019/07/equifax-pay-575-million-part-settlement-ftc-cfpb-states-related-2017-data-breach)
