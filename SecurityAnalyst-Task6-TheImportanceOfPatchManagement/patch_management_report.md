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

## Consequences of Not Patching Systems

Failure to apply security patches promptly can leave known vulnerabilities open to exploitation. Cybercriminals may use these weaknesses to access confidential information, deploy ransomware, disrupt business operations and compromise entire networks. Poor patch management can also result in regulatory penalties, legal claims, recovery expenses and loss of customer trust.

The following are major consequences of inadequate patch management:

### 1. Data Breaches and Loss of Sensitive Information

Unpatched software can provide attackers with an entry point into an organisation's network. Once inside, attackers may steal personal information, financial records, login credentials, intellectual property and other confidential data. A breach can lead to identity theft, legal action, incident investigation costs and reputational damage.

IBM's 2025 Cost of a Data Breach Report estimated the global average cost of a data breach at US$4.44 million. This figure covers the overall cost of studied breaches, not only those caused by unpatched vulnerabilities.

In 2017, attackers exploited an unpatched Apache Struts vulnerability at Equifax, contributing to a breach that affected approximately 147 million people. The incident demonstrates how failing to identify and patch a known vulnerability can expose highly sensitive information.

### 2. Ransomware Attacks and Operational Disruption

Attackers can exploit unpatched systems to install ransomware, encrypt files, spread across networks and interrupt essential services. An organisation may lose access to business applications, experience prolonged downtime or need to rebuild affected systems. Even when backups are available, restoring operations can require considerable time and resources.

Verizon's 2025 Data Breach Investigations Report found that ransomware was present in 44% of the breaches analysed. The same report found that exploitation of vulnerabilities accounted for 20% of initial access vectors in the relevant breach dataset. These figures show the importance of vulnerability remediation, although they do not mean every ransomware incident resulted from missing patches.

The 2017 WannaCry outbreak exploited Windows vulnerabilities addressed by Microsoft's MS17-010 security update. Many affected systems had not installed the update before the outbreak, allowing the malware to spread and disrupt organisations worldwide.

### 3. Compliance Violations and Regulatory Penalties

Organisations that process personal, financial or health information may be subject to laws, regulations, contracts and security standards requiring appropriate protection of systems and data. Failure to manage known vulnerabilities may indicate that an organisation did not implement reasonable security measures. Depending on the applicable rules and circumstances, this may result in regulatory investigations, corrective orders, fines or legal claims.

Following the Equifax breach, the U.S. Federal Trade Commission, Consumer Financial Protection Bureau and states announced a settlement of at least US$575 million, potentially rising to US$700 million under the settlement terms. The FTC alleged, among other security failures, that Equifax had failed to patch its network after receiving notice of a critical vulnerability.

This example demonstrates that inadequate vulnerability management can have significant financial and regulatory consequences. However, not every failure to patch automatically constitutes a legal violation; the outcome depends on the applicable requirements and facts.

### 4. Financial Losses and Reputational Damage

The financial impact of an unpatched vulnerability can extend well beyond the initial attack. Organisations may face incident response expenses, forensic investigations, system restoration costs, loss of revenue, customer compensation, legal fees and increased security spending. Customers and business partners may also lose confidence in an organisation that fails to protect its systems and information.

IBM's 2025 report estimated that the average cost of a data breach in the United States reached US$10.22 million, compared with the global average of US$4.44 million. These figures illustrate the potential scale of breach-related losses, but actual costs vary considerably by industry, location and incident.

### 5. Increased Exposure to Known Exploits

When vendors release security patches, technical details about the underlying vulnerabilities may become publicly available. Attackers can use this information to identify systems that remain unpatched and target them with existing or newly developed exploits. The longer a vulnerable system remains exposed, the greater the opportunity for exploitation.

Verizon's 2025 Data Breach Investigations Report found that exploitation of vulnerabilities as an initial access method increased by 34% compared with the previous report, reaching 20% of initial access vectors in the analysed dataset. Verizon also reported a median remediation time of 32 days for the perimeter-device vulnerabilities examined, with only about 54% fully remediated during the year.

These findings highlight the importance of maintaining an accurate asset inventory, prioritising actively exploited vulnerabilities and measuring how quickly patches are deployed and verified.

## References

