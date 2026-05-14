# FUTURE_CS_03 — API Security Risk Analysis

## Internship Details

**Program:** Future Interns Cyber Security Internship  
**Task:** Task 3 — API Security Risk Analysis  
**Analyst:** Shaik Sami Hassan  

---

## Objective

This project focused on performing a professional read-only API security assessment on a public demo API.

The goal was to evaluate:

- Authentication enforcement
- Object-level access behavior
- Error handling
- Input validation
- Security headers
- Rate limiting
- API endpoint exposure

---

## Target API

**API Tested:** ReqRes Demo API  
ReqRes: [ReqRes API](https://reqres.in?utm_source=chatgpt.com)

---

## Tools Used

- [Postman](https://www.postman.com?utm_source=chatgpt.com)
- Manual API Analysis
- Browser Inspection
- Security Documentation Review

---

## Security Tests Performed

| Finding ID | Area | Observation | Risk |
|------------|------|-------------|------|
| F-01 | Authentication | Unauthorized access blocked | Low |
| F-02 | Authenticated Access | Valid API key grants access | Low |
| F-03 | Object Access | Direct object access observed | Informational |
| F-04 | Error Handling | No information leakage | Low |
| F-05 | Security Headers | Security protections enabled | Low |
| F-06 | Input Validation | Invalid input handled safely | Low |

---

## Project Structure

```text
FUTURE_CS_03/
├── evidence/
├── notes/
├── postman_collection/
├── report/
└── README.md
```

---

## Ethical Notice

This assessment was conducted only on publicly accessible demo APIs using safe, read-only testing methods.

No exploitation, bypass attempts, flooding, brute forcing, or harmful testing was performed.

---

## Learning Outcome

This project strengthened practical understanding of:

- API Authentication
- Authorization Concepts
- API Reconnaissance
- Security Headers
- Input Validation
- Application Security Methodology
