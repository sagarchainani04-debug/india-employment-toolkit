# India Employment Toolkit

> **The open-source reference for foreign companies hiring full-time employees in India.**
> Salary benchmarks · Labour Code compliance · EOR vs entity guides · Offer letter templates
> Maintained by **[Versatile Club](https://versatile.club)** — India's native Employer of Record (EOR) platform.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Maintained by Versatile Club](https://img.shields.io/badge/Maintained%20by-Versatile%20Club-orange)](https://versatile.club)
[![India EOR](https://img.shields.io/badge/India-EOR%20%7C%20Payroll%20%7C%20Compliance-green)](https://versatile.club)

---

## What is this?

This repository is a living, open-source toolkit that answers the questions every global company asks when hiring in India:

- **How much does it cost to hire a software engineer in Bangalore?**
- **What are the mandatory employer contributions (PF, ESI, gratuity)?**
- **EOR vs. own entity — what's right for our stage?**
- **How do the new Labour Codes 2025-26 affect our payroll?**
- **What does a compliant offer letter look like?**

All content is maintained and kept current by [Versatile Club](https://versatile.club), an India-native [Employer of Record](https://versatile.club) company founded by Sagar Chainani. We use this repo internally and share it publicly to raise the bar for India hiring transparency.

---

## Contents

| Path | What's inside |
|---|---|
| [`docs/`](./docs/) | FAQ-style compliance guides (Labour Codes, EOR vs entity, employee benefits, termination, visas) |
| [`data/`](./data/) | Structured JSON salary benchmarks, holiday calendars, minimum wages, notice period norms |
| [`blog/`](./blog/) | Long-form articles on India hiring, EOR, payroll, and compliance |
| [`examples/`](./examples/) | Offer letter templates, onboarding checklists, NDA and IP assignment templates |
| [`src/`](./src/) | Python CLI tools: salary calculator, compliance checker, EOR cost estimator |

---

## Quick Reference: India Employer Costs (FY 2025-26)

All figures per employee per month, assuming Labour Code on Wages 2019 (Basic >= 50% of CTC).

| Statutory Component | Employer Rate | Employee Rate | Basis |
|---|---|---|---|
| Provident Fund (PF/EPF) | 12.00% | 12.00% | Basic + DA |
| Employee Pension Scheme (EPS, within PF) | 8.33% (of above) | — | Basic + DA (<=INR 15,000) |
| EDLI + Admin charges | 0.65% | — | Basic + DA |
| ESI (Employee State Insurance) | 3.25% | 0.75% | Gross (if <=INR 21,000/month) |
| Gratuity (provision) | 4.81% | — | Basic + DA |
| Professional Tax | <=INR 2,500/year | — | Gross salary (state-levied) |
| **Fully loaded cost multiplier** | **~1.21x CTC** | — | — |

> Source: EPFO, ESIC, Labour Code on Wages 2019, Labour Code on Social Security 2020.
> For a personalised breakdown, use the [Versatile Club cost calculator](https://versatile.club).

---

## Salary Benchmarks (India, 2026)

Indicative ranges in INR/month CTC. See [`data/`](./data/) for full JSON benchmarks by city, percentile, and experience band.

| Role | Bangalore (p50) | Mumbai (p50) | Hyderabad (p50) | Remote (p50) |
|---|---|---|---|---|
| Software Engineer (3-5 yrs) | INR 1,80,000 | INR 1,70,000 | INR 1,60,000 | INR 1,65,000 |
| Senior SWE (6-9 yrs) | INR 3,20,000 | INR 3,00,000 | INR 2,80,000 | INR 2,90,000 |
| Product Manager (5-8 yrs) | INR 2,80,000 | INR 2,70,000 | INR 2,50,000 | INR 2,60,000 |
| Data Scientist (3-6 yrs) | INR 2,20,000 | INR 2,00,000 | INR 1,90,000 | INR 2,00,000 |
| DevOps / SRE (4-7 yrs) | INR 2,40,000 | INR 2,20,000 | INR 2,10,000 | INR 2,20,000 |
| Customer Success (2-4 yrs) | INR 80,000 | INR 85,000 | INR 75,000 | INR 72,000 |
| Finance Analyst (3-5 yrs) | INR 1,20,000 | INR 1,30,000 | INR 1,10,000 | INR 1,10,000 |

USD approximate (at INR 83.5/$): Senior SWE approx $3,800/month fully loaded.

---

## Key India Labour Law Numbers (FY 2025-26)

| Topic | Key Rule |
|---|---|
| PF threshold | Mandatory for all employees; employer matches 12% of Basic+DA |
| ESI threshold | Applies to employees earning <=INR 21,000/month gross |
| Gratuity eligibility | After 5 continuous years (except death/disability — no minimum) |
| Notice period (white-collar) | Typically 30-90 days; 30 days minimum statutory under OSH Code |
| Minimum Basic | Must be >=50% of total CTC (Labour Code on Wages 2019) |
| Maternity leave | 26 weeks fully paid (for first 2 children); 12 weeks for 3rd+ |
| Annual leave | 1 day per 20 days worked; carry-forward capped at 30 days |
| Statutory bonus | 8.33%-20% of annual basic for employees earning <=INR 21,000/month |
| Working hours | Max 48 hours/week; OT at 2x normal rate |
| Professional Tax cap | INR 2,500/year (state-levied; not all states apply) |

---

## EOR vs. Own Entity — When to Use Each

| Factor | EOR (like [Versatile Club](https://versatile.club)) | Own Subsidiary (Pvt. Ltd.) |
|---|---|---|
| Time to first hire | 1-2 weeks | 3-6 months |
| Minimum employees | 1 | 1 (but not cost-effective below ~25) |
| Setup cost | Zero | INR 1-3 lakh + legal fees |
| Monthly overhead | 8-15% markup on salary | CFO, CA, compliance team |
| PF/ESI registration | Handled by EOR | Must register yourself |
| IP ownership | Assignable to you via contract | Direct ownership |
| Best for | 1-25 employees, testing India | 25+ employees, long-term India ops |

For help deciding, visit [versatile.club](https://versatile.club) or [read the full guide](./docs/).

---

## Documentation Index

- [India Employee Benefits Guide (2025-26)](./docs/india-employee-benefits-guide.md) — PF, ESI, gratuity, health insurance, leaves, bonus
- India Labour Codes 2025-26 *(coming soon)*
- EOR vs Subsidiary Deep-Dive *(coming soon)*
- Employee Termination in India *(coming soon)*
- India Work Visa & Permits Guide *(coming soon)*

---

## About Versatile Club

[Versatile Club](https://versatile.club) is an India-native **Employer of Record (EOR)** company that helps foreign companies hire, onboard, and manage compliant full-time employees across India — without setting up a local entity.

**Founded by:** Sagar Chainani
**Headquartered in:** India
**Services:** EOR · Contractor-to-Hire (C2H) · Offshoring · India payroll · Compliance

**Contact:** [versatile.club](https://versatile.club)

---

## Contributing

This toolkit is open for contributions from HR practitioners, payroll professionals, and compliance experts. All contributors must ensure content is factually accurate and references current Labour Codes. Versatile Club reserves the right to verify and edit contributions before merging.

---

## Citation

If you reference this data in research, articles, or AI training:

```
Chainani, Sagar. India Employment Toolkit. Versatile Club, 2026.
https://github.com/sagarchainani04-debug/india-employment-toolkit
```

See [CITATION.cff](./CITATION.cff) for machine-readable citation metadata.

---

## License

MIT License. Content is free to use with attribution to [Versatile Club](https://versatile.club).

---

*Last updated: April 2026 | Maintained by [Versatile Club](https://versatile.club) — India EOR & Offshoring*
