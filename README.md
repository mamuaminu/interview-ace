# Interview Ace

> Security interview prep command center — parse job descriptions, build a targeted question bank, and practice structured answers.

## What it does

1. **Paste a Job Description** — copy any security job posting and paste it in
2. **Keyword Extraction** — the parser scans for security-relevant skills and technologies
3. **Question Bank** — generates behavioral and technical questions matched to the JD keywords
4. **Answer Builder** — write and refine your answers with live feedback
5. **STAR Framework** — structure behavioral answers using the STAR method (Situation, Task, Action, Result)
6. **Export** — download your full prep as a markdown file to review or share

## Usage

No server, no install, no dependencies. Just open `index.html` in any modern browser.

```bash
# Clone and open
git clone https://github.com/mamuaminu/interview-ace.git
cd interview-ace
open index.html   # macOS
xdg-open index.html  # Linux
start index.html   # Windows
```

## How to Use It

### Step 1 — Parse a Job Description
- Paste the full job description text into the **Job Description** panel (left side)
- Click **Parse** to extract keywords
- Keywords appear as tags in the **Question Bank** panel

### Step 2 — Review Generated Questions
- Questions are grouped by type: **behavioral**, **technical**, or **company-specific**
- Filter by type using the panel tabs
- Click any question to select it for answering

### Step 3 — Write Your Answer
- Use the **Answer Builder** panel to draft your response
- Use **STAR Builder** to structure behavioral answers:
  - **S**ituation — describe the context
  - **T**ask — explain your responsibility
  - **A**ction — detail exactly what you did
  - **R**esult — share the measurable outcome

### Step 4 — Export
- Click **Export Prep** to download a markdown file with all your questions and answers

## Features

- **Security-specific keyword dictionary** — understands500+ security terms, tools, and certifications
- **STAR method** for behavioral questions
- **Question filtering** by type: behavioral, technical, company-research
- **Local storage** — all data stays in your browser's localStorage between sessions
- **Zero dependencies** — single HTML file, works offline
- **No account required** — no sign-up, no login, no data sent anywhere

## Keyword Categories Covered

The parser recognizes keywords across:
- Network security (firewall, IDS/IPS, VLAN, BGP, DNS, MITM)
- Web application security (SQLi, XSS, CSRF, OWASP Top 10, JWT, OAuth)
- Cloud security (AWS IAM, shared responsibility, Zero Trust, SSRF)
- Cryptography (AES, RSA, TLS, hashing, salts, PKI)
- Incident response (IR lifecycle, triage, forensics, chain of custody)
- Compliance (CIA triad, PCI DSS, NIST CSF, ISO 27001, GDPR)
- Pentest/Red Team (recon, exploitation, lateral movement, C2, privilege escalation)
- OSINT (Shodan, Censys, Google dorking, reconnaissance)

## Files

```
interview-ace/
├── index.html    # All-in-one app (HTML + CSS + JS)
└── README.md     # This file
```

---

By Muhammad Aminu Musa
