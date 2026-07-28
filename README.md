## Automation Portfolio

A set of end-to-end automation builds, each covering a different tool and business domain — every one shipped with the full package a real engagement needs: working code/scenario, sample data, tests proving the logic is correct, and the business documentation (SOP, before/after impact analysis, user guide) that makes it usable by a team, not just runnable by me.

| # | Project | Tool | Domain | What it does |
|---|---|---|---|---|
| 1 | [Chargeback Rebuttal Automation](https://github.com/squesadag2000/chargebackrebuttalautomation) | Python (ETL + PDF) | Payments / Risk Ops | Auto-drafts evidence-backed dispute rebuttal letters from gateway + OMS data; flags weak cases for manual review instead of guessing |
| 2 | [Support Inbox Automation](https://github.com/squesadag2000/supportinboxautomation) | Google Apps Script | Customer Support | Turns a shared Gmail inbox into a lightweight helpdesk — auto-triage, SLA tracking with Chat escalation, load-balanced routing, daily digest |
| 3 | [Lead Qualification & Routing](https://github.com/squesadag2000/leadqualification-routing) | Zapier | Sales / RevOps | Scores inbound leads 0–100 via a Code by Zapier JS step and routes them into CRM/Slack/email actions by tier using Paths |
| 4 | [New Hire Onboarding Automation](https://github.com/squesadag2000/newhireonboardingautomation) | Make.com | People Ops / HR | Provisions a new hire's entire first day from one signed-offer row — account, calendar, tasks, Slack, welcome emails — with idempotency and error handling |
| 5 | New Hire Automation (RPA) | Power Automate Desktop | Operations | *Coming soon* |

**Every project in this portfolio uses a fictional company and synthetic data** — built to demonstrate the full skill set (requirements → build → test → document → quantify impact) without exposing any real client's process or information.

### What makes these different from a typical "no-code portfolio"

- **Tested, not just built.** Every project ships unit tests for its core logic — classification rules, scoring algorithms, date/SLA math, mapper formulas — run with Node or Python, independent of the platform's own runtime.
- **Documented like a real handoff.** Each one includes an SOP, a quantified before/after impact summary (with the math shown, not just a headline number), and a user guide — the artifacts a client actually needs to run the thing without me.
- **Platform-idiomatic, not copy-pasted logic.** The Zapier and Make projects intentionally lean on each platform's own strengths (Code by Zapier + Paths vs. Make's Router + Data Store + error handlers) rather than treating every no-code tool as interchangeable.
