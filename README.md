# Cloud Exploit and Detect: AWS GuardDuty Lab

## Objective


This project demonstrates a "Purple Team" approach to cloud security by simulating real-world attacks and enterprise-level detection. Using AWS CloudFormation, I deployed a vulnerable OWASP Juice Shop application behind Amazon CloudFront and Amazon S3 to create a realistic attack surface. The primary objective was to execute targeted web exploits and then utilize Amazon GuardDuty to detect, analyze, and document the resulting threat intelligence, effectively bridging the gap between offensive techniques and defensive cloud monitoring.

### Skills Learned
[Bullet Points - Remove this afterwards]

- Infrastructure as Code (IaC): Automating security environments using AWS CloudFormation to ensure consistent and repeatable deployments.
- Web Vulnerability Analysis: Identifying and exploiting OWASP Top 10 flaws (such as SQL Injection and Cross-Site Scripting) within a modern web application framework.
- Cloud Threat Detection: Configuring and monitoring Amazon GuardDuty to identify malicious activity, account compromises, and unauthorized data access.
- Adversary Emulation: Simulating real-world attack patterns, including IAM credential exfiltration, reconnaissance, and brute-force attacks.
- Edge & Storage Security: Implementing and securing content delivery via Amazon CloudFront and managing sensitive data policies within Amazon S3.
- Incident Investigation: Analyzing raw JSON findings and GuardDuty logs to understand the "who, what, and where" of a security breach.
- Defensive Architecture: Designing a "Defense-in-Depth" strategy by correlating application-layer attacks with cloud-native monitoring tools.

### Tools Used
[Bullet Points - Remove this afterwards]

- Amazon GuardDuty: The core intelligent threat detection service used to monitor for malicious activity and unauthorized behavior.
- Amazon CloudFront: Used as the Content Delivery Network (CDN) to secure the application "at the edge" and manage public access.
- Amazon S3: Used for scalable object storage to hold sensitive application data and simulate data breach targets.
- AWS CloudFormation: The Infrastructure as Code (IaC) tool used to automate the deployment of the entire lab environment.
- Amazon EC2: Provides the compute power to host the web application and serves as the primary target for server-side exploits.
- AWS CloudShell: A browser-based shell used to execute CLI commands and simulate attacker behavior within the environment.
- OWASP Juice Shop: A sophisticated, intentionally insecure web application used to simulate real-world vulnerabilities (SQLi, XSS, etc.).
- Kali Linux / Burp Suite: (Optional but recommended) Professional-grade tools used for intercepting traffic and performing manual penetration testing.
- AWS CLI: Used for programmatic interaction with AWS services to simulate credential theft and data exfiltration.

## Steps
drag & drop screenshots here or use imgur and reference them using imgsrc

Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*
