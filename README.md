<a href="https://akshita-r-portfolio.netlify.app"><img src="assets/banner.svg" alt="Akshita R: Data Analyst moving into Associate Product Manager" width="100%" /></a>

<p align="center">
  <a href="https://akshita-r-portfolio.netlify.app"><img src="https://img.shields.io/badge/Portfolio-visit-2350dc?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfolio" /></a>
  <a href="https://akshita-r-portfolio.netlify.app/?mode=recruiter"><img src="https://img.shields.io/badge/Recruiter_view-1_page-111111?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Recruiter view" /></a>
  <a href="https://akshita-r-portfolio.netlify.app/assets/resume.pdf"><img src="https://img.shields.io/badge/Résumé-PDF-555555?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Résumé PDF" /></a>
  <a href="https://linkedin.com/in/akshita-r"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:akshitar2003@gmail.com"><img src="https://img.shields.io/badge/Email-say_hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

I sit where **data, users and product decisions** meet. 1.5+ years in enterprise SaaS analytics, backend engineering in a fintech product team before that, and one product I took from **a user survey to a live launch**. I'm now moving into **product management**.

### Impact

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/impact-dark.svg" />
  <img src="assets/impact-light.svg" alt="15+ product KPIs defined · ~40% less manual reporting · 20% drop-off uncovered → 3 product changes · 129-case AI evaluation" width="100%" />
</picture>

### How I make a product call

The hardest decision on **[MedNear](https://mednearproduct.netlify.app)**, an AI-assisted medicine-availability app I built 0→1, was what **not** to ship:

```yaml
# MedNear: the go / no-go call
question:  "Where should I go now?"        # one user question, from survey + personas
success_metric: stock_accuracy >= 80%      # written in the PRD before building

launch_bar:                                # set BEFORE testing
  emergencies_caught: ">= 95%"
  lookup_accuracy:    ">= 90%"

eval_set: 129 cases                        # brands, salts, typos, Hindi, Kannada, emergencies
results:
  rules_on_known_cases:      100%
  emergencies_on_blind_set:  20%           # far below the bar

decision:
  ship:      medicine_lookup               # closed/out-of-stock suggestions 30% → 0%, taps 2 → 1
  hold_back: ai_triage
  fallback:  urgent_help_route
  guardrail: eval runs in CI on every change
```

<sub>Full story → <a href="https://akshita-r-portfolio.netlify.app/case.html?id=mednear">MedNear case study</a></sub>

### Featured work

| | | |
|---|---|---|
| 💊 **[MedNear](https://akshita-r-portfolio.netlify.app/case.html?id=mednear)** | AI medicine finder, 0→1 · PRD, Supabase, Gemini API | Live app · AI triage held back on evidence |
| 📊 **[Product KPIs @ CSG](https://akshita-r-portfolio.netlify.app/case.html?id=kpi-dashboards)** | 15+ KPIs · 10+ Power BI dashboards · 6-person pipeline | ~40% less reporting · 25% less rework |
| 🅿️ **[Urban Parking Analytics](https://akshita-r-portfolio.netlify.app/case.html?id=urban-parking)** | Real-time occupancy pipeline · Python, MongoDB, AWS | ₹50K grant · patent filed · 2× finalist |
| 🛒 **[E-commerce Funnel](https://akshita-r-portfolio.netlify.app/case.html?id=ecommerce-funnel)** | SQL funnel + 5+ cohort dashboards · MySQL, Power BI | Found the 23% cart → checkout leak |

### Experience

| Role | Where | When |
|---|---|---|
| **Data Analyst**, Product & Analytics | CSG Systems International | Feb 2025 – present |
| **Backend Engineer**, Product Team | Volopay | Apr 2024 – Feb 2025 |
| **B.E. Computer Science** · CGPA 8.78 | CMR Institute of Technology | 2021 – 2025 |

### How I work

- **Metric first.** I write down what "working" means before anything gets built.
- **Find the leak.** Funnels and cohorts over dashboards nobody reads.
- **Ship what's true.** If the evaluation says "not yet", the feature waits.
- **Team sport.** Years of state-level hockey taught me to read the play and trust my teammates.

### Toolkit

**Product** · User research · PRDs · MVP scoping · RICE · KPIs · Funnel analysis · Agile/Scrum  
**AI product** · Evaluation sets · Launch criteria · Human-in-the-loop design

<p>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white" alt="BigQuery" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Microsoft_Fabric-0078D4?style=flat-square" alt="Microsoft Fabric" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini API" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white" alt="Jira" />
  <img src="https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white" alt="Confluence" />
  <img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white" alt="Excel" />
</p>

### Recognition

🏑 State-level hockey player · 🏆 ₹50K grant + patent filed (Urban Parking) · Srishti 2024 & Smart Argothon 2023 finalist · Merit Scholarship · Best Mini-Project (Sem 1–5) · President, Rise Club · 5th, WIE Competition

---

<p align="center">
  <b>Open to Associate Product Manager & Product Analyst roles.</b><br />
  <a href="mailto:akshitar2003@gmail.com">akshitar2003@gmail.com</a> · <a href="https://akshita-r-portfolio.netlify.app">akshita-r-portfolio.netlify.app</a>
</p>
