# SQL Injection Notes and Payload Analysis

## 1. Details of the Lab

- **Application:** Damn Vulnerable Web Application (DVWA)
- **Operating System:** Kali Linux
- **Web Server:** Apache2
- **Database:** MariaDB
- **Module:** SQL Injection
- **Security Level:** Low
- **Environment:** Authorized testing lab (DVWA)

## Purpose of Testing

The purpose of this exercise was to show how the DVWA SQL Injection module responds when normal input and different SQL injection payloads are used. I recorded the results and analyzed what happens when user input is not handled properly and how this can adversely affect database queries.

## Payload Log
### Test 1: 
### Payload:

' OR '1'='1 #

Purpose: Test whether an always-true condition can alter the logic of a SQL query.

## Result Observed

# screenshot

## Data exposed: 

The following information was exposed:
-	User IDs
-	First Names
-	Surnames
