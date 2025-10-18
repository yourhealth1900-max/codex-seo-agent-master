# AFFILIATE MEDICAL CONTENT — CONSTITUTION PROTOCOL (v3.3.2 • FINAL, EN‑only)
Last‑Updated: 2025-10-18 06:46

> Canonical, mandatory rulebook. Superset of v3.3 + v3.3.1. English‑only. All rules are **Fail‑Stop**. If any item is missing → **BLOCK PUBLISH**.

---

## 0) Scope, Policy & Legal
- Applies to all niches (Anti‑Aging, Men’s/Women’s Health, Muscle & Fitness, Skin Care, Intimate Wellness, German Offers).
- Targets **Google SEO + AI/SGE** safely (YMYL/affiliate compliant).
- **Legal**: DSHEA (US) + EFSA‑compatible phrasing (EU). **FDA/FTC + Affiliate disclosures** near the first CTA.
- **No invented products/links**, **Base affiliate link only per product**, **no fake PMIDs**.

## 1) Required Inputs (before writing)
- **FOCUS_KEYWORD** (exact, 1–3 words) + **3–6 LSI**.
- **Taxonomy**: Primary + Secondary + **15 tags** (standardised list).
- **Internal links (approved JSON)**: ingredients / dosage / side‑effects / user‑reviews / where‑to‑buy.
- **Products**: primary + contextual secondaries with **base affiliate links only (no parameters)** + **HTML image codes**.
- **Author + Medical Reviewer**: names, credentials, profile URLs (headshots optional).
> Missing any input ⇒ **STOP** and request assets.

## 2) Language, Tone, Hook
- **American English only**.
- **Hook**: problem → expected outcome → one caution (2–3 sentences), non‑promotional.
- Editorial/medical voice; soft‑sell only; no hype/emoji/year in titles.

## 3) AEO / AI‑Search
- **Answer‑First box** under H1: **45–60 words**.
- **Every H2** begins with a **45–60‑word direct answer**.
- **FAQ 8–10**; natural‑language, covers purchase/usage/comparisons.
- **Snippet formatting**: paragraphs **<50 words**, scannable lists/tables, quantified claims with citations.

## 4) Words, Density & Outline
- **Word count**: new posts **5,000–6,000** (min 4,000 for updates only).
- **Density**: 0.8–1.5%; ≤2 exact matches/paragraph; **3–5 LSI** naturally.
- Place FK in H1, one early H2/H3, **first 100 words**, and at least **one image ALT**.
- **Outline (minimum)**: What/Who → Mechanism → Evidence → Usage (timing/dosage/stacks) → **30‑day plan** → Safety & interactions → Comparisons (responsive table; sticky first column on mobile) → **TL;DR 8–12 bullets** → **CTAs** (Top/Mid/End).

## 5) Mandatory SEO Metadata (RankMath)
- **Title ≤60**: starts with FK + **number + power/authority + benefit**; **no year/emoji**.
- **Meta 150–160**: starts with FK; hook + benefit + soft CTA + optional social proof.
- **Slug**: short, lowercase, hyphenated, includes FK.
- **RankMath must be Green** pre‑publish.

**Templates**
- **SEO Title**: `[FOCUS_KEYWORD]: [NUMBER] [POWER/Authority] [BENEFIT]`
- **Meta**: `Focus‑KW + hook + benefit + soft CTA (+ social proof)` (150–160)
- **Slug**: `focus-keyword-[number]-[benefit]`

## 6) Links Policy (zero‑tolerance)
- **Real store links only** (primary + contextual secondary). No placeholders in production.
- Exactly **one base affiliate link per product** (no parameters) with `rel="sponsored noopener"`.
- **Internal links ≥52** for new cornerstone posts (≥8 for updates). **External medical 3–6** (NIH/NCCIH/PubMed/Examine).

## 7) Images & Media (Spec + Prompts + UX)
- **Featured**: **2560×1396 WebP**, realistic editorial photo; **Alt/Title/Description/Caption** mandatory; `loading="eager"`; width/height set (LCP).
- **Infographic**: **2560×1396 WebP**, 4–6 blocks (what/plan/dosing/quick wins/cautions); full metadata; `loading="lazy"`.
- **Inline images**: ~**1 per 300–500 words**; logical breaks (prefer end of paragraphs); `loading="lazy"` + width/height.
- **Video**: `preload="metadata"` + poster; width/height declared.

