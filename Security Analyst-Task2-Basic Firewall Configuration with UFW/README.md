# Task 2: Basic Firewall Configuration with UFW

# Objective

Set up and configure a basic firewall on a Linux system using UFW (Uncomplicated Firewall), applying rules to allow and deny specific types of traffic.

# Tech Stack / Tools

- UFW
- Linux (Metasploitable 2 or Kali Linux in a VM)

# Check Whether UFW Is Installed

Open your Kali Linux terminal and run: ufw --version
![Security Analyst-Task2-Basic Firewall Configuration with UFW](FWConfig1.jpg)

# Install UFW if not already present, run: sudo apt install ufw

# Enable UFW: sudo ufw enable

# Configure rule to allow SSH traffic (port 22): sudo ufw allow ssh

# Configure rule to deny HTTP traffic (port 80): sudo ufw deny http

# Add at least 2 additional rules of your choice (e.g., allow HTTPS, deny a specific IP range)
# Sudo ufw allow https

# Sudo ufw deny from 10.0.2.5


