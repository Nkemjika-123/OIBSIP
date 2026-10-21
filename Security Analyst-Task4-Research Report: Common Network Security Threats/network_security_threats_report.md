# Task 4: Common Network Security Threats

# Objective
To research and analyze common network security threats, including Denial-of-Service (DoS/DDoS), Man-in-the-Middle (MITM), IP Spoofing, and DNS Poisoning or Hijacking. This report explains how each attack works, examines real-world incidents and their impact, and identifies practical mitigation strategies to help network administrators protect systems, safeguard sensitive information, and maintain network availability and security. 

# Tech Stack / Tools 
- Markdown (for the report)
- GitHub (for submission)

# Introduction

Network security threats are a major concern in today's digital landscape because organizations increasingly depend on networks, cloud services and internet-facing systems that are linked to conduct daily operations. As technology keeps on growing, cybercriminals and other threat actors find ways around developing more sophisticated methods to disrupt services, steal sensitive information, gain unauthorized access and compromise critical infrastructure. The Mitre Att&ck framework describes how attackers use real-world tactics and techniques throughout the cyberattack lifecycle, while emphasizing on the importance of managing cybersecurity risks through security controls that are planned and risk management practices. Cyber and physical threats are becoming more complex and diverse. As a result, organizations are expected to strengthen their security posture and resilience. Human factor is also risk. Phishing and other social engineering attacks are major threats targeting users and network security. Effective defensive measures are essential for protecting organizational assets, maintaining business continuity and safeguarding sensitive data.

# References
1.	National Institute of Standards and Technology (NIST). (2024). The NIST Cybersecurity Framework (CSF) 2.0. https://www.nist.gov/cyberframework 
2.	Cybersecurity and Infrastructure Security Agency (CISA). Infrastructure Assessments & Analysis. https://www.cisa.gov/infrastructure-assessments-analysis 
3.	Cybersecurity and Infrastructure Security Agency (CISA). Critical Infrastructure Security and Resilience. https://www.cisa.gov/topics/critical-infrastructure-security-and-resilience 
4.	MITRE Corporation. MITRE ATT&CK® Framework. https://attack.mitre.org/ 
5.	SANS Institute. (2023). SANS 2023 Security Awareness Report: Managing Human Risk. https://www.sans.org/reading-room/ 

# DoS/DDoS Attacks
## How They Work
A Denial-of-Service (DoS) attack is a cyber-attack that attempts to make a system, network or service unavailable to legitimate users by overwhelming it with malicious traffic or requests. A DoS attack prevents authorized access to resources or delays critical operations.

A Distributed Denial-of-Service (DDoS) attack is a more powerful form of DoS attack that uses a lot of compromised devices or hosts to simultaneously flood a target with traffic. DDoS is a denial-of-service technique that uses multiple hosts to perform the attack. 

According to Mitre Att&ck (n.d.), attackers perform network DoS attacks by exhausting the bandwidth or resources that websites, DNS services, email systems and web applications rely on. Traffic may originate from a single system (DoS) or from thousands of distributed systems (DDoS), often organized into botnets. Mitre Att&ck classifies these attacks under “Technique T1498: Network Denial of Service” and identifies sub-techniques such as Direct Network Flood and Reflection Amplification. 

DDoS attacks can be categorized into three major types:
-	Volumetric attacks that consume available bandwidth.
-	Protocol attacks that exploit weaknesses in network protocols.
-	Application-layer attacks that target specific applications or services.

# Real-World Example: The Dyn DDoS Attack (2016)

On 21 October 2016, the DNS provider suffered a massive DDoS attack conducted through the Mirai botnet, which consisted of compromised Internet of Things (IoT) devices such as cameras, routers, and DVRs. The attack generated enormous volumes of malicious traffic, disrupting DNS services and causing outages for major websites and online services including Twitter, Spotify, Reddit, Netflix, PayPal, and GitHub. 

The attack targeted Dyn's DNS infrastructure, causing widespread internet disruptions across North America and Europe. The attack demonstrated how vulnerable IoT devices could be weaponized to conduct large-scale DDoS attacks. 

# Impact of DoS/DDoS Attacks

