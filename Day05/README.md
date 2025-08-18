# OWASP Top 10 – Web Application Security

The **OWASP Top 10** is a globally recognized awareness document for developers and security professionals.  
It highlights the **most critical vulnerabilities** in modern web applications.

---

## 1. Broken Access Control
Users gain privileges or access beyond their intended permissions.  

- **Risk:** Unauthorized access or privilege escalation  
- **Example:** A normal user accessing another person’s account or admin panel  

---

## 2. Cryptographic Failures
Sensitive data exposure due to weak, missing, or incorrect cryptographic protection.  

- **Risk:** Data theft or interception  
- **Example:** Transmitting login credentials in plain text over HTTP → vulnerable to MITM attacks  

---

## 3. Injection
Untrusted input is passed into an interpreter (SQL, OS commands, LDAP, etc.).  

- **Risk:** Attackers gain control over application logic or database  
- **Example (SQL Injection):**  
  ```sql
  SELECT * FROM users WHERE username = 'admin' --' AND password = '';
---
## 4. Insecure Design
Security flaws built into the system at the **design stage**.  

- **Risk:** Application is inherently unsafe, even before coding  
- **Examples:**  
  - CAPTCHA system that can be bypassed easily  
  - File upload feature allows `.exe` but restricts `.png`  

---

## 5. Security Misconfiguration
Weak or default settings left unchanged, incomplete configurations, or unnecessary features enabled.  

- **Risk:** Attackers exploit overlooked settings  
- **Example:** Leaving admin console exposed to the public  

---

## 6. Vulnerable and Outdated Components
Applications using outdated libraries, plugins, or frameworks with known flaws.  

- **Risk:** Attackers exploit public vulnerabilities  
- **Example:** An outdated Apache version with known exploits  

---

## 7. Identification and Authentication Failures
Improper authentication or session management.  

- **Risk:** Unauthorized access to user accounts  
- **Example:** Weak password enforcement or exposing session tokens in URLs  

---

## 8. Software and Data Integrity Failures
Application relies on untrusted or unverified software, code, or updates.  

- **Risk:** Hackers inject malicious software into trusted applications  
- **Example:** Using insecure CI/CD pipelines or installing tampered updates  

---

## 9. Security Logging and Monitoring Failures
Failure to log important events or monitor suspicious activity.  

- **Risk:** Attacks remain undetected for long periods  
- **Example:** No alert system for repeated failed login attempts  

---

## 10. Server-Side Request Forgery (SSRF)
Application’s server is tricked into sending requests to unintended destinations.  

- **Risk:** Attackers gain access to internal systems or sensitive data  
- **Example:** Manipulated URL forces the server to fetch internal resources  
