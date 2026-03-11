# FUTURE_CS_01
# Vulnerability Assessment Report – Live Website Analysis

## Overview

This project presents a **Vulnerability Assessment Report** conducted as part of **Cyber Security Internship Task 1 (2026)** by Future Interns.

The objective of this task was to analyze a publicly accessible website and identify potential security weaknesses using **ethical, read-only testing methods**.

The assessment focuses on identifying misconfigurations, exposed services, and security risks that may affect the confidentiality, integrity, or availability of the web application.

---

## Website Tested

The website analyzed during this assessment:

```
https://www.demoblaze.com
```

This site is a public demo e-commerce application commonly used for learning and security testing practice.

---

## Scope of Assessment

The testing was conducted under **read-only and ethical guidelines**.

### Allowed Activities

* Public page analysis
* Passive scanning
* HTTP header inspection
* Cookie inspection
* Service enumeration

### Restricted Activities

* Exploitation attempts
* Brute force attacks
* Denial-of-Service testing
* Authentication bypass attempts

---

## Tools Used

The following tools were used during the vulnerability assessment:

* **Nmap** – network scanning and service discovery
* **OWASP ZAP (Passive Scan)** – vulnerability detection without exploitation
* **Browser DevTools** – inspecting cookies, headers, and client-side behavior
* **Burp Suite (Repeater)** – HTTP request and response inspection
* **Canva** – professional vulnerability report design

---

## Key Security Observations

During the analysis, several potential security concerns were reviewed:

* Open web service ports
* Cookie security attributes
* HTTP request and response behavior
* Application configuration exposure

These observations were analyzed and classified according to risk level.

---

## Project Structure

```
FUTURE_CS_01
│
├── screenshots
│   ├── demoblaze_cookie_analysis.png
│   ├── nmap_service_scan.png
│   └── burp_http_request_analysis.png
│
├── report
│   └── Vulnerability_Assessment_Report.pdf
│
└── README.md
```

---

## Report

The full **Vulnerability Assessment Report** containing detailed findings, risk classification, and remediation recommendations is available in the **report folder**.

---

## Author

Suraj Kumar
Cyber Security Internship – Future Interns (2026)

