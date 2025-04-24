# 🛡️ SQL Injection Writeups – TryHackMe & PortSwigger Labs

**Author:** Priyanka  
**Focus Areas:** SQL Injection, Authentication Bypass, Blind SQLi, UNION attacks  
**Tools Used:** Burp Suite, Browser Dev Tools, TryHackMe VM  
**Status:** ✅ Completed

---

## 🔍 TryHackMe – SQL Injection Room

🔗 [TryHackMe: SQL Injection](https://tryhackme.com/room/sqlinjectionlm)  
**Topics Covered:**
- Manual SQL Injection
- Error-based injection
- Authentication bypass
- Extracting data with SQLi

**Key Takeaways:**
- How to spot SQLi vulnerabilities in login forms and GET parameters.
- Used `' OR '1'='1` for login bypass.
- Used `UNION SELECT` to extract usernames and passwords from the database.

---

## 💥 PortSwigger Labs Completed

### 1. 🔐 [Retrieve hidden data](https://portswigger.net/web-security/sql-injection/lab-retrieve-hidden-data)
- Used SQL injection to bypass filtering and extract hidden items from the product database.

### 2. 🚪 [Login bypass](https://portswigger.net/web-security/sql-injection/lab-login-bypass)
- Successfully bypassed login using `' OR 1=1--`.

### 3. 🧠 [Querying DB version - Oracle](https://portswigger.net/web-security/sql-injection/examining-the-database/lab-querying-database-version-oracle)
- Used injection in `ORDER BY` and `UNION SELECT` to determine Oracle DB version.

### 4. 🔢 [Retrieve multiple values in a single column](https://portswigger.net/web-security/sql-injection/union-attacks/lab-retrieve-multiple-values-in-single-column)
- Performed UNION-based SQLi to extract usernames and emails.

### 5. 🕰️ [Blind SQLi with time delays](https://portswigger.net/web-security/sql-injection/blind/lab-time-delays)
- Used `SLEEP(5)` payloads to confirm and extract blind SQLi via timing.

---

## 🧠 Skills Improved

- Identifying SQL Injection entry points
- Using SQL payloads to retrieve hidden data
- Mastering authentication bypass techniques
- Practicing time-based blind SQLi
- Familiarity with Oracle DB queries

---

## 🚀 What's Next?

- Complete advanced labs on blind SQLi and error-based injection
- Build a vulnerable lab (like DVWA or bwapp) locally
- Explore real-world cases of SQLi from HackerOne/bug bounty reports

---

📬 **Open to internships and collaborations in cybersecurity.**  
Let’s connect on [LinkedIn](https://www.linkedin.com/in/your-link)!

