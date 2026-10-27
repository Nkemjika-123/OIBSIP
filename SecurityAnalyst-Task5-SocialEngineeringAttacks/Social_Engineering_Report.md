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
*Canadian Centre for Cyber Security — Don't Take the Bait: Recognize and Avoid Phishing Attacks*.(https://www.cyber.gc.ca/en/guidance/dont-take-bait-recognize-and-avoid-phishing-attacks)

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

**Reference:** *CIS — MS-ISAC Security Primer: Spear Phishing*. (https://www.cisecurity.org/insights/white-papers/ms-isac-security-primer-spear-phishing)

## Real-World Case Study: The 2011 RSA SecurID Spear-Phishing Attack

### Incident Overview

In March 2011, RSA, a security company known for its SecurID authentication products, suffered a cyberattack that began with targeted phishing emails sent to employees of its parent company, EMC. The incident demonstrated how an email that looks ordinary could become the entry point for a serious security breach.

### How the Attack Happened

According to reporting by WIRED and Dark Reading, attackers sent targeted emails to small groups of employees with the subject line *"2011 Recruitment Plan."* The messages contained an Excel spreadsheet attachment. At least one employee retrieved the message from the junk email folder and opened the attachment.

The spreadsheet exploited a previously unknown Adobe Flash vulnerability and installed a backdoor known as Poison Ivy. This gave the attackers remote access to the compromised computer and allowed them to move further into the organization's network.

The attackers subsequently obtained information relating to RSA's SecurID two-factor authentication products. The incident was particularly significant because SecurID technology was used by organizations to strengthen authentication. Later, Lockheed Martin and other defense contractors were targeted in related activity involving SecurID credentials or tokens.

**References:**

*WIRED — How RSA Got Hacked*.
https://www.wired.com/2011/08/how-rsa-got-hacked/
*Dark Reading — RSA SecurID Attack Began With Excel File Rigged With Flash Zero-Day*. https://www.darkreading.com/cyberattacks-data-breaches/rsa-secureid-attack-began-with-excel-file-rigged-with-flash-zero-day
