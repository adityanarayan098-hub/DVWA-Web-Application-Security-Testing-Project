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

## Reflected Cross-Site Scripting (XSS) 

**📌 Description**

Injected JavaScript into reflected user input fields.

**HTML**

<script>alert('XSS')</script>

**Result**

JavaScript executed successfully in browser popup.

![XSS Popup](Screenshots/xss_popup.png)



