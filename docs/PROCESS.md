# My Website Build Process

A repeatable workflow for taking a client from brief to live site.

---

## Phase 1 — Discovery (Before You Touch Any Code)

1. **Send the intake form** → `https://YOUR-USERNAME.github.io/client-sites/intake-form/`
2. Wait for client to complete it
3. Review the brief — look for red flags, missing info, or scope creep risks
4. Confirm scope, timeline, and payment terms before proceeding

**Red flags to watch for:**
- Vague goals ("just make it look nice")
- No content ready ("we'll sort that later")
- Unrealistic timelines ("can you do it by tomorrow?")
- No budget clarity

---

## Phase 2 — Setup

1. Duplicate `clients/_template/` → rename to `client-name-YYYY`
2. Paste brief into `BRIEF.md`
3. Collect all assets into `assets/`
4. Create a new branch: `git checkout -b client-name-YYYY`

---

## Phase 3 — Build

1. Copy the brief summary to clipboard (auto-done by intake form)
2. Open your AI build platform (Cursor / v0 / Bolt)
3. Paste the full brief as your first prompt
4. Let AI generate the initial scaffold
5. Iterate with targeted follow-up prompts (see prompt tips below)

### Prompt Tips for AI Builders

**Good first prompt structure:**
```
Build a website for [BUSINESS NAME].

Business: [what they do]
Audience: [who they serve]
Goal: [primary CTA]
Pages needed: [list]
Design vibe: [adjectives from brief]
Colours: [hex or description]
Tone: [voice style]
Must-haves: [non-negotiables]
Avoid: [deal-breakers]
```

**Follow-up prompts:**
- "Make the hero section bolder with a full-bleed background image"
- "Add a sticky nav that changes colour on scroll"
- "The CTA button needs more contrast — try [colour]"
- "The mobile layout is breaking on the services section, fix it"

---

## Phase 4 — Review & Revisions

1. Deploy a preview link to share with the client
2. Collect feedback in writing (email or Notion — not voice notes)
3. Log all changes in the `Revision Log` section of `BRIEF.md`
4. Cap revisions at [X] rounds — specify this upfront

---

## Phase 5 — Delivery

1. Final checks: mobile, tablet, desktop
2. Test all forms, links, and integrations
3. Go live on client's domain
4. Screenshot final site → save to `exports/`
5. Hand over login credentials / CMS access
6. Send invoice

---

## Tools I Use

| Job | Tool |
|-----|------|
| AI Build | Cursor / v0 / Bolt |
| Hosting (client) | Vercel / Netlify / Webflow |
| Asset management | This repo |
| Communication | Email / Notion |
| Payment | [Your tool] |

---

## Pricing Reference *(edit this)*

| Package | Includes | Price |
|---------|----------|-------|
| Starter | 3-page site, contact form | $XXX |
| Standard | 6-page site, CMS, integrations | $XXX |
| Premium | Custom design, e-commerce, animations | $XXX |
| Retainer | Monthly updates & maintenance | $XXX/mo |