DoS and DDoS attacks can have severe consequences for organizations like the following:
-	Service outages, preventing legitimate users from accessing websites and applications. 
-	Financial losses due to downtime, lost transactions and recovery costs. 
-	Reputational damage when customers lose trust in an organization's ability to provide reliable services. 
-	Operational disruption, particularly when critical systems become unavailable. 

# Three Specific Mitigation Strategies

1. Use DDoS Protection Services and Content Delivery Networks (CDNs)
Mitre Att&ck recommends filtering attack traffic upstream through Internet Service Providers (ISPs), CDNs or specialized DDoS mitigation providers before it reaches the target network. 

2. Implement Network Traffic Filtering and Monitoring
Organizations should deploy firewalls, intrusion prevention systems, rate limiting and continuous network monitoring to identify abnormal traffic patterns and block malicious traffic before it affects services and Mitre Att&ck recommend filtering suspicious packets, ports and protocols associated with attacks.

3. Increase Capacity and Build Redundancy
Mitre Att&ck recommends managing network capacity, bandwidth and redundancy to reduce susceptibility to information-flooding attacks. Load balancing and redundant infrastructure can help absorb large traffic spikes and maintain service availability during an attack. 

# References
1.	National Institute of Standards and Technology (NIST). Denial of Service (DoS) Glossary. https://csrc.nist.gov/glossary/term/denial_of_service.
2.	National Institute of Standards and Technology (NIST). Distributed Denial of Service (DDoS) Glossary. https://csrc.nist.gov/glossary/term/distributed_denial_of_service 
3.	Cybersecurity and Infrastructure Security Agency (CISA). Understanding and Responding to Distributed Denial-of-Service Attacks (2024). https://www.cisa.gov/resources-tools/resources/understanding-and-responding-distributed-denial-service-attacks 
4.	MITRE ATT&CK. T1498: Network Denial of Service. https://attack.mitre.org/techniques/T1498/ 
5.	DDoS on Dyn Impacts Twitter, Spotify, Reddit (2016). https://krebsonsecurity.com/2016/10/ddos-on-dyn-impacts-twitter-spotify-reddit/ 
6.	Cybersecurity and Infrastructure Security Agency (CISA). Heightened DDoS Threat Posed by Mirai and Other Botnets (2017). https://www.cisa.gov/news-events/alerts/2016/10/14/heightened-ddos-threat-posed-mirai-and-other-botnets 

# Man-in-the-Middle (MITM) Attacks

A Man-in-the-Middle (MITM) attack occurs when attackers secretly position themselves between two networks and intercepts, monitors or alters the data being exchanged without realizing it. They can also intercept or alter data traveling between them. 

According to Mitre Att&ck (n.d.), attackers use Man-in-the-Middle (T1557) techniques to place themselves between networked devices by exploiting protocols such as ARP, DNS, DHCP and name resolution services. This position allows attackers to perform activities including network sniffing, credential theft, session hijacking, traffic manipulation and replay attacks.

Common MITM techniques include:
-	ARP Cache Poisoning
-	DNS Spoofing
-	DHCP Spoofing
-	Evil Twin (Rogue Wi-Fi) Access Points
-	SSL/TLS Downgrade Attacks

# Real-World Example: DigiNotar Certificate Authority Breach (2011)

A well-known example of a MITM attack was the Certificate Authority Breach in 2011. Attackers compromised the Dutch certificate authority DigiNotar and issued fraudulent SSL certificates, including fake certificates for Google domains. These certificates were used to conduct large-scale MITM attacks against approximately 300,000 Iranian Gmail users, allowing attackers to intercept supposedly secure communications. 

Browsers trusted certificates issued by DigiNotar so victims thought that they were communicating securely with legitimate websites no knowing that their traffic was actually being intercepted and monitored by attackers. The incident made browser vendors like Google, Microsoft and Mozilla revoke trust in DigiNotar certificates and the company went bankrupt. 

# Impact of MITM Attacks

-	Theft of sensitive information such as usernames, passwords, banking details and confidential communications. 
-	Modification of transmitted data allowing attackers to alter messages, transactions or files without detection. 
-	Session hijacking and credential theft enabling unauthorized access to user accounts and organizational systems. 
-	Loss of confidentiality and integrity compromising the trustworthiness of network communications.

