# Advent of Cyber 2025 – Day 5  
## Insecure Direct Object Reference (IDOR)

### Lab Overview
This lab focused on Insecure Direct Object Reference (IDOR), a common web application vulnerability where attackers gain unauthorized access to resources by manipulating identifiers in requests.

### Tools / Environment
- Web browser
- TryHackMe AttackBox
- Vulnerable web application

### Tasks Performed
- Interacted with a web application using object identifiers
- Modified URL parameters and request values
- Observed how improper access controls expose sensitive data
- Identified unauthorized access to restricted resources

### What I Learned
- What IDOR vulnerabilities are and how they occur
- Why missing access control checks are dangerous
- How attackers exploit predictable identifiers
- The importance of proper authorization checks in applications

### Security Relevance (SOC Perspective)
IDOR vulnerabilities are frequently exploited in real-world attacks. For SOC analysts, this knowledge helps to:
- Understand how web application attacks are performed
- Investigate suspicious access patterns in logs
- Support vulnerability management and remediation efforts
