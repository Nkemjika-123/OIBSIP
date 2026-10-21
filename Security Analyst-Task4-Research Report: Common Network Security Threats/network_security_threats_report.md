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
