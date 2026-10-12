# WorkforceHub — Workforce Management + HR Copilot

An independent **portfolio demo by Wenting Wang** for managing four workforce categories: **FTE, Contractor, Summer Intern and TDP (Technology Development Program)**.

## What's included

- Responsive professional HR dashboard and workforce metrics
- Fictional workforce directory with add-record, classification filters and CSV export
- Staffing requisition requests and hiring pipeline
- Onboarding / offboarding activity tracker
- Contractor agreement-end and renewal visibility
- Summer internship program and TDP rotation planning
- Development goal tracking
- Budget and capacity estimates (illustrative only)
- Workforce analytics and team distribution
- Scripted HR Copilot chatbot with suggested questions
- Local browser storage to preserve demo changes; reset button

## Publish for free with GitHub Pages

1. Create a **public** GitHub repository, e.g. `workforce-management-demo`.
2. Upload `index.html`, `styles.css`, `app.js`, and `.nojekyll` to the **repository root**, not a `/docs` subfolder.
3. Open **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, and click **Save**.
4. After deployment, the URL should be `https://YOUR_USERNAME.github.io/workforce-management-demo/`.

Or from Git Bash (after creating the repo):

```bash
git init
git config user.name "Wenting Wang"
git config user.email "YOUR_GITHUB_EMAIL"
git add .
git commit -m "Launch workforce management demo"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/workforce-management-demo.git
git push -u origin main
```

If the `origin` remote already exists, inspect `git remote -v` and do not add it again. For a GitHub account named `elliewang`, substitute that for `YOUR_USERNAME`.

## Security and deployment notes

**This is not an actual HRIS or AI system.** All people, pay, hiring details and tasks are *fictional*. Browser localStorage saves demo changes on the current device; this is not secure storage. Do **not** enter real personnel information, salary data, legal information, employee IDs, or other protected data. The chatbot uses local scripted keyword responses. There are no network calls, authentication, payroll processing, actual notifications, or employer-system connections. No API keys or paid services are required.

To build a production system, you would need authenticated role-based access, secure server-side storage, consent/privacy safeguards, audit logs, compliant data retention, HRIS/payroll integrations and a secured LLM gateway for a real AI chatbot.
