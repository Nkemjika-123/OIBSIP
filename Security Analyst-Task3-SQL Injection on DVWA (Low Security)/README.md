# TASK 3 · SQL Injection on DVWA (Low Security) 

## Objective

The objective of this lab is to demonstrate SQL Injection vulnerability by exploiting the login form of DVWA (Damn Vulnerable Web Application) on its Low security setting and document the attack with an explanation of how it works and how to prevent it.

## Tech Stack / Tools

- DVWA (Damn Vulnerable Web Application)
- XAMPP or LAMP (for this lab, i used LAMP on kali linux VM)
- Web Browser

# Install and configure DVWA on a local server (using LAMP on Kali Linux )

## Update before beginning the installation process

## sudo apt update
## screenshot

## sudo systemctl  restart apache2 and mariadb

## screenshot

## sudo systemctl enable --now apache2

## screenshot

## sudo systemctl enable --now mariadb

## screenshot

## sudo systemctl status apache2

## screenshot

## sudo systemctl status mariadb

## screenshot

## sudo systemctl  restart apache2 and mariadb

## screenshot

## sudo git clone https://github.com/digininja/DVWA.git dvwa

## screenshot

## Navigate to cd /var/www/html/dvwa/config to copy the config file using 
## sudo cp config.inc.php.dist config.inc.php

## screenshot

## Create database using sudo mysql 

## screenshot

## Grant Permissions:
## sudo chmod -R 777 /var/www/html/dvwa/hackable/uploads
## sudo chmod -R 777 /var/www/html/dvwa/config

## screenshot

## sudo systemctl  restart apache2 and mariadb

## screenshot

## Click on create/reset database in this dvwa page

## screenshot

## Login with default username and password

## screenshot

## Set DVWA security level to Low 

## screenshot







