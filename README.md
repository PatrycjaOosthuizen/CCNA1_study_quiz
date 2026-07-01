# CCNA 1 Study Quiz — PoCodes

An interactive browser-based study quiz for the **Cisco CCNA 1 (ITN — Introduction to Networks)** certification exam, built under the **PoCodes** brand.

🌐 **Live site:** [ccna-1.netlify.app](https://ccna-1.netlify.app)

---

## About

This quiz tool was built to support active recall and exam preparation for CCNA 1 topics including:

- Network models (OSI and TCP/IP) and layer functions
- IPv4 and IPv6 addressing, subnetting and VLSM
- Network protocols (HTTP/S, DNS, DHCP, FTP, SSH, SNMP, ARP, ICMP)
- Transport layer — TCP vs UDP, ports, windowing and handshake
- Data Link layer — Ethernet, MAC/LLC sublayers, CSMA/CD, frame structure
- Physical layer — UTP, fibre optic, connectors and media types
- Network security fundamentals — AAA framework, threats, attacks
- Switching and routing fundamentals
- IPv6 — global unicast, link-local, SLAAC, EUI-64, NDP
- Cisco IOS CLI — privilege modes, SSH, configuration management

The quiz contains **163 questions** with detailed summaries, per-option explanations, and exhibit images for scenario-based questions.

Explanations written to support active recall and knowledge retention.

---

## Features

- ✅ 163 CCNA 1 exam-style questions
- ✅ Multiple choice and multi-select (choose two/three) question types
- ✅ Case variant questions — multiple versions of the same question with different answer sets
- ✅ Exhibit images for topology, CLI output and diagram questions
- ✅ Detailed summary for every question explaining the concept
- ✅ Per-option explanations showing why each answer is correct or incorrect
- ✅ Score tracking and results summary
- ✅ Question review tool (`ccna1_review.html`) for studying all questions at once
- ✅ Fully browser-based — no installation or backend required
- ✅ Mobile friendly

---

## Files

| File                | Description                                              |
| ------------------- | -------------------------------------------------------- |
| `index.html`        | Main quiz application entry point                        |
| `ccna1_app.js`      | Quiz logic and interactivity                             |
| `ccna1_data.js`     | All 163 questions with answers, summaries, and images    |
| `ccna1_style.css`   | Styling and layout                                       |
| `ccna1_review.html` | Question review tool — browse all questions with answers |

---

## How to Use

### Online

Visit [ccna-1.netlify.app](https://ccna-1.netlify.app) — no setup needed.

### Local

1. Clone the repository:
```bash
git clone https://github.com/PatrycjaOosthuizen/CCNA1_study_quiz.git
```
2. Open the folder in VS Code
3. Use **Live Server** extension to open `index.html`
4. The quiz runs entirely in the browser — no dependencies to install

---

## Per-Option Explanations

After answering, every single option reveals an inline explanation:

- ✓ **Green** — what this is and exactly why it is correct
- ✗ **Red** — what this is and why it is wrong

A **📖 Topic Summary** panel also appears below each answered question covering the broader concept.

---

## Navigation

| Control | Action |
| ------- | ------ |
| **Check Answer** | Reveal correct/wrong options and all explanations |
| **Next →** | Advance to the next question |
| **← Back** | Return to the previous question (removes last result) |
| **Skip** | Show the correct answer without scoring |
| **CCNA 1** (top-left badge) | Return to the main menu from anywhere |

---

## Score Screen

After completing a quiz you see:

- A percentage ring coloured green (≥83%), yellow (≥65%), or red (below 65%)
- Breakdown of Correct / Wrong / Skipped / Memorise counts
- A note showing exactly how many questions were scored
- **Review Wrong** — click any item to expand the correct answer and topic summary
- **🔁 Practice Wrong** — jump straight into a practice session of only your missed questions

---

## Review Tool

Open `ccna1_review.html` via Live Server to access the question review tool.

Features:

- Browse all 163 questions with correct answers highlighted
- Jump directly to any question by number
- Filter by question range
- Per-option explanations visible at a glance

---

## Tech Stack

- Vanilla JavaScript (no frameworks)
- HTML5 + CSS3
- Deployed on Netlify
- Questions stored as a JavaScript data array

---

## About PoCodes

PoCodes is an educational brand creating interactive learning tools for IT certifications. This is part of a series of CCNA study quiz tools covering CCNA 1, 2, and 3.

---

## Also Available

| Quiz | Link |
| ---- | ---- |
| CCNA 2 — Switching, Routing and Wireless Essentials | [ccna-2.netlify.app](https://ccna-2.netlify.app) |
| CCNA 3 — Enterprise Networking, Security & Automation | [ccna-3.netlify.app](https://ccna-3.netlify.app) |

---

## Disclaimer

This quiz is an independent study tool created for educational purposes. It is not affiliated with or endorsed by Cisco Systems. CCNA® is a registered trademark of Cisco Systems, Inc.

---

_Built with ❤️ by PoCodes_
