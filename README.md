# PENETRATION-TESTING-TOOLKIT
*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : ANUBHAV KUMAR

*INTERN ID* : CT04DF1662

*DOMAIN* : Cyber Security & Ethical Hacking

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH
# DESCRIPTION
A TOOLKIT WITH MULTIPLE MODULES (E.G., PORT SCANNER, BRUTE-FORCER) FOR PENETRATION TESTING.
The Penetration Testing Toolkit is a Python-based modular security testing tool designed for ethical hacking and cybersecurity professionals. It includes multiple modules such as a port scanner and a brute-force attack tool to help identify vulnerabilities in network security and authentication mechanisms.
# TOOLS AND LIBRARIES USED:
1. Python Built-in Libraries
Library     	Purpose
socket -	    Network communication (port scanning, banner grabbing)

argparse -	  Command-line interface for toolkit

ftplib -	    FTP connection for brute-force attack

os -	        (Optional) File path, system calls, etc.

time -	      (Optional) Add delays, measure response times

# KEY FEATURES:
Port Scanner: Scans specified ports on a target host to identify open services.

Brute Force Login: Attempts to crack web-based authentication using a username and a list of potential passwords.

Password Generator: Creates possible password combinations using custom character sets and lengths.

Modular Structure: Easily extendable with new penetration testing features.

Simple CLI Interface: Easy-to-use command-line interface for quick security assessments.
# USE CASES:
1. Port Scanning
To scan for open ports on a target:

Penetration Testing Toolkit
1. Port Scanner
2. Brute Force Login
Select a module (1/2): 1
Enter target IP or domain: example.com
Enter ports to scan (comma-separated): 22,80,443
Example Output:
[OPEN] Port 22 is open on example.com
[OPEN] Port 80 is open on example.com
[OPEN] Port 443 is open on example.com
2. Brute Force Login
To attempt a brute-force attack on a login page:

Penetration Testing Toolkit
1. Port Scanner
2. Brute Force Login
Select a module (1/2): 2
Enter login URL: https://example.com/login
Enter username: admin
Enter password list (comma-separated): password123, admin123, qwerty
Example Output:
[SUCCESS] Password found: admin123
