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

## 🧪 Vulnerabilities Tested

### 1️⃣ SQL Injection

**Description:**

Tested improper input sanitization in database queries.

**💉 Payload Example**

sql
1' OR '1'='1

**Result**

Successfully manipulated backend query logic and retrieved multiple records.

[SQL Injection] <img width="1522" height="911" alt="Screenshot 2026-04-28 at 10 20 25 PM" src="https://github.com/user-attachments/assets/7e5ace21-07f8-499f-9ee2-8937c2dedf24" />

## 2️⃣ Reflected Cross-Site Scripting (XSS) 

**📌 Description**

Injected JavaScript into reflected user input fields.

**💉 Payload Example**

**HTML**

<script>alert('XSS')</script>


**Result**

JavaScript executed successfully in browser popup.

[XSS Popup] <img width="1566" height="955" alt="Screenshot 2026-04-28 at 10 31 28 PM" src="https://github.com/user-attachments/assets/2e817603-07d7-4496-a03f-f6383e447a9c" />



