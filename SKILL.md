---
name: ecovadis-advisor
description: Expert EcoVadis sustainability rating advisor and document drafter. Use this skill whenever a user asks about EcoVadis scores, wants to improve their EcoVadis rating, needs help drafting policies or documents for EcoVadis submission, wants to understand EcoVadis suggestions or corrective actions, asks what documents to upload, wants to go from one medal tier to another, or asks about EcoVadis themes (Environment, Labour & Human Rights, Ethics, Sustainable Procurement). Trigger this skill even for questions like "how do I increase my EcoVadis score", "what should I upload for EcoVadis", "can you write a supplier code of conduct for EcoVadis", "I got a score of 50 and EcoVadis gave me suggestions — help me act on them", or any question about ESG documentation for supply chain sustainability assessments. Always use this skill rather than answering from memory — EcoVadis methodology, medal thresholds, and document requirements evolve regularly.
---

# EcoVadis Advisor

Expert advisor for achieving high EcoVadis scores. This skill covers:
- **Gap-to-Action**: Parse EcoVadis suggestions/corrective actions and produce a prioritised improvement roadmap
- **Document Drafting**: Draft all core policy and evidence documents needed for submission
- **Score Strategy**: Explain how scoring works and which levers move scores fastest
- **Submission Readiness**: Checklist validation before upload

---

## Step 1: Understand the Organisation's Context

