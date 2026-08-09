# Nelvin Amonsot — Portfolio Website Spec

Status: **✅ FINALIZED — ready to build.** This document is the single source of truth we'll build from.

---

## 1. Project Overview

**Purpose:** A personal portfolio site to support Nelvin's applications for online/remote Virtual Assistant and Operations roles, showcasing his combined niche of:

1. **Operations Management** (remote team leadership, SOPs, process improvement, KPI tracking)
2. **Amazon SEO & Listing Optimization** (Seller Central, Helium 10, catalog management)
3. **Automation System Development** (AI-assisted app/workflow automation — n8n, Claude Code, Cursor, Supabase, Vercel)

**Primary CTA:** Resume download + direct contact (email).

**Audience:** Recruiters, hiring managers, and potential clients evaluating Nelvin for remote/VA/ops roles.

---

## 2. Design Direction

| Aspect | Decision |
|---|---|
| Visual style | **Modern tech/SaaS** — bold headlines, icons, subtle animation, clean cards/grids |
| Color palette | **Blue & teal** — tech-forward, calm, fits SEO/data/automation niche. Suggested: deep navy/blue (`#0B3D91`–`#1A56DB` range) as primary, teal/cyan (`#14B8A6`–`#22D3EE`) as accent, white/light-gray backgrounds, dark slate for text |
| Typography | Suggest a clean sans-serif pairing — e.g. **Inter** or **Manrope** for headings + body. (Open to alternatives.) |
| Tone/voice | **Confident & conversational** — first-person, capable but approachable. E.g. "Hi, I'm Nelvin — I help businesses run smoother and sell more on Amazon." |
| Site structure | **Multi-page** with shared nav/footer |
| Photo | Use the headshot pulled from his CV ([assets/nelvin-headshot.jpg](assets/nelvin-headshot.jpg)) — professional, smiling, plain background. Good for hero + about. |

---

## 3. Tech Stack & Hosting

- **Stack:** Simple static HTML/CSS/JS (no framework, no build step) — fast to load, easy to edit, easy to host free.
- **Hosting:** Free hosting, no custom domain yet (e.g. GitHub Pages or Netlify free subdomain). Domain can be added later.
- **Forms:** Since it's static, if we want an on-page contact form to actually deliver email, we'll need a third-party form service (e.g. Formspree free tier) — otherwise contact is just a `mailto:` link. *(Confirmed: going with resume download + direct contact, so a simple mailto/contact block is enough — no form service needed unless you want one added later.)*

---

## 4. Site Structure & Pages

### 4.1 Home
- Hero: name, photo, headline/tagline, short intro line, primary CTA buttons ("Download Resume", "Contact Me")
- Quick highlight strip: 3 niche pillars (Ops / Amazon SEO / Automation) as icon cards linking to Services
- Snapshot stats (e.g. "25,000+ ASINs managed", "Cum Laude, Chemical Engineering") — see Open Items for which stats to feature
- Featured case study teasers (2–3 cards) linking to Portfolio
- Closing CTA banner → Contact

