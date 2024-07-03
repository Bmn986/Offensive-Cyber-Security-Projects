# Offensive-Cyber-Security-Projects

<b>Brandon's Offensive Security Projects<br>
Description: This repository serves as a hub for my personal projects in offensive cybersecurity. It explores various techniques for penetration testing, vulnerability research, and exploit development.<br>
Disclaimer: The tools and techniques showcased here are intended for educational purposes only. This repository does not endorse or encourage malicious activity. Responsible disclosure of vulnerabilities is highly encouraged.<br>
Project List:<br>
OWASP Juice Shop Admin Page Exploitation (Web App Security)
This project focused on exploiting weak access controls in the OWASP Juice Shop web application. By leveraging Burp Suite, a hidden admin page was discovered and accessed without proper authorization. This vulnerability allowed for unauthorized actions including:<br>
Viewing other users' shopping baskets (Privacy Breach)<br>
Deleting all 5-star product reviews (Manipulation of Review System)<br>
Technologies Used:<br>
OWASP Juice Shop (Web Application)<br>
Burp Suite Community Edition (Web Security Testing Tool)<br>
Link to the project directory within the repository (optional).<br>
OWASP Juice Shop - Unsecured Sensitive Document (Web App Security)<br>
This project focused on exploiting inadequate access controls within the OWASP Juice Shop web application. By analyzing the application structure and manipulating URLs, a critical file named "acquisitions.md" was discovered and accessed. This file contained confidential information about planned acquisitions.<br>
Technologies Used:<br>
OWASP Juice Shop (Web Application)<br>
Burp Suite Community Edition (Web Security Testing Tool)<br>
Impact:<br>
Exposure of the "acquisitions.md" file could lead to competitive disadvantage, financial loss, and potential legal issues for the company.<br>
<br>
OWASP Juice Shop - Null Byte Injection for File Download (Web App Security)<br>
This project explored exploiting a null byte injection vulnerability in the OWASP Juice Shop web application. By manipulating file download functionalities and injecting a null byte (%2500), I successfully downloaded:<br>
package.json.bak: A potentially sensitive backup configuration file.<br>
eastere.gg: A file containing a hidden message encoded with Base64 and ROT13.<br>
Technologies Used:<br>
OWASP Juice Shop (Web Application)<br>
Burp Suite Community Edition (Web Security Testing Tool)<br>
Impact:<br>
This vulnerability could allow attackers to access sensitive configuration data or hidden information within the application.<br>
Key Takeaway:<br>
The project highlights the importance of secure input validation, proper file access controls, and awareness of null byte injection vulnerabilities for web applications.<br>
<br>
OWASP Juice Shop - SQL Injection for Admin Login (Web App Security)<br>
This project focused on exploiting a SQL injection vulnerability in the login form of the OWASP Juice Shop web application. By crafting a malicious payload and utilizing Burp Suite's Intruder tool, I successfully bypassed authentication and gained unauthorized access to the administrator account.<br>
Technologies Used:<br>
OWASP Juice Shop (Web Application)<br>
Burp Suite Community Edition (Web Security Testing Tool)<br>
Impact:<br>
This vulnerability could allow attackers to gain unauthorized access to privileged accounts, potentially leading to data breaches or system compromise.<br>
Key Takeaway:<br>
The project highlights the importance of secure input validation and parameterized queries to prevent SQL injection vulnerabilities in web applications.<br>
<br>
OWASP Juice Shop - Bypassing CAPTCHA (Web App Security)<br>
This project explored exploiting a weak CAPTCHA implementation in the OWASP Juice Shop web application. By leveraging Burp Suite's Intruder tool, I successfully bypassed the CAPTCHA challenge and:<br>
Submitted multiple fake customer feedbacks.<br>
Artificially inflated the customer rating to a high value.<br>
Technologies Used:<br>
OWASP Juice Shop (Web Application)<br>
Burp Suite Community Edition (Web Security Testing Tool)<br>
Impact:<br>
Inadequate CAPTCHA protection can be exploited to automate actions that could overwhelm the server with fake data, manipulate ratings, or potentially launch denial-of-service attacks.<br>
Key Takeaway:<br>
The project emphasizes the importance of robust anti-automation measures, such as strong CAPTCHA implementations, rate limiting, and other security features, to protect web applications from abuse.<br>
<br>
OWASP Juice Shop - Brute-Forcing Admin Password (Web App Security)<br>
This project focused on exploiting a weak password for the administrator account in OWASP Juice Shop. By using Burp Suite's Intruder tool and a password wordlist, I successfully:<br>
Brute-forced the admin password: Identified the weak password "admin123".<br>
Gained unauthorized access: Logged in as the administrator.<br>
Demonstrated the impact: Changed the admin password to a new value ("brandon").<br>
Technologies Used:<br>
OWASP Juice Shop (Web Application)<br>
Burp Suite Community Edition (Web Security Testing Tool)<br>
Password Wordlist (best1050.txt)<br>
Impact:<br>
Weak passwords, especially for privileged accounts, pose a significant security risk. They are vulnerable to brute-force attacks, potentially leading to unauthorized access, data breaches, and system compromise.<br>
Key Takeaway:<br>
The project emphasizes the importance of strong password policies, password managers, and Multi-Factor Authentication (MFA) to secure web applications and user accounts.<br>
<br>
OWASP Juice Shop - SQL Injection for User Login (Web App Security)<br>
This project focused on exploiting a SQL injection vulnerability in the login form of the OWASP Juice Shop web application. By crafting malicious payloads and utilizing Burp Suite's Intruder tool, I successfully gained unauthorized access to a specific user account ("Bender") without a password.<br>
Technologies Used:<br>
OWASP Juice Shop (Web Application)<br>
Burp Suite Community Edition (Web Security Testing Tool)<br>
SQL Injection Payloads (Auth_Bypass.txt)<br>
Impact:<br>
A single SQL injection vulnerability can allow attackers to bypass authentication and compromise any user account within the application.<br>
Key Takeaway:<br>
The project emphasizes the critical importance of secure coding practices and input validation to prevent SQL injection vulnerabilities in web applications.<br>
Contact: <br>
Email: Bmn986@outlook.com<br>
Linkedin: linkedin.com/in/brandon-noey<br>
Additional Notes:<br>
Ethical Hacking Disclaimer: <br>
The information contained within this repository is for educational and research purposes only. Penetration testing techniques demonstrated here are intended for authorized testing on personal environments or with explicit permission from the system owners. By accessing this repository, you agree to use the information ethically and responsibly.<br>
Do not:<br>
Use the information for malicious purposes or unauthorized penetration testing.<br>
Attempt to exploit vulnerabilities in systems you do not own or have permission to test.<br>
Cause harm or disruption to any system or network.<br>
This repository is for educational purposes only and the author(s) are not responsible for any misuse of the information.<br>
<br>
Project Maturity:<br>
These projects are for personal learning and exploration of offensive security techniques. They represent a limited scope and may not encompass the full methodology or rigor of a professional penetration test. A comprehensive professional penetration test would involve additional steps like detailed planning, scope definition, vulnerability scanning, exploitation verification, post-exploitation activities, and reporting, all conducted in accordance with ethical hacking principles and with proper authorization.<br>
Continuous Learning: <br>
The field of offensive security is constantly evolving, with new vulnerabilities and defensive techniques emerging all the time. I am committed to continuous learning and improvement in this domain. This repository reflects my ongoing exploration and experimentation with various offensive security tools and methodologies. I actively seek out new challenges, learning resources, and opportunities to enhance my skills and stay up-to-date with the latest advancements in the field.<br>
References: <br>
	This section lists resources I consulted during these offensive security projects. These references were helpful in understanding the vulnerabilities, crafting exploits, and learning best practices:<br>
OWASP Juice Shop Documentation: https://owasp.org/www-project-juice-shop/ (Details on functionalities and potential vulnerabilities within the Juice Shop application)<br>
PortSwigger Web Security Academy: https://portswigger.net/web-security (Tutorials and resources on various web security topics, including SQL Injection and Brute-forcing)<br>
OWASP Testing Guide: https://owasp.org/www-project-web-security-testing-guide/ (Comprehensive guide to web application security testing methodologies)<br>
Specific Vulnerability Tutorials (Optional):<br>
If you referenced specific tutorials or write-ups on exploiting the vulnerabilities you discovered (e.g., SQL Injection tutorial for beginners), you can list them here with links.<br>