Before diving into documents or strategy, gather this information (ask for what's missing):

| Question | Why It Matters |
|---|---|
| Industry / sector | Determines which themes are weighted most heavily |
| Company size (headcount) | Affects which criteria are activated |
| Current overall score | Establishes baseline |
| Scores per theme (Env / L&HR / Ethics / Proc) | Pinpoints which pillar to focus on |
| EcoVadis improvement suggestions received | Exact gap list to work from |
| Existing certifications (ISO 14001, 45001, 27001, SA8000, etc.) | These are strong evidence multipliers |
| Already-existing policies / sustainability reports | Avoids reinventing documents that exist |
| Target score / medal | Sets the ambition level |

**If the user pastes their EcoVadis scorecard suggestions verbatim** → jump straight to Step 3 (Gap Interpreter).

---

## Step 2: Score Architecture — Explain How EcoVadis Scoring Works

When users don't understand how scores are calculated, explain this:

### The Four Themes
EcoVadis scores across four themes, each weighted by industry/size:

| Theme | Typical Weight Range | Key Focus |
|---|---|---|
| **Environment** | 25–35% | GHG/energy/water/waste policies, ISO 14001, sustainability report |
| **Labour & Human Rights** | 25–35% | H&S, working conditions, non-discrimination, training |
| **Ethics** | 15–25% | Anti-corruption, whistleblower, data privacy, CoC |
| **Sustainable Procurement** | 10–20% | Supplier CoC, supplier audits, supply chain risk |

### The Three Pillars (P-A-R)
Within each theme, EcoVadis evaluates three pillars:
- **Policies (P)** — ~25% of theme score: Formal written commitments, signed by senior management, with scope and objectives
- **Actions (A)** — ~50% of theme score: Concrete implementation evidence (training records, audits, KPI tracking, certifications)
- **Results (R)** — ~25% of theme score: Measurable outcomes, third-party verification, year-on-year improvement data

> **Key insight**: A company with great policies but no actions will plateau around 40–50. To push past 60, you need actions. To reach 70+, you need measurable results.

### Medal Tiers (2025 onwards — percentile-based)
| Medal | Approximate Percentile |
|---|---|
| Platinum | Top 1% |
| Gold | Top 5% |
| Silver | Top 25% |
| Bronze | Top 35% |
| No medal | Below threshold |

**Hard floor**: Any theme scoring below 30 disqualifies from all medals.

---

## Step 3: Gap Interpreter — From Suggestions to Actions

When a user shares EcoVadis improvement suggestions, follow this workflow:

### 3a. Parse the suggestions
Map each suggestion to:
- Which theme it belongs to (Env / L&HR / Ethics / Proc)
- Which pillar it targets (Policy / Action / Result)
- What document or evidence would satisfy it

### 3b. Score impact triage
Classify each suggestion:
- 🔴 **High impact** — directly unlocks points in a high-weight theme, currently at 0 (missing policy or major gap)
- 🟡 **Medium impact** — upgrades an existing partial response to full credit
- 🟢 **Quick win** — easy to implement or document, moderate points

### 3c. Output a prioritised action table

Format:
```
| # | EcoVadis Suggestion (paraphrased) | Theme | Pillar | Action Required | Impact | Document to Draft |
```

Then ask: *"Which of these would you like me to draft first?"*

---

## Step 4: Document Drafting

Read the reference file for the theme being drafted:
- **Environment** → `references/environment.md`
- **Labour & Human Rights** → `references/labour-hr.md`
- **Ethics** → `references/ethics.md`
- **Sustainable Procurement** → `references/procurement.md`
- **Cross-cutting / Foundations** → `references/foundations.md`

### Universal document quality rules (ALWAYS apply):
1. **Signed by senior leadership** — Every policy needs a CEO/MD/Board signatory line
2. **Dated and versioned** — Include version number and effective date
3. **Scope statement** — Clearly state which entities/geographies/operations are covered
4. **Specific commitments** — Replace vague language like "we aim to reduce" with "we commit to reducing GHG emissions by X% by year Y"
5. **Review cadence** — State when the policy will be reviewed (annually)
6. **References to international standards** — Cite UN Global Compact, ILO, GRI, ISO 26000 as applicable
7. **Company branding placeholder** — Include `[COMPANY NAME]`, `[LOGO]`, `[DATE]` placeholders
8. **Max 55 documents** — EcoVadis has an upload cap; prioritise comprehensive documents that cover multiple criteria

### Document types and their scoring value:
| Document Type | Scoring Value |
|---|---|
| Formal signed policy | Satisfies Policies pillar for the theme |
| ISO certificate (14001, 45001, 27001) | Strong Actions evidence — treat as gold |
| Annual sustainability / CSR report (GRI-aligned) | Covers Results + Actions across multiple themes |
| Training records / completion logs | Actions evidence for L&HR and Ethics |
| Audit reports (internal or third-party) | Actions + Results evidence |
| KPI dashboards / GHG inventory | Results evidence for Environment |
| Supplier assessment results / questionnaires | Actions for Procurement |
| Board resolution or governance document | Strengthens Policies pillar |

---

## Step 5: Score Improvement Roadmap

When helping a company go from one score band to the next, use this tiered guidance:

### Score 0–30 ("Insufficient") → Aim for 35–45
Focus: **Establish baseline policies**
- Draft the four core policies (Environmental, L&HR, Ethics/CoC, Supplier CoC)
- Answer questionnaire questions with at least a policy reference for each
- Upload any existing certifications

### Score 40–50 ("Beginner") → Aim for 55–65 *(most common request)*
Focus: **Add Actions evidence**
- Core policies exist — now show they're implemented
- Priority documents: training completion records, internal audit reports, H&S incident data, GHG/energy consumption data, supplier questionnaire template
- Introduce a sustainability report (even a short PDF)
- Map existing ISO certifications to EcoVadis questions explicitly

### Score 55–65 ("Intermediate") → Aim for 70–75
Focus: **Results and third-party validation**
- GHG inventory with Scope 1 & 2 (begin Scope 3)
- Science-Based Targets (SBTi) submission
- External audit or third-party verification of claims
- Supplier audit programme with documented outcomes
- Year-over-year KPI improvement data

### Score 70+ ("Advanced") → Aim for Silver/Gold
Focus: **Depth, consistency, and comprehensive supply chain**
- GRI-aligned sustainability report published externally
- Scope 3 emissions data
- Supplier development programme (not just assessment)
- Participation in UN Global Compact or equivalent
- Board-level governance of sustainability topics documented

---

## Step 6: Submission Readiness Check

Before the user submits, run through this checklist:

### Policies Checklist
- [ ] Environmental Policy (signed, dated, scoped, with specific targets)
- [ ] Labour & Human Rights Policy (ILO references, working conditions, non-discrimination)
- [ ] Health & Safety Policy
- [ ] Equal Opportunity / DEI Policy
- [ ] Code of Conduct / Business Ethics Policy (CEO-endorsed)
- [ ] Anti-Corruption & Anti-Bribery Policy
- [ ] Whistleblower / Speak-Up Policy
- [ ] Data Protection / Privacy Policy
- [ ] Supplier Code of Conduct

### Actions Evidence Checklist
- [ ] ISO certificates (14001, 45001, 27001 — whichever held)
- [ ] Training records or e-learning completion logs
- [ ] Internal audit reports
- [ ] H&S incident and near-miss tracking records
- [ ] Supplier questionnaire or self-assessment template used
- [ ] Evidence of supplier risk assessment

### Results Evidence Checklist
- [ ] GHG/energy/water/waste KPI data (multi-year preferred)
- [ ] Sustainability or CSR report
- [ ] External verification or assurance statement
- [ ] Employee survey or engagement data
- [ ] Supplier audit outcome summary

### Common Disqualifiers — Check These
- [ ] Any theme scoring below 30? (medal disqualification)
- [ ] 360° Watch negative findings unaddressed?
- [ ] Document upload count at/near 55 limit? (prioritise comprehensive docs)
- [ ] All uploaded documents in English or translated?

---

## Quick Reference: Drafting Commands

The user can ask for any of these documents by name and Claude will draft them:

**Environment Theme**
- Environmental Policy
- GHG / Carbon Management Policy
- Energy Management Policy
- Waste & Circular Economy Policy
- Biodiversity Policy
- GHG Inventory template
- Sustainability / ESG Report outline

**Labour & Human Rights Theme**
- Labour & Human Rights Policy
- Health & Safety Policy
- Equal Opportunity & DEI Policy
- Modern Slavery & Anti-Trafficking Statement
- Employee Handbook sections (H&S, whistleblowing, grievance)
- Training log template

**Ethics Theme**
- Code of Conduct
- Anti-Corruption & Anti-Bribery Policy
- Whistleblower Policy
- Conflict of Interest Policy
- Data Protection / Privacy Policy
- Gift & Hospitality Policy

**Sustainable Procurement Theme**
- Supplier Code of Conduct
- Supplier Sustainability Questionnaire (SSQ) template
- Supplier Risk Assessment Matrix
- Responsible Sourcing Policy
- Supplier Due Diligence procedure

**Cross-cutting**
- Sustainability Report executive summary
- ESG KPI dashboard template
- Board resolution on sustainability governance
- UN Global Compact Communication on Progress (COP) outline

---

## Tone and Format for Drafted Documents

All drafted policy documents must:
- Use professional, formal language appropriate for regulatory/audit review
- Be structured: Purpose → Scope → Commitments → Responsibilities → Review
- Include a signature block: `Approved by: [Name], [Title] | Date: [DD Month YYYY] | Version: X.X`
- Be between 400–1200 words (enough detail to be credible, not so long analysts won't read it)
- Reference applicable international standards (ILO, GRI, ISO 26000, UN Global Compact, UNGP)
- Avoid generic filler — every commitment should be specific enough to be auditable

When drafting, always ask if the company has any **existing certifications** that should be referenced in the document (e.g., "In support of our ISO 14001 certification...").

---

## Reference Files

Load these when drafting documents for the relevant theme:

- `references/environment.md` — Environment theme criteria, document templates, KPI examples
- `references/labour-hr.md` — L&HR theme criteria, H&S policy templates, training log formats
- `references/ethics.md` — Ethics theme criteria, CoC and anti-corruption templates
- `references/procurement.md` — Sustainable Procurement criteria, SSQ template, supplier CoC
- `references/foundations.md` — Cross-cutting docs: sustainability report structure, GRI alignment, board governance
