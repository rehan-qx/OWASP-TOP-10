# 🛡️ OWASP Top 10 — Security Research Guides

> A collection of in-depth, practical security guides covering the OWASP Top 10 vulnerabilities — written for Bug Bounty Hunters, Penetration Testers, and Security Researchers.

---

## 📁 Repository Contents

| File | Topic | Description |
|------|-------|-------------|
| [`SSRF.pdf`](./SSRF.pdf) | Server-Side Request Forgery | Detection, exploitation, cloud attack chains & bypasses |
| [`SQLi.pdf`](./SQLi.pdf) | SQL Injection | All types, dumping data, WAF bypass & sqlmap usage |
| [`CSRF_Guide.pdf`](./CSRF_Guide.pdf) | Cross-Site Request Forgery | Attack examples, SameSite cookies, token bypass & POC crafting 
| [`OpenRedirect_Guide.pdf`](./OpenRedirect_Guide.pdf) | Open Redirect | PoC examples, OAuth chaining, payload bypass tricks & bounty reporting |
| [`VMware_Security_Guide_EN.pdf`](./VMware_Security_Guide_EN.pdf) | VMware Security Guide | Kali Linux setup, VM isolation, WSL risks, network modes & one-click isolation script |


> ⚙️ More guides coming soon — XSS, IDOR, XXE, RCE & more.

---

## 📖 What's Inside Each Guide

### 🔴 SSRF — Server-Side Request Forgery
- What SSRF is & how it works
- Where to find it (parameters & features)
- Key targets — AWS Metadata, Redis, Docker, Kubernetes
- Blind SSRF detection via OOB tools
- Cloud exploitation chains (AWS, GCP, Azure)
- Defense bypass tricks (DNS Rebinding, Open Redirects)

### 🔴 SQLi — SQL Injection
- 5 types — Classic, Blind, Time-Based, OOB, Second-Order
- Where to find it — login forms, headers, cookies
- Identifying the database engine (MySQL, PostgreSQL, MSSQL, Oracle)
- Dumping data with UNION-based queries
- Bypassing WAFs & filters
- Automation with sqlmap

### 🔴 CSRF — Cross-Site Request Forgery
- How CSRF exploits browser trust
- POST & GET-based attack examples with POC code
- Advanced CSRF with JSON, CORS & Preflight
- Bypassing CSRF tokens & weak implementations
- SameSite cookies — Lax vs Strict vs None
- Step-by-step testing methodology with Burp Suite

### 🟢 VMware Security Guide
- Kali Linux installation on external disk via VMware
- Manual partitioning — preserve existing data safely
- WSL security risks — why it’s NOT a true isolated environment
- VM network modes — NAT vs Bridged vs Host-only vs No Network
- Full VM isolation checklist — shared folders, USB, VMware Tools
- One-click isolation script — lock down your VM instantly
- 7 Golden Rules every security researcher should follow

---

## 🎯 Who Is This For?

- 🐛 **Bug Bounty Hunters** — looking for practical exploitation techniques
- 🔍 **Penetration Testers** — needing structured reference guides
- 🎓 **Security Students** — learning OWASP Top 10 from scratch
- 👨‍💻 **Developers** — understanding vulnerabilities to build better defenses

---

## ⚠️ Disclaimer

> These guides are created **strictly for educational purposes** and authorized security research.  
> Never test on systems you don't own or have explicit permission to test.  
> The author is not responsible for any misuse of this information.

---

## 👤 Author

**N1xR00t** — Cybersecurity Researcher | Bug Bounty Hunter | Offensive Security 

- 🐙 GitHub: [github.com/rehan-qx](https://github.com/rehan-qx)
- 💼 LinkedIn: *[https://www.linkedin.com/in/rehanqx/]*

---

## ⭐ Support

If you find these guides helpful, please consider giving this repo a **star ⭐** — it helps others find this resource!

[![GitHub stars](https://img.shields.io/github/stars/rehan-qx/OWASP-TOP-10?style=social)](https://github.com/rehan-qx/OWASP-TOP-10)
