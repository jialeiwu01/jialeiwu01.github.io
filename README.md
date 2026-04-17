# Jialei Wu — Finance & Analytics Portfolio

Personal portfolio site and two sample projects showing how I approach marketplace analytics and SaaS financial modeling.

**Live site:** https://jialeiwu01.github.io

---

## Projects

### Kestrel Market — Marketplace Analytics Dashboard

Interactive analytics dashboard for a fictional B2B services marketplace. Five analyst views (Overview, Growth, Unit Economics, Cohorts, Categories) with period and category filters that re-render the KPIs and charts live.

- **Built with:** HTML, JavaScript, Chart.js, Tailwind CSS (all via CDN, no build step)
- **Includes:** GMV and take-rate trends, buyer cohort retention heatmap, per-buyer unit economics, LTV:CAC by acquisition quarter, category mix and YoY decomposition
- **Open:** [live dashboard](https://jialeiwu01.github.io/kestrel-dashboard.html) · [source](./kestrel-dashboard.html)

### Lumen Analytics — SaaS Financial Model

Driver-based three-year model for a fictional B2B SaaS company. Customer acquisition, retention, ACV, and opex ratios flow into an ARR waterfall and a quarterly P&L. A single scenario toggle updates every downstream metric.

- **Format:** Excel (.xlsx), 431 formulas, zero formula errors
- **Sheets:** Cover · Summary · Assumptions · Revenue · P&L
- **Includes:** Scenario toggle (Base / Bull / Bear), ARR waterfall (new / expansion / churn), SaaS health metrics (NDR, GRR, CAC payback, LTV:CAC, Rule of 40)
- **Open:** [Google Sheets](https://docs.google.com/spreadsheets/d/1yql3iSmsHjWvYNNVEpPk7QiGut3VAOO8/edit?gid=1432785275#gid=1432785275) · [download .xlsx](./lumen-saas-model.xlsx)

---

## About the data

All data in these projects is synthetic. Company names (Kestrel Market, Lumen Analytics) are fictional. Numbers were generated to tell a coherent story and demonstrate analytical approach, not to represent any real business.

---

## Running locally

No build step required — everything loads via CDN.

```bash
git clone https://github.com/jialeiwu01/jialeiwu01.github.io.git
cd jialeiwu01.github.io
open index.html
```

---

## Contact

- Email: wujialei65@gmail.com
- LinkedIn: https://www.linkedin.com/in/jialeiwu/
- Portfolio: https://jialeiwu01.github.io
