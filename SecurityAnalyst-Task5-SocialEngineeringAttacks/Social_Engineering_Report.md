# TASK 5  Social Engineering Attacks

## Objective

To research and analyze major social engineering attacks, focusing on phishing, pretexting and baiting; examine their methods and real-world case studies; identify the psychological techniques used to deceive victims; and recommend effective prevention measures to help individuals and organizations reduce cybersecurity risks.

## Tech Stack / Tools

- Markdown (for the report)
- GitHub (for submission)

## Introduction

Social engineering is a cybersecurity attack technique in which attackers deceive people into revealing confidential information, performing unauthorized actions, or providing access to systems and networks. Instead of relying solely on technical vulnerabilities in software or hardware, social engineers exploit human psychology, trust, fear, curiosity, urgency, and the desire to help.

Common social engineering techniques include:

- Phishing
- Pretexting
- Baiting
- Impersonation
- Other forms of deception

(SANS Institute, *A Multi-Level Defense Against Social Engineering*, https://www.sans.org/white-papers/920)

Social engineering is considered one of the most effective attack vectors because people can be persuaded to bypass security procedures even when technical security controls are in place. For instance, an attacker may send a fraudulent email that appears to come from a trusted organization, impersonate an IT support staff to obtain login credentials or offer a free download that looks harmless but actually contains malicious software. These methods can give attackers an initial entry point into an organization's systems, potentially leading to data theft, financial losses, account compromise, malware infections and disruption of business operations. The Cybersecurity and Infrastructure Security Agency (CISA) identifies phishing as a technique used to trick people into disclosing personal information or downloading malicious software by pretending to be a trustworthy source (CISA, *Phishing General Security Guidance*).

The significance of this threat is supported by cybersecurity research. Verizon's *2024 Data Breach Investigations Report* found that 68% of the breaches analyzed involved a non-malicious human element, such as human error or a person falling victim to social engineering. Although this figure does not mean that all these breaches were caused by social engineering, it demonstrates the important role human behavior plays in cybersecurity incidents (Verizon, 2024). Similarly, the FBI's Internet Crime Complaint Centre reported that phishing and spoofing were among the most frequently reported categories of cybercrime in 2024, highlighting the continuing impact of deceptive online activities (FBI, 2025).

## References

1. SANS Institute. (2003). *A Multi-Level Defense Against Social Engineering*. SANS Reading Room. https://www.sans.org/white-papers/920

2. Cybersecurity and Infrastructure Security Agency (CISA). (2024). *Phishing General Security Guidance*. https://www.cisa.gov/sites/default/files/2024-02/Update%20to%20Phishing%20General%20Security%20Postcard_01.01.2024.pdf

3. Verizon. (2024). *2024 Data Breach Investigations Report*. https://www.verizon.com/business/resources/T850/reports/2024-dbir-data-breach-investigations-report.pdf

4. Federal Bureau of Investigation (FBI). (2025). *FBI Releases Annual Internet Crime Report*. https://www.fbi.gov/news/press-releases/fbi-releases-annual-internet-crime-report

5. Zetter, K. (2011, March 17). *Hacker Spies Hit Security Firm RSA*. WIRED. https://www.wired.com/2011/03/rsa-hacked/

6. Culafi, A., & Waldman, A. (2020, August 4). *Twitter Breach Raises Concerns Over Phone Phishing*. Dark Reading / TechTarget. https://www.techtarget.com/cybersecurity/news/252487156/Twitter-breach-raises-concerns-over-phone-phishing

## Phishing Attacks

Phishing is a form of social engineering in which cybercriminals impersonate trusted individuals, companies, or organizations to trick victims into revealing sensitive information, clicking malicious links, opening infected attachments, or providing unauthorized access to computer systems. Phishing commonly exploits human emotions such as fear, curiosity, trust, and urgency to persuade victims to take action without verifying the authenticity of a message (CISA, 2024).

Phishing is a significant cybersecurity threat because it can affect both individuals and organizations. A successful attack may result in stolen login credentials, financial fraud, malware infections, data breaches, and unauthorized access to corporate networks.

### Types of Phishing Attacks

### 1. Spear Phishing

Spear phishing is a targeted phishing attack aimed at a specific individual or a small group of people. Unlike generic phishing emails, spear-phishing messages are personalized using information about the target, such as their name, job title, employer, colleagues, or current projects.

**How it works:**

An attacker researches a target and creates a message that is convincing and appears to come from a trusted colleague, manager, supplier, or service provider. The message may contain a malicious link or attachment designed to steal credentials or install malware.

**Scenario:**

An employee receives an email that appears to come from their manager requesting that they review an attached company document. Opening the attachment may execute malicious code or lead to credential theft.

**Reference:**
*Center for Internet Security (CIS) — MS-ISAC Security Primer: Spear Phishing*. https://www.cisecurity.org/insights/white-papers/ms-isac-security-primer-spear-phishing

### 2. Whaling

Whaling is a specialized form of spear phishing that targets senior executives and other high-profile individuals, such as chief executive officers (CEOs), chief financial officers (CFOs), and directors. These individuals may have access to confidential business information, financial accounts, or the authority to approve significant transactions.

**How it works:**

An attacker impersonates a trusted business partner, senior colleague, legal adviser, or financial institution. The message may request confidential documents, employee information, or an urgent payment. Because the message appears to come from an authoritative source, the recipient may feel pressured to comply.

**Scenario:**

A finance employee receives an email apparently from the CEO requesting an urgent transfer of company funds to a new supplier account. If the employee does not independently verify the request, the organization may lose money.

**Reference:**
*Canadian Centre for Cyber Security — Don't Take the Bait: Recognize and Avoid Phishing Attacks*. https://www.cyber.gc.ca/en/guidance/dont-take-bait-recognize-and-avoid-phishing-attacks

**3. Vishing (Voice Phishing)**

Vishing is a phishing attack conducted through telephone calls, voicemail messages, or internet-based voice communication. Attackers impersonate trusted people or organizations to persuade victims to disclose confidential information or perform unauthorized actions.

**How it works:**

An attacker may pretend to be a bank representative, IT support employee, or government official. They might claim that an account has been compromised or that immediate action is required. The victim is then pressured to reveal passwords, one-time verification codes, banking details, or other sensitive information.

**Scenario:**

A caller claims to be from a bank's fraud department and tells a customer that suspicious transactions have been detected. The caller requests the customer's verification code to supposedly secure the account but uses it to gain unauthorized access.

**Reference:** *CISA — Phishing General Security Guidance*. (https://www.cisa.gov/sites/default/files/2024-02/Update%20to%20Phishing%20General%20Security%20Postcard_01.01.2024.pdf)

### 4. Smishing (SMS Phishing)

Smishing is a phishing attack that uses fraudulent SMS or text messages to deceive victims into clicking malicious links, downloading harmful applications, or disclosing sensitive information.

**How it works:**

The attacker sends a message pretending to be from a bank, delivery company, mobile network provider, or government agency. The message may claim that a package is delayed, an account has been suspended, or a payment must be confirmed. The victim is directed to a fraudulent website or encouraged to provide personal information.

**Scenario:**

A person receives a text message claiming that their bank account will be blocked unless they verify their details through a supplied link. The link opens a fake banking website designed to collect login credentials.

**Reference:** *Canadian Centre for Cyber Security — Don't Take the Bait: Recognize and Avoid Phishing Attacks*. https://www.cyber.gc.ca/en/guidance/dont-take-bait-recognize-and-avoid-phishing-attacks

## How a Phishing Attack Works

A typical phishing attack follows these stages:

1. **Target research:**
   The attacker identifies potential victims and may collect information from social media, company websites, or publicly       available records.
2. **Message preparation:**
   The attacker creates a deceptive email, text message, or voice communication that impersonates a trusted source.
3. **Delivery:**
   The fraudulent message is sent to the target, often using an urgent request, a tempting offer, or a warning about a          supposed problem.
4. **Victim interaction:**
   The victim clicks a link, opens an attachment, replies to the message, or provides sensitive information.
5. **Compromise:**
   The attacker may steal credentials, install malware, gain access to an account, or use the compromised device to reach       other systems.
6. **Exploitation:**
   The attacker may steal data, commit financial fraud, impersonate the victim, or move further into an organization's          network.

**Reference:** *CIS — MS-ISAC Security Primer: Spear Phishing*. https://www.cisecurity.org/insights/white-papers/ms-isac-security-primer-spear-phishing

## Real-World Case Study: The 2011 RSA SecurID Spear-Phishing Attack

### Incident Overview

In March 2011, RSA, a security company known for its SecurID authentication products, suffered a cyberattack that began with targeted phishing emails sent to employees of its parent company, EMC. The incident demonstrated how an email that looks ordinary could become the entry point for a serious security breach.

### How the Attack Happened

According to reporting by WIRED and Dark Reading, attackers sent targeted emails to small groups of employees with the subject line *"2011 Recruitment Plan."* The messages contained an Excel spreadsheet attachment. At least one employee retrieved the message from the junk email folder and opened the attachment.

The spreadsheet exploited a previously unknown Adobe Flash vulnerability and installed a backdoor known as Poison Ivy. This gave the attackers remote access to the compromised computer and allowed them to move further into the organization's network.

The attackers subsequently obtained information relating to RSA's SecurID two-factor authentication products. The incident was particularly significant because SecurID technology was used by organizations to strengthen authentication. Later, Lockheed Martin and other defense contractors were targeted in related activity involving SecurID credentials or tokens.

**Impact**

The breach exposed sensitive information associated with RSA's authentication technology and created security concerns for organizations that relied on SecurID. RSA subsequently announced measures to replace most of the affected security tokens.

**References**

*WIRED — Researchers Uncover RSA Phishing Attack, Hiding in Plain Sight (August 26, 2011)*. https://www.wired.com/2011/08/how-rsa-got-hacked/

*Dark Reading — RSA SecurID Attack Began With Excel File Rigged With Flash Zero-Day (April 1, 2011)*. https://www.darkreading.com/cyberattacks-data-breaches/rsa-secureid-attack-began-with-excel-file-rigged-with-flash-zero-day

## Preventive Measures Against These Attacks

Organizations and individuals can reduce phishing risks by implementing the following measures.

### 1. Provide Regular Security Awareness Training

Train employees to recognize suspicious emails, unexpected attachments, unusual payment requests and messages that create a false sense of urgency. Use authorized phishing simulations to assess awareness and teach staff how to report suspicious messages.

### 2. Verify Messages Before Taking Action

Avoid clicking unexpected links or opening suspicious attachments. Check the sender's full email address and verify unusual requests through a separate, trusted communication channel. For financial transfers or sensitive requests, follow established approval procedures rather than relying on email alone.

### 3. Implement Multi-Factor Authentication (MFA)

Require multi-factor authentication for email, remote access, financial systems and other important accounts. Where available, use phishing-resistant authentication, such as FIDO2 security keys or passkeys, because these provide stronger protection against credential-harvesting websites than passwords alone.

### 4. Deploy Technical Email and Access Controls

Use email filtering, anti-malware protection and domain authentication controls such as SPF, DKIM and DMARC to reduce fraudulent messages and sender impersonation. Keep operating systems and applications updated, restrict administrative privileges using the principle of least privilege, and monitor accounts for unusual login activity.ing.com/cyberattacks-data-breaches/rsa-secureid-attack-began-with-excel-file-rigged-with-flash-zero-day

## References

1. Cybersecurity and Infrastructure Security Agency (CISA). (2024). *Phishing General Security Guidance*. [https://www.cisa.gov/sites/default/files/2024-02/Update%20to%20Phishing%20General%20Security%20Postcard_01.01.2024.pdf](https://www.cisa.gov/sites/default/files/2024-02/Update%20to%20Phishing%20General%20Security%20Postcard_01.01.2024.pdf)

2. Center for Internet Security (CIS). (2018). *MS-ISAC Security Primer: Spear Phishing*. [https://www.cisecurity.org/insights/white-papers/ms-isac-security-primer-spear-phishing](https://www.cisecurity.org/insights/white-papers/ms-isac-security-primer-spear-phishing)

3. Canadian Centre for Cyber Security. *Don't Take the Bait: Recognize and Avoid Phishing Attacks*. [https://www.cyber.gc.ca/en/guidance/dont-take-bait-recognize-and-avoid-phishing-attacks](https://www.cyber.gc.ca/en/guidance/dont-take-bait-recognize-and-avoid-phishing-attacks)

4. National Institute of Standards and Technology (NIST). (2023). *Phishing Resistance – Protecting the Keys to Your Kingdom*. [https://www.nist.gov/blogs/cybersecurity-insights/phishing-resistance-protecting-keys-your-kingdom](https://www.nist.gov/blogs/cybersecurity-insights/phishing-resistance-protecting-keys-your-kingdom)

5. Zetter, K. (2011, August 26). *Researchers Uncover RSA Phishing Attack, Hiding in Plain Sight*. WIRED. [https://www.wired.com/2011/08/how-rsa-got-hacked/](https://www.wired.com/2011/08/how-rsa-got-hacked/)

6. Higgins, K. J. (2011, April 1). *RSA SecurID Attack Began With Excel File Rigged With Flash Zero-Day*. Dark Reading. [https://www.darkreading.com/cyberattacks-data-breaches/rsa-secureid-attack-began-with-excel-file-rigged-with-flash-zero-day](https://www.darkreading.com/cyberattacks-data-breaches/rsa-secureid-attack-began-with-excel-file-rigged-with-flash-zero-day)

## Pretexting Attacks

Pretexting is a type of social engineering attack in which a cybercriminal invents a believable story or false situation to persuade a victim to reveal confidential information, grant unauthorized access, or perform an action that benefits the attacker. The attacker often impersonates a trusted person such as an IT support employee, bank representative, manager, supplier or government official to make the request appear legitimate.

According to the Canadian Centre for Cyber Security, pretexting involves creating a fabricated scenario that makes an interaction seem reasonable and believable with the aim of building trust and encouraging the target to disclose sensitive information or provide access. *Canadian Centre for Cyber Security — Social Engineering*. https://www.cyber.gc.ca/en/guidance/social-engineering-itsap00166

Unlike a random fraudulent message, pretexting often involves research and a carefully constructed explanation. The attacker may use publicly available information about an organization, its employees or its procedures to make the false story more convincing.

### How an Attacker Builds a False Scenario

Pretexting attacks commonly involve the following stages:

**1. Researching the Target**

The attacker gathers information about the victim, their workplace, job responsibilities, colleagues or service providers. Information may come from company websites, social media profiles, public records or previously compromised accounts.

**2. Creating a Believable Identity**

The attacker assumes a false identity such as an IT technician, bank employee, manager or trusted business partner. They may use a fake email address, caller ID manipulation or a fraudulent website to support the identity.

**3. Inventing a Convincing Situation**

The attacker develops a story that gives them a reason to contact the victim. For example, they might claim that an employee's account has been compromised, a password must be reset or an urgent payment requires verification.

**4. Building Trust and Applying Pressure**

The attacker uses familiar terminology, apparent knowledge of the organization, authority, urgency or fear to make the request seem genuine. The victim may feel compelled to cooperate rather than question the request.

**5. Requesting Sensitive Information or an Action**

Once the victim believes the story, the attacker requests login credentials, verification codes, confidential documents, a password reset or access to an internal system.

**6. Exploiting the Information Obtained**

The attacker may use the information to access accounts, steal data, commit fraud or move further into the organization's network.

These stages are consistent with MITRE's description of pretexting as an attack pattern involving an invented scenario and an assumed identity to manipulate a target.
*MITRE CAPEC-407 — Pretexting*. https://capec.mitre.org/data/definitions/407.html

**Scenario:**

An attacker calls an employee and claims to be from the company's IT help desk. The attacker explains that a recent system update has caused login problems and asks the employee to verify their credentials on a supplied website. Believing the explanation, the employee enters their username and password, allowing the attacker to steal the credentials.

This illustrates how a false scenario can turn an ordinary support interaction into a security breach.

### Real-World Case Study: The 2020 Twitter Hack

#### Incident Overview

On July 15, 2020, Twitter experienced a major security incident in which attackers gained access to internal systems and compromised several high-profile accounts. The affected accounts included those belonging to public figures and cryptocurrency-related businesses.

The New York State Department of Financial Services investigated the incident and published its findings in October 2020. The investigation documented how attackers used social engineering to obtain employee credentials and gain access to Twitter's internal network.

#### How the Pretexting Attack Worked

The attackers contacted Twitter employees by telephone and pretended to be members of the company's IT help desk. They claimed they were helping employees resolve problems with Twitter's virtual private network (VPN), which staff used for remote work.

This fabricated explanation was convincing because VPN problems were familiar to employees working remotely. The attackers had also researched Twitter's employees and internal functions, helping them make their impersonation more credible.

During the calls, the attackers persuaded employees to enter their login credentials into a fraudulent website designed to resemble Twitter's legitimate VPN login page.

The incident combined pretexting, telephone-based social engineering (vishing) and credential phishing. The attackers used the false IT-support scenario to gain employees' trust and then directed them to a fraudulent login page.

### Impact

After obtaining employee credentials and access to internal tools, the attackers took control of dozens of high-profile Twitter accounts. They posted messages promoting a Bitcoin scam that encouraged followers to send cryptocurrency with the promise of receiving a larger amount in return.

The New York State Department of Financial Services reported that the attackers stole more than $118,000 worth of Bitcoin. The incident also raised concerns about employee access privileges, internal security controls and the protection of administrative tools.

### Primary Sources for the Case Study

1. New York State Department of Financial Services (2020). *Twitter Investigation Report*. https://www.dfs.ny.gov/reports-and-publications/other-reports/Twitter_Report. Read the Executive Summary and the section titled "Phase One: Stealing Credentials through Social Engineering." These sections describe the false help-desk story, fraudulent VPN website, employee credential theft, and consequences.

2. X (formerly Twitter). (2020). *An Update on Our Security Incident*. https://blog.x.com/en/company/an-update-on-our-security-incident. Read the July 30 update under "What we know now." This company statement confirms that the attack targeted a small number of employees through a phone spear-phishing attack and that the attackers obtained credentials granting access to internal support tools.

### Prevention Measures

Organizations can reduce the risk of pretexting attacks by implementing the following three measures.

**1. Verify Identities Independently**

Employees should never rely solely on a caller's claimed identity, displayed phone number, email signature, or knowledge of internal procedures. When someone requests sensitive information or access, employees should verify the person's identity through an independently obtained, trusted contact method.

For example, if someone calls claiming to be from IT support and requests a password or verification code, the employee should end the interaction and contact the official IT help desk using the organization's approved contact details. Employees should never disclose passwords or one-time authentication codes to callers.

**2. Establish Strong Verification and Approval Procedures**

Organizations should implement formal procedures for password resets, changes to employee accounts, disclosure of confidential information and financial transactions. Sensitive requests should require identity verification and, where appropriate, approval from a second authorized person.

The principle of least privilege should also be applied so that employees and administrators have only the access necessary to perform their duties. This limits the potential damage if an attacker successfully deceives an employee.

**3. Conduct Regular Security Awareness Training**

Employees should receive regular training on impersonation, pretexting, vishing and other social engineering techniques. Training should explain how attackers use urgency, authority, familiarity and personal information to manipulate victims.

Organizations can reinforce this training with authorized simulations, clear incident-reporting procedures and exercises involving fraudulent IT-support calls. Employees should be encouraged to report suspicious interactions without fear of blame or punishment.

## References

1. Canadian Centre for Cyber Security. *Social Engineering — ITSAP.00.166*. Government of Canada. [https://www.cyber.gc.ca/en/guidance/social-engineering-itsap00166](https://www.cyber.gc.ca/en/guidance/social-engineering-itsap00166)

2. MITRE. *CAPEC-407: Pretexting*. Common Attack Pattern Enumeration and Classification. [https://capec.mitre.org/data/definitions/407.html](https://capec.mitre.org/data/definitions/407.html)

3. New York State Department of Financial Services. (2020, October 14). *Twitter Investigation Report: Report on Investigation of Twitter's July 15, 2020 Cybersecurity Incident and the Implications for Election Security*. [https://www.dfs.ny.gov/reports-and-publications/other-reports/Twitter_Report](https://www.dfs.ny.gov/reports-and-publications/other-reports/Twitter_Report)

4. X (formerly Twitter). (2020, July 30). *An Update on Our Security Incident*. [https://blog.x.com/en/company/an-update-on-our-security-incident](https://blog.x.com/en/company/an-update-on-our-security-incident)

5. Federal Bureau of Investigation, Internet Crime Complaint Center (IC3). (2024, April 11). *Cyber Criminals Target Victims Using Social Engineering Techniques*. [https://www.ic3.gov/PSA/2024/PSA240411](https://www.ic3.gov/PSA/2024/PSA240411)

6. Cybersecurity and Infrastructure Security Agency (CISA). (2021). *Avoiding Social Engineering and Phishing Attacks*. Archived cybersecurity guidance. [https://www.cisa.gov/news-events/news/avoiding-social-engineering-and-phishing-attacks](https://www.cisa.gov/news-events/news/avoiding-social-engineering-and-phishing-attacks)
