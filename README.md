# 🛠 Client Website Projects
> A centralised workspace for all client website builds — from intake brief to final delivery.

---

## 🔗 Live Links

| Tool | URL |
|------|-----|
| 📋 **Client Intake Form** | https://lilking2007.github.io/client-sites/intake-form/ |
| 📄 **Web Services Contract** | https://lilking2007.github.io/client-sites/contract/ |
| 🌐 **This Repo** | https://github.com/lilking2007/client-sites |

> **→ Send clients the intake form first:** https://lilking2007.github.io/client-sites/intake-form/
>
> **→ Send the contract when ready to sign:** https://lilking2007.github.io/client-sites/contract/

---

## 📁 Repo Structure

```
client-sites/
│
├── intake-form/              ← Live client brief form (deployed via GitHub Pages)
│   └── index.html
│
├── contract/                 ← Live web services contract (deployed via GitHub Pages)
│   └── index.html
│
├── clients/                  ← One folder per client project
│   ├── _template/            ← Copy this folder for every new client
│   │   ├── assets/           ← Logos, images, brand files
│   │   ├── exports/          ← Final build exports / screenshots
│   │   └── BRIEF.md          ← Paste the client's filled brief here
│   │
│   ├── client-name-2025/     ← Example: real client folder
│   └── ...
│
├── docs/                     ← Internal notes, process docs, templates
│   └── PROCESS.md
│
├── .gitignore
└── README.md                 ← You are here
```

---

## 🚀 How to Add a New Client Project

1. **Send the intake form link** to your client and wait for them to fill it in
2. **Send the contract link** once the scope and fee are agreed
3. **Duplicate the `_template` folder** inside `/clients/` and rename it: `client-name-YYYY`
4. **Paste the filled brief** into `BRIEF.md` inside their folder
5. **Drop their assets** (logo, photos, etc.) into `assets/`
6. **Build the site** using Cursor, v0, Bolt, or your preferred AI platform
7. **Save the final export / screenshots** into `exports/`
8. **Commit and push** — done ✅

```bash
# Quick start for a new client
cp -r clients/_template clients/jane-doe-2025
cd clients/jane-doe-2025
# Add BRIEF.md content, assets, then build
```

---

## 📋 Client Projects

| # | Client | Status | Live URL | Date |
|---|--------|--------|----------|------|
| 1 | *(Add first client here)* | 🟡 In Progress | — | — |

> Update this table as you take on projects.

**Status key:** 🟡 In Progress &nbsp;|&nbsp; 🔵 In Review &nbsp;|&nbsp; 🟢 Live &nbsp;|&nbsp; ⚫ Complete

---

## ⚙️ GitHub Pages Setup

This repo uses **GitHub Pages** to host the intake form and contract as live URLs.

### First-time setup:
1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save**
5. Both tools will be live at their respective URLs above

> Takes ~2 minutes to go live after setup. Refresh if it doesn't appear immediately.

---

## 🧰 Tech Stack & Tools Used

| Purpose | Tool |
|---------|------|
| Version control | GitHub |
| Form & contract hosting | GitHub Pages |
| Contract submissions | Formspree |
| AI site builder | Cursor / v0 / Bolt |
| Asset storage | This repo (`/assets`) |
| Brief intake | Custom HTML form |

---

## 📝 Notes

- Keep client folders **private** if this repo is public — consider using a private repo or keeping sensitive briefs local
- Always get the brief **before** you start building — it saves hours of revision
- The intake form auto-copies a text summary to clipboard when submitted, ready to paste into any AI build platform
- The contract auto-generates a unique reference number (e.g. `RK-8H6GFO`) for every session and emails you via Formspree when signed

---

*Built and maintained by Ryan Kipchumba · Updated 2025*
