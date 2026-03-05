# 🐞 Bug Bounty Report Example

**Platform:** HackerOne  
**Target:** [Redacted]  
**Vulnerability Type:** SQL Injection  

## 📝 Summary
Discovered a SQL injection vulnerability in the login form due to unsanitized user input.

## 🔍 Steps to Reproduce
1. Navigate to the login page.  
2. Enter payload `' OR '1'='1` in the username field.  
3. Observe successful bypass of authentication.

## 🎯 Impact
- Unauthorized access to user accounts.  
- Potential data leakage.

## ✅ Recommendation
- Implement parameterized queries.  
- Sanitize and validate all user inputs.

---

⭐️ *Always learning, always securing.*
