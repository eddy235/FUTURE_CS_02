# FUTURE_CS_02
API Security Risk Analysis (Modern SaaS Skill)
## Project Overview
This project conducts a professional API security risk analysis on the public test API `jsonplaceholder.typicode.com`. The analysis identifies vulnerabilities based on the OWASP API Security Top 10 framework and provides remediation recommendations.

## 🎯 Objective
- Identify common API security risks in a real-world (test) API
- Assess authentication, authorization, and data exposure issues
- Document findings in a professional security report
- Demonstrate API security testing skills relevant for SaaS security roles

## 🛠️ Tools Used
- **Postman**: API request testing and inspection
- **Browser DevTools**: Header and response analysis
- **OWASP API Security Top 10**: Vulnerability classification framework

## 📝 Methodology
1. **Documentation Review**: Analyzed API documentation for endpoints and expected behavior
2. **Endpoint Testing**: Performed read-only GET requests to all endpoints
3. **Risk Identification**: Mapped findings to OWASP API Security Top 10 categories
4. **Severity Assessment**: Classified risks as Critical/High/Medium/Low
5. **Remediation Planning**: Developed actionable fixes for each vulnerability

## 🔍 Key Findings Summary

| Risk | OWASP Category | Severity |
|------|----------------|----------|
| No Authentication Required | API2: Broken Authentication | 🔴 Critical |
| No Rate Limiting | API4: Lack of Resources | 🔴 Critical |
| Broken Object Level Authorization (IDOR) | API1: BOLA | 🟠 High |
| Excessive Data Exposure | API3: Excessive Data Exposure | 🟡 Medium |
| Missing Security Headers | API7: Security Misconfiguration | 🟢 Low |

## 🚀 Remediation Priorities
1. Implement authentication (OAuth 2.0/JWT) for all endpoints
2. Add rate limiting to prevent abuse and DoS attacks
3. Implement object-level authorization checks
4. Create DTOs to limit data exposure
5. Add security headers (CSP, X-Frame-Options, etc.)

## ⚠️ Disclaimer
This analysis was performed on a public API explicitly designed for testing. All tests were read-only and conducted ethically. This project is for educational and portfolio purposes only.

## 📚 References
- [OWASP API Security Top 10](https://github.com/OWASP/API-Security)
- [JSONPlaceholder](https://jsonplaceholder.typicode.com)
- [API Security Checklist](https://github.com/shieldfy/API-Security-Checklist)

## 👤 Author
Eddy Biegon
[Link to LinkedIn/Portfolio - (https://www.linkedin.com/in/eddy-biegon-60385b296/)]