1. **National Institute of Standards and Technology (NIST). (2022).** *Guide to Enterprise Patch Management Planning: Preventive Maintenance for Technology (SP 800-40 Rev. 4).*  
   [https://csrc.nist.gov/pubs/sp/800/40/r4/final](https://csrc.nist.gov/pubs/sp/800/40/r4/final)

2. **Cybersecurity and Infrastructure Security Agency (CISA).** *Known Exploited Vulnerabilities (KEV) Catalog.*  
   [https://www.cisa.gov/known-exploited-vulnerabilities-catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)

3. **Verizon Business. (2025).** *2025 Data Breach Investigations Report.*  
   [https://www.verizon.com/business/resources/reports/dbir/](https://www.verizon.com/business/resources/reports/dbir/)

4. **IBM. (2025).** *Cost of a Data Breach Report 2025.*  
   [https://www.ibm.com/think/x-force/2025-cost-of-a-data-breach-navigating-ai](https://www.ibm.com/think/x-force/2025-cost-of-a-data-breach-navigating-ai)

5. **Federal Trade Commission (FTC). (2019).** *Equifax to Pay $575 Million as Part of Settlement Related to 2017 Data Breach.*  
   [https://www.ftc.gov/news-events/news/press-releases/2019/07/equifax-pay-575-million-part-settlement-ftc-cfpb-states-related-2017-data-breach](https://www.ftc.gov/news-events/news/press-releases/2019/07/equifax-pay-575-million-part-settlement-ftc-cfpb-states-related-2017-data-breach)

6. **Microsoft Security Response Center. (2017).** *WannaCrypt Ransomware Worm Targets Out-of-Date Systems.*  
   [https://www.microsoft.com/en-us/security/blog/2017/05/12/wannacrypt-ransomware-worm-targets-out-of-date-systems/](https://www.microsoft.com/en-us/security/blog/2017/05/12/wannacrypt-ransomware-worm-targets-out-of-date-systems/)

7. **MITRE Corporation.** *Common Vulnerabilities and Exposures (CVE).*  
   [https://www.cve.org/](https://www.cve.org/)

8. **National Institute of Standards and Technology (NIST).** *National Vulnerability Database (NVD).*  
   [https://nvd.nist.gov/](https://nvd.nist.gov/)

   ## Patch Management Lifecycle

An effective patch management program follows a structured lifecycle that helps organizations identify vulnerabilities, evaluate risk, safely deploy updates and verify that security weaknesses have been successfully remediated. According to SP 800-40 Rev. 4, *Guide to Enterprise Patch Management Planning: Preventive Maintenance for Technology*, patch management includes identifying, prioritizing, acquiring, installing and verifying patches throughout the organization.

### 1. Discovery

The first phase involves identifying assets, software, operating systems and vulnerabilities within the organization's environment. Security teams monitor vendor advisories, the Common Vulnerabilities and Exposures (CVE) database and vulnerability scanning tools to discover systems requiring updates. Vulnerabilities are assigned unique CVE identifiers so they can be consistently tracked and managed.

Organisations cannot patch systems effectively if they do not know which devices and software they own or which vulnerabilities affect them. This highlights the importance of discovery.

### 2. Assessment

Once vulnerabilities are identified, organisations assess their severity and potential impact. This stage typically uses the Common Vulnerability Scoring System (CVSS), which assigns numerical scores ranging from 0 to 10 and classifies vulnerabilities as Low, Medium, High or Critical. The assessment process helps determine which patches should be prioritised first.

Assessment helps organisations focus limited time and resources on vulnerabilities that pose the greatest risk.

### 3. Testing

Before deployment, patches should be tested in a controlled environment to ensure they do not disrupt business operations or introduce compatibility issues. Patch testing is recommended to minimise operational risks while still maintaining timely remediation of vulnerabilities.

Testing reduces the risk of compatibility problems, failed installations and unexpected downtime.

### 4. Deployment

After successful testing, patches are deployed to production systems. Critical security updates are usually prioritised and installed according to organisational patch management policies and risk assessments. Timely deployment reduces the window of opportunity for attackers to exploit known vulnerabilities.

A patch only reduces the vulnerability of a system when the update or another effective remediation measure has actually been applied.

### 5. Verification

The final phase confirms that patches were installed successfully and that vulnerabilities have been eliminated. Organisations perform vulnerability scans, system audits and compliance checks to verify patch effectiveness and ensure all systems remain protected.

Without verification, an organisation may assume that a vulnerability has been fixed while some systems still remain exposed.