# Three Specific Mitigation Strategies

1. Use Strong Encryption (HTTPS/TLS)

   Using modern TLS/SSL encryption protects data in transit. Encryption and digital certificates help ensure the                confidentiality and integrity of communications, making it significantly harder for attackers to intercept or modify         traffic. Organizations should disable outdated SSL versions and use latest TLS standards.

2. Implement Phishing-Resistant Multi-Factor Authentication (MFA)

   Modern adversary-in-the-middle attacks often target user credentials and authentication tokens. It is recommended to         implement strong, phishing-resistant MFA methods to reduce the likelihood of credential theft and account compromise.

3. Secure Network Infrastructure and Monitor for Anomalies

   Mitre Atta&ck recommends disabling unnecessary legacy protocols, encrypting wired and wireless traffic, using network        intrusion detection/prevention systems (IDS/IPS) and putting networks in segments to limit opportunities for attackers to    intercept communications. 

# References
1.	National Institute of Standards and Technology (NIST). Man-in-the-Middle Attack (MitM) Glossary. https://csrc.nist.gov/glossary/term/man_in_the_middle_attack [csrc.nist.gov], [csrc.nist.rip]
2.	Cybersecurity and Infrastructure Security Agency (CISA). Securing End-to-End Communications. https://www.cisa.gov/news-events/alerts/2015/04/30/securing-end-end-communications [cisa.gov]
3.	Cybersecurity and Infrastructure Security Agency (CISA). Phishing Guidance: Stopping the Attack Cycle at Phase One (2023). https://www.cisa.gov/resources-tools/resources/phishing-guidance-stopping-attack-cycle-phase-one [cisa.gov]
4.	MITRE ATT&CK. T1557: Adversary-in-the-Middle. https://attack.mitre.org/techniques/T1557/ [attack.mitre.org], [attack.mitre.org]
5.	Electronic Frontier Foundation (EFF). A Post Mortem on the Iranian DigiNotar Attack (2011). https://www.eff.org/deeplinks/2011/09/post-mortem-iranian-diginotar-attack [eff.org]
6.	 LearnTPRM. [learntprm.com]

# IP Spoofing

IP Spoofing is a technique in which an attacker falsifies the source IP address in network packets to make the traffic appear as though it originates from a trusted or legitimate system rather than the actual sender. Spoofing is a form of impersonation in which attackers disguise their identity and bypass security controls, evade detection or facilitate other attacks. According to (NIST). (n.d.), spoofing involves posing as an authorized user or resource and deliberately inducing a user or system to take incorrect actions. 

IP spoofing is commonly used to:
-	Hide the true source of malicious traffic. 
-	Support Distributed Denial-of-Service (DDoS) attacks. 
-	Conduct reflection and amplification attacks by tricking servers into sending responses to a victim instead of the attacker.
-	Bypass systems that rely on IP-based trust mechanisms. 

Mitre Att&ck notes that adversaries may spoof network services such as DHCP servers or manipulate network traffic to redirect communications through attacker-controlled systems, enabling credential theft, network sniffing or traffic manipulation. 

# Real-World Example: DNS Reflection DDoS Attacks Against KrebsOnSecurity

In 2016, Dyn was targeted by one of the largest DDoS attacks recorded at the time. This attack relied heavily on IP spoofing. The Attackers sent DNS requests with the victim's IP address forged as the source address. Open DNS servers then send their responses to the victim instead of the attacker, creating a massive flood of unwanted traffic. 

Reflection and amplification attacks are particularly dangerous because attackers can spoof source addresses and take advantage of infrastructures such as DNS and NTP servers to magnify attack traffic, generating attacks exceeding hundreds of gigabits per second. 

# Impact of IP Spoofing

IP spoofing can significantly affect organizations and networks by:
-	Concealing attacker identity, making incident investigation and attribution more difficult. 
-	Enabling DDoS reflection and amplification attacks, which can disrupt websites, services and critical infrastructure. 
-	Facilitating traffic interception and redirection, thereby allowing attackers to steal sensitive information. 
-	Bypassing weak IP-based authentication mechanisms, giving attackers unauthorized access opportunities. 

# Three Specific Mitigation Strategies

