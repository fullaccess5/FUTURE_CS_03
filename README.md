# 🔐 API Security Risk Analysis

**Future Interns – Cyber Security Task 3 (2026)**

---

## 🔍 Objective

This project focuses on performing a **read-only API Security Risk Analysis** using the OWASP API Security Top 10 (2023).

---

## 🌐 APIs Tested

* https://jsonplaceholder.typicode.com
* https://reqres.in

---

## 🛠️ Tools Used

* Postman
* Browser DevTools
* Manual Header Analysis

---

## 📂 Repository Structure

```bash
FUTURE_CS_03/
│
├── README.md
├── report/
│   └── API_Security_Risk_Analysis_Report.pdf
│
└── evidence/
    ├── postman_requests.png
    ├── api_responses.png
    ├── headers_analysis.png
```

---

## 🧪 Summary

| Metric           | Value |
| ---------------- | ----- |
| Endpoints Tested | 12    |
| Total Risks      | 6     |
| High             | 2     |
| Medium           | 3     |
| Low              | 1     |

---

## 🚨 Key Findings

### 🔴 High

* Unauthenticated API access
* PII data exposure

### 🟠 Medium

* No rate limiting
* Missing security headers
* Predictable IDs

### 🟡 Low

* No token expiration

---

## 🛡️ Recommendations

### Immediate

* Implement authentication (JWT / OAuth2)
* Restrict sensitive data

### Short-Term

* Add security headers
* Implement rate limiting
* Use UUIDs instead of IDs

### Long-Term

* Token expiration & rotation
* Monitoring & logging

---

## 👨‍💻 Author

AMEGANDJI Akuete Anoumou Antoine
Cyber Security Intern – Future Interns (2026)
---------------------------------------------