**Prompts (copy/edit)**
- Featured: “A real, high‑resolution editorial photograph of a [SUBJECT] for ‘[FOCUS‑KW]’, clean daylight, neutral background, medical context; no text/logo; 2560×1396 WebP.”
- Infographic: “Clean wide infographic 2560×1396 for ‘[FOCUS‑KW]’: 4–6 blocks (what it is, 30‑day plan, dosage timing, quick wins, cautions), legible fonts, brand‑neutral palette; WebP.”

## 8) JSON‑LD (One @graph, store‑safe)
- Connect: **Organization**, **Author**, **MedicalReviewer**, **BreadcrumbList**, **ImageObject**, **Article**, **FAQPage**, **Product + embedded Review**.
- **No Offers/AggregateOffer** on articles. Only on true store/price pages.
- If a video is embedded, include **`VideoObject`** in the same graph.
- Validate **0 Errors** in Rich Results.

## 9) E‑E‑A‑T / YMYL
- **Author byline** + **Medical Reviewer** (credentials + profile links).
- Disclaimers; cautious language; cite all health claims; ban fake PMIDs.
- **Affiliate/FDA/FTC disclosures** near first CTA.

## 10) Mobile‑First UX
- Responsive tables; **sticky first column** if needed.
- Tap targets **≥44px**; lazy images; prevent CLS; WebP everywhere.

## 11) CTAs (indirect)
- Placements: **Top / Mid / End** only (one CTA per placement).
- Copy: trust‑first, educational; **base link only** with `rel="sponsored noopener"`.

## 12) RankMath Pass‑Map (error → fix)
- FK in meta/URL/start/content/sub‑headings/ALT; density 0.8–1.5%; ≥5,000 words; internal links present; rich media present.

## 13) Pre/Post‑Publish Gates (Fail‑Stop)
- **G1 Words/Density**: 5–6K; 0.8–1.5%; ≤2/paragraph; LSI present.
- **G2 AEO**: Answer‑First 45–60w; H2 answers 45–60w; FAQ 8–10; snippet formatting OK.
- **G3 Links**: Real links; **1 base affiliate/product** + rel; ≥52 internal (new)/≥8 (update); 3–6 external medical.
- **G4 RankMath & Metadata**: Title ≤60; Meta 150–160; Slug OK; **RankMath Green**.
- **G5 JSON‑LD**: single @graph; Product+Review store‑safe; **VideoObject if video**; 0 Errors.
- **G6 E‑E‑A‑T**: Author + Med Reviewer + DSHEA/EFSA & FDA/FTC disclosures + citations; no fake PMIDs.
- **G7 Media/UX**: Featured spec + infographic metadata + inline cadence + CLS/tap targets.
- **G8 CTAs**: Top/Mid/End; indirect; base link only.
- **G9 Taxonomy/Tags**: Primary + Secondary + **15 tags**.

## 14) Operations Annex (90‑Day Plan & KPIs)
- Weeks 1–3: Trust reviews / Safety / Dosage / Interactions / Where‑to‑Buy.
- Weeks 4–7: Long‑tail problem solvers + Comparisons; 2–4 authority links.
- Weeks 8–12: Authority pillars; internal links complete; US/EU tone/claims as needed.

**KPIs:** AI Search (citations), SEO (Top‑5 transactional terms), Revenue (EPC/CR/AOV), Content Ops (QA pass‑rate & internal links added).

## 15) GSC Enhancements & Experience — Playbook (EN‑only)
Covers HTTPS, Product Snippets (Article vs Store), Merchant Listings, Breadcrumbs, FAQ, Review, VideoObject; includes ready‑to‑paste JSON‑LD for both page types and a warning‑to‑fix matrix.

## 16) Appendix — HTML/Schema Snippets & Prompts
Ready snippets: Article skeleton, comparison table, CTA buttons, FAQ boilerplate, JSON‑LD blocks, Featured/Infographic prompts.
