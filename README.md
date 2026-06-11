# EcoVadis Advisor — Claude Skill

> An expert Claude skill for improving EcoVadis sustainability ratings — from gap analysis to audit-ready document drafting.

---

## What This Skill Does

The **EcoVadis Advisor** is a [Claude Skill](https://docs.claude.ai) that turns Claude into a specialist EcoVadis advisor. It helps sustainability and procurement teams:

- **Interpret EcoVadis improvement suggestions** and convert them into a prioritised action roadmap
- **Draft all core policy and evidence documents** required for submission (Environmental Policy, Code of Conduct, Supplier CoC, Whistleblower Policy, and more)
- **Understand how scoring works** — the P-A-R model, theme weights, and medal thresholds
- **Plan a score improvement strategy** based on your current band
- **Run a pre-submission readiness check** before uploading to the EcoVadis platform

---

## Capabilities at a Glance

| Capability | Description |
|---|---|
| **Gap Interpreter** | Paste in EcoVadis suggestions → get a prioritised action table mapped to theme, pillar, and document |
| **Document Drafting** | Generate audit-ready policy documents across all four EcoVadis themes |
| **Score Strategy** | Band-by-band guidance on which levers move scores fastest |
| **Submission Readiness** | Pre-upload checklist covering Policies, Actions, and Results pillars |

---

## EcoVadis Themes Covered

| Theme | Weight Range | Key Documents Covered |
|---|---|---|
| **Environment** | 25–35% | Environmental Policy, GHG Inventory, Energy Policy, Sustainability Report |
| **Labour & Human Rights** | 25–35% | L&HR Policy, Health & Safety Policy, Equal Opportunity Policy, Modern Slavery Statement |
| **Ethics** | 15–25% | Code of Conduct, Anti-Corruption Policy, Whistleblower Policy, Data Privacy Policy |
| **Sustainable Procurement** | 10–20% | Supplier Code of Conduct, Supplier Sustainability Questionnaire, Risk Assessment Matrix |

---

## Repo Structure

```
ecovadis-advisor/
├── SKILL.md                        # Main skill instructions for Claude
├── README.md                       # This file
└── references/
    ├── environment.md              # Environment theme: criteria, templates, KPIs
    ├── labour-hr.md                # Labour & HR theme: criteria, templates, KPIs
    ├── ethics.md                   # Ethics theme: criteria, templates, KPIs
    ├── procurement.md              # Sustainable Procurement theme: criteria, templates, KPIs
    └── foundations.md              # Cross-cutting: Sustainability Report, Board governance, UNGC COP
```

---

## How to Use

### Option 1 — Use as a Claude Project Skill

1. Create a new [Claude Project](https://claude.ai/projects)
2. Upload `SKILL.md` and the entire `references/` folder as project knowledge files
3. Start a conversation and trigger with `/ecovadis-advisor` or just ask EcoVadis-related questions

### Option 2 — Use via System Prompt

Paste the contents of `SKILL.md` into your Claude system prompt, and upload the reference files as context documents.

---

## Example Prompts

```
/ecovadis-advisor I got a score of 48 and EcoVadis gave me these suggestions — help me prioritise them:
[paste suggestions]
```

```
/ecovadis-advisor Draft an Environmental Policy for a SaaS company with ~500 employees. We have ISO 27001 but not ISO 14001.
```

```
/ecovadis-advisor We're at 55 and want to reach Silver. What should we focus on?
```

```
/ecovadis-advisor Run a submission readiness check — here's what we have so far: [list documents]
```

---

## Score Band Guidance (Quick Reference)

| Current Score | Target | Primary Focus |
|---|---|---|
| 0–30 | 35–45 | Establish the four core policies |
| 40–50 | 55–65 | Add Actions evidence (training logs, audits, GHG data) |
| 55–65 | 70–75 | Results + third-party validation |
| 70+ | Silver / Gold | Depth, Scope 3, GRI-aligned report, supply chain programme |

> **Hard rule**: Any theme scoring below 30 disqualifies from all medals — check this first.

---

## Documents This Skill Can Draft

**Environment**
- Environmental Policy
- GHG / Carbon Management Policy
- Energy Management Policy
- Waste & Circular Economy Policy
- GHG Inventory template
- Sustainability / ESG Report outline

**Labour & Human Rights**
- Labour & Human Rights Policy
- Health & Safety Policy
- Equal Opportunity & DEI Policy
- Modern Slavery & Anti-Trafficking Statement
- Training log template

**Ethics**
- Code of Conduct
- Anti-Corruption & Anti-Bribery Policy
- Whistleblower / Speak-Up Policy
- Conflict of Interest Policy
- Data Protection / Privacy Policy
- Gift & Hospitality Policy

**Sustainable Procurement**
- Supplier Code of Conduct
- Supplier Sustainability Questionnaire (SSQ) template
- Supplier Risk Assessment Matrix
- Responsible Sourcing Policy
- Supplier Due Diligence procedure

**Cross-Cutting**
- Sustainability / CSR Report structure
- ESG KPI Dashboard template
- Board Resolution on ESG governance
- UN Global Compact COP outline

---

## Author

**Mark** — Information Security & Compliance Specialist  
[GitHub: Mseq-z](https://github.com/Mseq-z)

---

## License

MIT — free to use, adapt, and build on. Attribution appreciated.
