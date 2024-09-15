Overview of the Project

Project: Simple Vulnerability Scanner

Objective:
To create a tool for identifying potential vulnerabilities in networked systems and web applications. This involves scanning for open ports, checking HTTP headers for outdated software versions or sensitive information, and detecting basic security misconfigurations.

Key Activities:
**Port Scanning:**
Uses Nmap to scan a range of ports (1-1024) on a given target.
Identifies and lists open ports.
**HTTP Header Analysis:**
Makes HTTP requests to a target URL to retrieve and analyze HTTP headers.
Checks for outdated software versions and sensitive information revealed through headers.
**Misconfiguration Detection:**
Checks for the presence of important security headers (e.g., Strict-Transport-Security, Content-Security-Policy).
Identifies missing headers that could indicate security misconfigurations.
**Execution and Reporting:**
Runs both port scanning and HTTP header checks if the target is a web URL.
Provides feedback on detected vulnerabilities and misconfigurations.
**Technologies used:**
Nmap: A network scanning tool used for port scanning.
Requests: A Python library for making HTTP requests and handling responses.
