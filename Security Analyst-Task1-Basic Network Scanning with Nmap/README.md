# Objective 

Perform a network scan to identify open ports and services running on a local machine or virtual machine using Nmap, and document your findings with security analysis.

# Tech Stack / Tools

Nmap, Linux terminal (or Windows PowerShell), a local VM (e.g., VirtualBox with Kali Linux or Ubuntu)


# Task 1: Basic Network Scanning with Nmap

## What is Nmap?

Nmap is also called Network Mapper. It is an open-source network scanning and security auditing tool. It is used to discover hosts and services on a network, identify open ports, detect running services and in some cases, determine the operating system of a target system.

In this lab, Nmap was used from Kali Linux to scan the Metasploitable 2 virtual machine in an isolated laboratory environment.

## Why Network Scanning Matters

Network scanning is an important part of cybersecurity because it helps security professionals understand what systems and services are accessible on a network.

Scanning can help to:

- Identify active hosts and open ports.
- Discover services running on systems that are on the network.
- Identify potential entry points that may require further security assessment.
- Detect services that are exposed.
- Provide information that can be used to improve network security and reduce the attack surface.

In this lab, Nmap scanning was used to identify the open ports and services on the intentionally vulnerable Metasploitable 2 system.

## Ethical Use Guidelines

Network scanning should only be performed on systems and networks where you have explicit authorization to conduct security testing.

Unauthorized scanning of systems or networks may violate organizational policies, terms of service, or applicable laws.

For this project, all scanning activities were performed in my own controlled and isolated cybersecurity laboratory using Metasploitable 2, an intentionally vulnerable virtual machine designed for security education and testing.

The techniques demonstrated in this project should only be applied to systems for which appropriate permission has been obtained.

## Test Connection

Testing connection between the target and the attacker machines

![Security Analyst-Task1-Basic Network Scanning with Nmap](TestConnection1.jpg)
![Security Analyst-Task1-Basic Network Scanning with Nmap](TestConnection2.jpg)


