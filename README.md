NAME: ARKESHWAR S
COMPANY: CODTECH IT SOLUTIONS
ID: CT12DS1596
DOMAIN: CYBER-SECURITY & ETHICAL HACKING
DURATION: JULY 5TH, 2024 - SEPTEMBER 5TH, 2024

OVERVIEW OF THE PROJECT

Vulnerability Scanning Tool - Program Overview
The Vulnerability Scanning Tool is a Python-based utility designed to scan a network or website for common security vulnerabilities. The tool helps identify open ports and potential security risks associated with outdated or vulnerable software versions.

Key Features:
Port Scanning:

The tool checks a range of ports (1 to 1024) on the target system to determine which ports are open. Open ports can be potential entry points for attackers.
Vulnerability Detection:

The program utilizes Nmap, a powerful network scanning tool, to detect software versions running on the target and identifies any known vulnerabilities or outdated software. The results highlight critical issues that need to be addressed.
Execution Time Tracking:

The tool tracks the time taken to complete the scan, providing insight into the efficiency of the scanning process.
How the Program Works:
The user inputs the target's IP address or domain name.
The program first performs a port scan to identify open ports.
It then runs a vulnerability scan using Nmap, filtering the results to highlight any vulnerabilities related to outdated software or known security issues.
The total time taken for the entire scan is displayed at the end.
Technical Details:
Programming Language: Python
Dependencies:
Python: The program is compatible with Python 3.x.
Nmap: The tool uses Nmap for advanced vulnerability detection. Ensure Nmap is installed on your system.
Input: Target IP address or domain name
Output: List of open ports and any detected vulnerabilities related to outdated or insecure software.
Prerequisites:
Python: Make sure Python 3.x is installed on your system.
Nmap: Install Nmap to enable the vulnerability scanning functionality.
Usage Instructions:
Run the Program: Execute the program from your terminal or command prompt.
Enter the Target: Provide the target IP address or domain name when prompted.
View Results: The program will display the open ports and any vulnerabilities detected, along with the total scanning time.
Ethical Considerations:
This tool should be used responsibly. Ensure you have explicit permission before scanning any network or system. Unauthorized scanning may violate laws and regulations.

Future Enhancements:
This tool can be extended by:

Adding options for scanning specific port ranges.
Implementing more detailed vulnerability reports.
Integrating additional security checks, such as misconfigurations or SSL/TLS vulnerabilities.
This Vulnerability Scanning Tool serves as a foundational tool for basic network security assessments, providing essential insights into the security posture of a network or website.
