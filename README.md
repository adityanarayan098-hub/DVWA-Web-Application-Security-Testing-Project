# 🔐 DVWA-Web-Application-Security-Testing-Project

## 📌 Overview

This project demonstrates hands-on web application security testing using **DVWA (Damn Vulnerable Web Application)** in a controlled lab environment on **Kali Linux**.

The purpose of this project is to gain practical experience in identifying, testing, and understanding common web vulnerabilities using industry-recognized tools.

This project is ideal for beginner cybersecurity learners and showcases practical offensive security skills for interviews, internships, and GitHub portfolios.

---

## 🎯 Objectives

- Understand common web application vulnerabilities
- Practice manual security testing techniques
- Learn HTTP request/response interception
- Gain experience with penetration testing tools
- Document findings professionally

---

## 🛠️ Tools & Technologies Used

- Kali Linux
- Firefox Browser
- MariaDB
- Apache / DVWA Service

---

## 1️⃣ DVWA Security Level: Low

### 📌 Configuration

The DVWA security level was configured to **Low** to enable beginner-friendly testing of common web vulnerabilities in a controlled lab environment.

### 🎯 Purpose

This setting was used to practice:

- SQL Injection  
- Cross-Site Scripting (XSS)  
- Command Injection  
- Weak Input Validation  
- Insecure Web Application Behavior

### ✅ Result

Successfully configured DVWA to Low security mode and performed hands-on vulnerability testing.

[DVWA Security Level Low] <img width="1295" height="756" alt="Screenshot 2026-04-29 at 12 28 33 PM" src="https://github.com/user-attachments/assets/7aec2e27-04aa-4faf-aa36-62ef111fcd36" />

## 🧪 Vulnerabilities Tested

### 2️⃣ SQL Injection

**Description:**

Tested improper input sanitization in database queries.

**💉 Payload Example**

sql
1' OR '1'='1

### ✅ Result

Successfully manipulated backend query logic and retrieved multiple records.

[SQL Injection] <img width="1522" height="911" alt="Screenshot 2026-04-28 at 10 20 25 PM" src="https://github.com/user-attachments/assets/7e5ace21-07f8-499f-9ee2-8937c2dedf24" />

## 3️⃣ Reflected Cross-Site Scripting (XSS) 

**📌 Description**

Injected JavaScript into reflected user input fields.

**💉 Payload Example**

**HTML**

<script>alert('XSS')</script>

### ✅ Result

JavaScript executed successfully in browser popup.

[XSS Popup] <img width="1566" height="955" alt="Screenshot 2026-04-28 at 10 31 28 PM" src="https://github.com/user-attachments/assets/2e817603-07d7-4496-a03f-f6383e447a9c" />


## 4️⃣ Command Injection

**📌 Description**

Tested insecure server-side command execution through user input.

**💉 Payload Example**

127.0.0.1 && whoami

### ✅ Result

Additional system command executed successfully.

[Command Injection] <img width="1296" height="673" alt="Screenshot 2026-04-28 at 10 55 58 PM" src="https://github.com/user-attachments/assets/0b36f33c-e052-49b0-866b-f3dc7dea95b6" />

## 5️⃣ HTTP Request Interception

🛠️ Tool Used

Burp Suite

**📌 Description**

Captured and analyzed HTTP requests between browser and DVWA.

### ✅ Result

[Burp Intercept] <img width="1372" height="615" alt="Screenshot 2026-04-28 at 10 44 28 PM" src="https://github.com/user-attachments/assets/70663adf-81cf-400c-9518-e607993c97bc" />

## 🔐 Security Recommendations

**SQL Injection Prevention**

Use parameterized queries

Validate input

Use least privilege DB accounts

**XSS Prevention**

Output encoding

Input sanitization

Implement Content Security Policy (CSP)

**Command Injection Prevention**

Avoid shell execution

Sanitize inputs

Use allowlists

Run apps with least privileges

## 📚 Skills Gained

Web Application Security Testing

Vulnerability Assessment

Manual Penetration Testing

Burp Suite Usage

HTTP Traffic Analysis

Security Reporting

OWASP Awareness

## 💼 Resume Value

Performed hands-on web application security testing using DVWA and Burp Suite. Identified SQL Injection, XSS, and Command Injection vulnerabilities with remediation recommendations.

## 🚀 Future Enhancements

Add OWASP Juice Shop testing

Use OWASP ZAP scanner

Session management testing

Authentication bypass testing

Automated reporting

## ⚠️ Disclaimer

This project was conducted in a legal, local lab environment using DVWA for educational and ethical learning purposes only.

## 📬 Contact

- GitHub: Aditya Narayan  

- LinkedIn: www.linkedin.com/in/adityanarayan2990