### 4.2 About
- Short bio (draft below, section 6)
- Education: BS Chemical Engineering, Cum Laude — Mindanao State University–Iligan Institute of Technology (2020–2025)
- Professional competencies / characteristics (from CV's "Professional Competencies" section)
- Optional: personal touch (based in Cotabato, Philippines; remote work background)

### 4.3 Services ("What I Do")
Three main pillars, each with a sub-list of specifics pulled directly from the CV:

**1. Operations Management**
- Remote team leadership & supervision
- SOP creation, documentation & continuous process improvement
- Project & workflow management (Notion, Slack, Asana, ClickUp, Trello)
- CRM management (GoHighLevel, HubSpot, Monday.com, Brevo)
- KPI tracking, dashboards & performance reporting
- Executive/administrative support

**2. Amazon SEO & Listing Optimization**
- Amazon Seller Central listing & catalog management
- Keyword research, competitor analysis & listing audits (Helium 10)
- Title/bullet/description/backend search term optimization
- Flat file creation, bulk upload & troubleshooting
- Listing compliance, suppressed listing & error resolution
- Buy Box / Featured Offer troubleshooting
- A+ Content & Brand Story creation/management
- Business Reports & SQP analysis, conversion optimization

**3. Automation System Development**
- AI-assisted app & internal tool development (Claude Code, Cursor)
- n8n workflow automation, API/webhook integration
- GitHub, Supabase, Vercel, Hostinger (dev/deploy stack)
- Excel/data processing automation
- Custom dashboards & productivity systems
- Process mapping & workflow optimization

### 4.4 Portfolio / Case Studies
3 detailed case studies with **real metrics**, pulled from Nelvin's actual results at RSH Décor:

1. **Amazon Flat File Automation System**
   Built an end-to-end app (using Claude Code) that auto-generates Amazon Flat Files for new listings and product variations — replacing a fully manual process.
   **Result: work that used to take 1 month now takes 1 week** (~75% faster turnaround). Nelvin was the only team member to ship a tool that removes future recurring work rather than just completing tasks.

2. **Amazon Listing SEO Overhaul**
   Owned SEO and listing optimization (keyword research, titles, bullets, backend search terms, A+ Content) across a catalog of 25,000+ active ASINs for RSH Décor.
   **Result: raised the account's SEO/listing quality score from 2.8 to 8.7** by the time Nelvin left the role.

3. **Remote Team Leadership & SOP Systems**
   Directly managed and trained a cross-functional remote team of **11 people** across listing, flat file, image generation, and Shopify workflows — while documenting SOPs and maintaining dashboards/trackers for real-time visibility into team output.
   **Result:** consistently ranked among the company's top performers (see Recognition, section 4.7).

### 4.5 Skills / Tools
Grouped tool/skill grid (from CV's "Core Skills and Expertise" section):
- **Amazon/E-commerce:** Seller Central, Helium 10, Shopify, Flat Files, A+ Content
- **Automation/Dev:** n8n, Claude Code, Cursor, GitHub, Supabase, Vercel, Hostinger
- **Ops/PM/CRM:** Notion, Slack, Asana, ClickUp, Trello, GoHighLevel, HubSpot, Monday.com, Brevo
- **Data/Reporting:** Excel, QuickBooks, Business Reports/KPI analysis
- **AI Tools:** Claude, ChatGPT, Genspark, Google AI Studio

### 4.6 Contact
- Email: dadotamonsot@gmail.com (mailto link)
- Resume download button (polished PDF, exported from the provided CV)
- LinkedIn: [linkedin.com/in/nelvin-amonsot-4b652a217](https://www.linkedin.com/in/nelvin-amonsot-4b652a217/)
- Simple, friendly closing message

### 4.7 Recognition / Performance Highlights
A short section (on Home and/or About) built from RSH Décor's internal **Impact-Weighted Performance Report** — a system that scores employees on real leverage/impact rather than task count.

- **Consistently ranked #2 company-wide** in weekly impact-weighted scoring — behind only Anthony, the business owner — effectively making Nelvin the **top-ranked employee** on the team.
- Called out by name as a **"Needle-Mover"**: *"the only person on the team who built something that removes future work"* (the Flat File Creation App).
- Recognized as **Top Team Builder** for shipping a full automation app end-to-end.
- Near-perfect discipline score (99/100) combined with the highest-leverage work on the team.

> **Privacy note (confirmed approach):** the owner, Anthony, can be named since he's the employer and appears under his own name in the report. Other rank-and-file coworkers named in the same report will **not** be named or have their individual scores published — the site references only Nelvin's own ranking/results, described against "the company's internal performance system."

---

## 5. Testimonials / References

- No public quotes yet. Section will show reference **names/titles only** (no emails published):
  - Engr. Ronald P. Bual, DOE — Department Chairperson, Chemical Engineering & Technology
  - Engr. Catherine O. Acibar, M.Sc. — Chapter Adviser, MSU-IIT JPIChE
- Framed as "References available upon request."

---

## 6. Bio (revised — for About page)

> Hi, I'm Nelvin — an Operations Manager and Amazon SEO specialist who also builds the automation systems that make operations run themselves. From 2024 to 2026, I managed end-to-end Amazon and e-commerce operations for a catalog of 25,000+ active ASINs at RSH Décor — owning listing optimization and SEO, Seller Central troubleshooting, and day-to-day leadership of an 11-person remote team. In that time, I raised the account's SEO/listing quality score from 2.8 to 8.7, and built an automation app that turned a full month of manual Flat File work into about a week. In the company's internal performance system, I consistently ranked #2 company-wide — behind only the owner — making me the top-ranked employee on the team. I hold a Bachelor's degree in Chemical Engineering (Cum Laude) from Mindanao State University–Iligan Institute of Technology, which shaped how I approach problems: analytically, systematically, and always looking for the system behind the task. I'm now looking for a remote role where I can bring that same mix of operational discipline, e-commerce expertise, and automation thinking to a growing team.

*(This is a starting draft based on everything you've shared — happy to adjust tone, length, or details further.)*

---

## 7. Tagline — Selected

**"I manage the operations, optimize the listings, and automate everything in between."**

Chosen for the hero headline — it's conversational (matches the site's tone), and walks through all 3 niches in the order they connect (Ops → Amazon SEO → Automation). Other options considered, kept here in case we want a secondary line (e.g. a shorter sub-headline) elsewhere on the site:

- "Operations Manager. Amazon SEO Specialist. Automation Builder." — plain statement, good as a role/subtitle line under the name.
- "From Seller Central to SOPs to self-running systems." — punchier alternative.
- "Operations that run. Listings that rank. Systems that scale themselves." — three-beat rhythm.

---

## 8. Assets Available

| Asset | Location | Notes |
|---|---|---|
| Headshot photo | [assets/nelvin-headshot.jpg](assets/nelvin-headshot.jpg) | Pulled from CV file, white polo shirt, plain background |
| CV/Resume (source) | [assets/CV-AMONSOT-NELVIN.docx](assets/CV-AMONSOT-NELVIN.docx) | Will be converted into a polished, portfolio-ready PDF for the "Download Resume" button |
| Performance report screenshots | provided in chat (RSH Décor internal Impact-Weighted Performance Report) | Used as the basis for section 4.7 Recognition — not published directly, summarized/anonymized instead |

**Branding:** text-based name treatment only (no logo mark) — "Nelvin Amonsot" styled as a clean wordmark in the nav/footer.

---

## 9. Open Items — All Resolved ✅

- [x] Bio finalized with real metrics (section 6)
- [x] Tagline selected (section 7)
- [x] Real case study metrics added (section 4.4)
- [x] LinkedIn link added (section 4.6)
- [x] Resume will be converted to a polished PDF
- [x] Branding confirmed: text-based wordmark, no logo
- [x] Recognition section approach confirmed (section 4.7) — Anthony (owner) named, other coworkers anonymized

**Remaining non-blocking item:**
- [ ] **Domain name** — none yet, using free hosting; let me know if/when you want to buy a custom domain later

---

*Spec is finalized. Ready to start building the site.*
