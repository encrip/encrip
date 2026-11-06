# Hi, I'm Encrypted 👋

I'm Saifullahi Khamisu, a full-stack developer and CEO of [atPay](https://atpay.ng). I build Flutter apps and PHP APIs for everyday payments in Nigeria. My networking and cloud computing background shapes how I approach security, from checking a TCP connection to tracing a wallet entry back to the payment that created it.

[Android apps](https://play.google.com/store/apps/dev?id=8907913731562967248&hl=en) · [Security tools](https://github.com/encrip/encrypted-security-tools) · [All repositories](https://github.com/encrip?tab=repositories)

## What I build

| Project | What it does |
|---|---|
| [atPay](https://atpay.ng) | A wallet for buying data and airtime and paying electricity and TV bills. My work covers the mobile app, provider integrations and customer support tools. |
| [Encrypted Security Tools](https://github.com/encrip/encrypted-security-tools) | My Python security projects include a TCP port scanner and an offline password strength analyzer. |
| Encrypted Web Auditor Pro | Checks headers, cookies and login forms within a defined scope. Its reports flag incomplete scans so readers can see what was actually checked. |
| Localhost Login Lab | Uses a local test account and synthetic passwords to study login responses. It stops on lockouts, rate limits or ambiguous results. |

## Latest work · 6 November 2026

I reviewed a PHP/MySQL application that handles identity requests and wallet payments. I traced who could approve a request, what proved a payment came from the provider, and what happened if two requests reached the same balance at once. I documented the findings, their potential impact and staging checks for each fix.

One lesson I’m taking back to my own work: test the **database result** as well as the HTTP response. If a provider delivers the same payment twice, both requests can receive an acknowledgement, but the ledger should contain exactly one credit.

<details>
<summary>Earlier milestones and learning roadmap</summary>

| Milestone | Evidence from the project |
|---|---|
| TCP Port Scanner | Interactive IPv4 input, connection timeouts and a summary of port states. |
| Password Strength Analyzer | Hidden input and local checks for common patterns. The initial version passed 9 unit tests. |
| Web Auditor Pro · 5 November | Passed 8 local tests covering scope, redirects, request limits and reporting. |
| Localhost Login Lab · 5 November | Passed 6 unit tests covering destination restrictions, response classification, stop conditions and demo candidates. |

**Next build:** IP & Subnet Calculator. After that I plan to work on DNS lookup, network discovery, packet analysis and TLS certificate inspection. My longer-term interests are log analysis, file integrity monitoring and digital forensics.

</details>

## Tools I work with

**Mobile and web:** Flutter, Dart, PHP, JavaScript, Java and REST APIs.  
**Data and infrastructure:** MySQL, SQLite, Firebase, Linux and Git.  
**Security learning:** Python sockets, Wireshark, Nmap, Burp Suite and OWASP guidance. I use controlled labs and systems I have permission to assess.

## Connect

I welcome collaboration on fintech, Flutter, Python security tools and networking projects.

[LinkedIn](https://linkedin.com/in/saifullah-khamisu-6a3604174/) · [X](https://twitter.com/atpay_wallet) · [Instagram](https://instagram.com/atpay_app/) · [TikTok](https://www.tiktok.com/@atpay_wallet) · [YouTube](https://www.youtube.com/c/atpaywallet) · [Facebook](https://fb.com/atpay/100094027181873/) · [Stack Overflow](https://stackoverflow.com/users/encrypted-ng)
