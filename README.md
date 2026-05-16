# 🛠 Client Website Projects

> A centralised workspace for all client website builds — from intake brief to final delivery.

---

## 🔗 Live Links

| Tool | URL |
|------|-----|
| 📋 **Client Intake Form** | `https://YOUR-USERNAME.github.io/client-sites/intake-form/` |
| 🌐 **This Repo** | `https://github.com/YOUR-USERNAME/client-sites` |

> **→ Send clients this link to fill in before every build:** `https://YOUR-USERNAME.github.io/client-sites/intake-form/`

---

## 📁 Repo Structure

```
client-sites/
│
├── intake-form/              ← Live client brief form (deployed via GitHub Pages)
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
2. **Duplicate the `_template` folder** inside `/clients/` and rename it: `client-name-YYYY`
3. **Paste the filled brief** into `BRIEF.md` inside their folder
4. **Drop their assets** (logo, photos, etc.) into `assets/`
5. **Build the site** using Cursor, v0, Bolt, or your preferred AI platform
6. **Save the final export / screenshots** into `exports/`
7. **Commit and push** — done ✅

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

This repo uses **GitHub Pages** to host the intake form as a live URL.

### First-time setup:
1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save**
5. Your intake form will be live at:
   `https://YOUR-USERNAME.github.io/client-sites/intake-form/`

> Takes ~2 minutes to go live after setup. Refresh if it doesn't appear immediately.

---

## 🧰 Tech Stack & Tools Used

| Purpose | Tool |
|---------|------|
| Version control | GitHub |
| Form hosting | GitHub Pages |
| AI site builder | Cursor / v0 / Bolt |
| Asset storage | This repo (`/assets`) |
| Brief intake | Custom HTML form |

---

## 📝 Notes

- Keep client folders **private** if this repo is public — consider using a private repo or keeping sensitive briefs local
- Always get the brief **before** you start building — it saves hours of revision
- The intake form auto-copies a text summary to clipboard when submitted, ready to paste into any AI build platform

---

*Built and maintained by Ryan · Updated 2025*