1. Implement Ingress and Egress Filtering (BCP 38)
   
   IP-level filtering techniques known as BCP 38 are recommended to block packets with spoofed source addresses before they     leave or enter a network. This prevents attackers from sending traffic with forged IP addresses. 

2. Deploy Anti-Spoofing Controls

   NIST SP 800-53 Control SC-16(2) specifically recommends implementing anti-spoofing mechanisms to prevent adversaries from    falsifying security attributes and network identities. Organizations should use router-based source validation, access       control lists (ACLs) and anti-spoofing technologies.

3. Use Secure Authentication and Network Monitoring
   
   This is recommended to strengthen network security through proper access controls, network segmentation, monitoring,         secure DNS configurations and reducing reliance on IP-based trust alone. Organizations should continuously watch out for     unusual network behavior and validate network traffic sources. 

# References
1.	National Institute of Standards and Technology (NIST). spoofing - Glossary | CSRC. https://csrc.nist.gov/glossary/term/spoofing [csrc.nist.gov]
2.	National Institute of Standards and Technology (NIST). Advanced DDoS Mitigation Techniques. https://www.nist.gov/programs-projects/advanced-ddos-mitigation-techniques [nist.gov]
3.	National Institute of Standards and Technology (NIST). SC-16 (2): Anti-spoofing Mechanisms. [csf.tools]
4.	Cybersecurity and Infrastructure Security Agency (CISA). Mitigate DNS Infrastructure Tampering (2021). https://www.cisa.gov/resources-tools/resources/mitigate-dns-infrastructure-tampering [cisa.gov]
5.	Cybersecurity and Infrastructure Security Agency (CISA). NSA and CISA Red and Blue Teams Share Top Ten Cybersecurity Misconfigurations (2023). https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-278a [cisa.gov]
6.	MITRE ATT&CK. Adversary-in-the-Middle: DHCP Spoofing (T1557.003). https://attack.mitre.org/techniques/T1557/003/ [attack.mitre.org]
7.	. KrebsOnSecurity Hit With Record DDoS (2016). https://krebsonsecurity.com/2016/09/krebsonsecurity-hit-with-record-ddos/ [krebsonsecurity.com]

# DNS Poisoning/Spoofing

DNS Poisoning is also known as DNS Cache Poisoning or DNS Spoofing. This is an attack that manipulates the Domain Name System (DNS) so that users are redirected to malicious or incorrect websites instead of legitimate ones. DNS acts as the Internet's phonebook by translating domain names into IP addresses. When attackers successfully alter DNS records or inject false DNS information into a resolver's cache, users can unknowingly be directed to attacker-controlled systems.

According to Mitre Att&ck, attackers may compromise DNS servers and alter DNS records to redirect an organization's traffic, facilitating credential theft, traffic interception and information collection. This technique allows attackers to redirect users to malicious infrastructure while appearing legitimate. 

This means that attackers can modify DNS records such as  A, MX or NS records and replace legitimate addresses with attacker-controlled addresses. As a result, web traffic and email traffic may be intercepted, monitored or manipulated without the user's knowledge. 

# Real-World Example: DNSpionage Campaign (2018-2019)

A well-documented example of DNS spoofing and DNS hijacking was the DNSpionage campaign. According to Krebs (2019), attackers hijacked DNS records belonging to government agencies and private organizations in the Middle East. By manipulating DNS settings, they redirected VPN and email traffic to attacker-controlled servers. The attackers then obtained valid SSL certificates for the targeted domains, enabling them to decrypt intercepted communications and steal login credentials.

The campaign demonstrated how compromising DNS infrastructure can provide attackers with access to sensitive email accounts, authentication credentials and confidential communications while remaining difficult to detect.

# Impact of DNS Poisoning/Spoofing

The impact of DNS Poisoning and Spoofing attacks can be the following:
-	Credential Theft: Users may be redirected to fake websites that steal usernames, passwords, and financial information. 
-	Traffic Interception: Attackers can inspect, modify, or monitor web and email communications.
-	Malware Distribution: Victims can be redirected to malicious websites that distribute malware or ransomware. 
-	Loss of Trust and Business Disruption: Organizations may suffer reputational damage, service disruption and financial losses when users cannot safely reach legitimate services. 
