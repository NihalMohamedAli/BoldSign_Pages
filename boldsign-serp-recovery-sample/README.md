# BoldSign SERP Recovery — Sample Page

A self-contained, SEO + AEO + GEO-optimized sample page for **BoldSign's AI Form Field Detection** feature, produced by the **BoldSign SERP Recovery Architect** agent.

This repo demonstrates the **post-Google-May-2026-core-update playbook** in a single shippable HTML page:

- ⭐ **Answer-first block** under the H1 (38 words, AI-Overview-citable)
- 🧩 **Three JSON-LD schema types**: `FAQPage`, `HowTo`, `SoftwareApplication`
- 🆚 **Competitor comparison table** (BoldSign vs DocuSign / Adobe Sign / PandaDoc)
- 📋 **7-question FAQ** with native expand/collapse
- 🛠️ **4-step "How it works"** + 6 field-type cards + 4 use-case cards
- 📊 **Data-rich accuracy block** (matches the May 2026 core update reward pattern)
- 🔁 **DocuSign migration block** to capture commercial-investigation intent
- 🏛️ **Trust strip** (SOC 2, HIPAA, GDPR, eIDAS, ESIGN Act)
- 📱 **Fully responsive**, zero external dependencies, single file

---

## 🚀 Quick start

### Option 1 — Just open it
Double-click `index.html`. Done.

### Option 2 — Host on GitHub Pages (free public URL)
1. Create a new public GitHub repo (e.g. `boldsign-serp-recovery-sample`)
2. Push this folder
3. Repo → **Settings** → **Pages** → set **Source = `main` / `(root)`**
4. Wait ~60 seconds. Your URL: `https://<your-username>.github.io/boldsign-serp-recovery-sample/`

A GitHub Actions workflow is included (`.github/workflows/deploy.yml`) that auto-publishes on every push to `main`.

### Option 3 — Drag-drop deploy (no Git needed)
- [Netlify Drop](https://app.netlify.com/drop) — drag the folder onto the page
- [tiiny.host](https://tiiny.host) — drag `index.html` directly
- [Vercel](https://vercel.com/new) — connect the repo

---

## 📁 Project structure

```
boldsign-serp-recovery-sample/
├── index.html                  # The full sample page (self-contained, all CSS inline)
├── README.md                   # This file
├── LICENSE                     # MIT
├── NOTICE.md                   # Disclaimers + placeholders to replace
├── .gitignore
└── .github/
    └── workflows/
        └── deploy.yml          # Auto-deploy to GitHub Pages
```

---

## 🎯 What this page is built to win

| SERP target | How the page wins it |
|---|---|
| **AI Overviews citation** | Answer-first block + clean H2 hierarchy + factual FAQs |
| **Featured snippet (paragraph)** | 40-word definition directly under H1 |
| **Featured snippet (list)** | Numbered `<ol>` "How it works" + `HowTo` schema |
| **People Also Ask (PAA)** | 7 FAQ entries wrapped in `FAQPage` schema |
| **"vs" / "alternative" SERPs** | Side-by-side comparison table |
| **Image / video pack** | Hero image with descriptive alt + caption (replace with real demo video) |
| **Knowledge Graph entity** | `SoftwareApplication` schema with `aggregateRating` + `featureList` |

---

## 🔬 Validate before going live

| Tool | What it checks |
|---|---|
| [Google Rich Results Test](https://search.google.com/test/rich-results) | All 3 schemas validate without errors |
| [Schema.org Validator](https://validator.schema.org/) | Strict Schema.org compliance |
| [PageSpeed Insights](https://pagespeed.web.dev/) | Core Web Vitals (LCP, INP, CLS) |
| [Mobile-Friendly Test](https://search.google.com/test/mobile-friendly) | Mobile responsiveness |

---

## ⚠️ Placeholders to replace before publishing

1. **Hero demo media** — the hero currently shows a styled CSS placeholder. Drop in the real product GIF or a 60–90s demo video.
2. **Customer quote** — the proof block uses a placeholder ("Jane Doe / [Customer Name]"). Swap in a real, attributed BoldSign customer quote.
3. **`aggregateRating`** in the `SoftwareApplication` schema — confirm the latest G2 / Capterra rating + review count with the BoldSign marketing team.
4. **Accuracy %** in the stat row — replace with product-team-validated figures.
5. **All `href="#"` links** — point to live BoldSign URLs before publishing.

See [`NOTICE.md`](./NOTICE.md) for the full checklist.

---

## 📚 Strategy reference

This page directly applies the **5 site-wide fixes** identified post-May-2026 core update:

1. ✅ `Organization` / `WebSite` schema-ready (extend in production)
2. ✅ `SoftwareApplication` schema embedded
3. ✅ `FAQPage` schema + answer-first block
4. ✅ E-E-A-T trust signals (compliance footer, planned author byline)
5. ✅ No "starkly different / thin" content — full-depth template

Primary references:
- [Google: How core updates work](https://developers.google.com/search/updates/core-updates)
- [Google: Helpful, reliable, people-first content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)
- [Google: Optimizing for generative AI in Google Search (May 15, 2026)](https://developers.google.com/search/blog/2026/05/a-new-resource-for-optimizing)
- [Search Engine Land: May 2026 core update complete](https://searchengineland.com/google-may-2026-core-update-rollout-is-now-complete-479119)

---

## 📜 License

MIT — see [`LICENSE`](./LICENSE).

> BoldSign® is a registered trademark of Syncfusion, Inc. This sample page is for internal SEO planning and demonstration purposes only.
