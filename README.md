# Last-Mile Delivery — KPI Dashboard

> **Operations Analytics · Berlin Metro Region · Simulated Dataset**

An interactive KPI dashboard built to surface the metrics that actually matter in last-mile logistics — on-time delivery rate, cost-per-delivery, first-attempt success, and route-level performance across Berlin's delivery zones.

---

## 🚀 Live Preview

Open `Project1_Logistics_KPI_Dashboard.html` directly in your browser — no server or dependencies needed.

---

## ⚠️ Data Disclaimer

**All data in this project is fully simulated.** No real company, real delivery operation, or proprietary dataset was used. All KPI values, route names, zone metrics, cost figures, and trend series were generated programmatically using Python (NumPy/random) and hardcoded illustrative values to produce a realistic operational scenario.

The Berlin district names (Mitte, Pankow, Marzahn, etc.) are real geographies; the performance figures attached to them are fictional.

This project demonstrates **analytical methodology and dashboard design** — not empirical research findings.

---

## 📊 What's Inside

| Component | Description |
|---|---|
| **4 KPI Cards** | OTD rate, cost/delivery, first-attempt success, avg delivery time — each with sparkline trend |
| **Volume vs OTD Chart** | 24-week dual-axis chart: parcel volume (bar) vs on-time rate (line) |
| **Failure Root Cause Analysis** | Donut breakdown of why deliveries fail — recipient absent, wrong address, access issues |
| **Route Performance Table** | Top 6 routes ranked by OTD%, volume, and risk status |
| **Cost Trend** | 6-month cost-per-delivery trajectory with fuel surcharge annotation |
| **Zone Heatmap** | Berlin district-level OTD heatmap — Mitte to Marzahn — colour-coded by performance |

---

## 🔍 Key Insight

> Zone Mitte shows the highest on-time rate (94.2%) but also the highest cost-per-delivery (€4.80). Pankow routes have the lowest failure rate (3.1%) — a strong candidate for operational benchmarking.

---

## 🛠 Tools & Methods

- **Python** — Pandas, NumPy (data simulation and preprocessing)
- **Chart.js** — All interactive visualisations
- **HTML/CSS/JS** — Single-file dashboard, no build tool required
- **Frameworks applied** — KPI tree design, operational variance analysis, route segmentation

---

## 📚 Reference Sources

The simulation parameters (KPI ranges, industry benchmarks, cost structures) were informed by the following publicly available sources. These are cited for context and methodology — not as the source of the dashboard's data.

- **McKinsey & Company** — *The Last-Mile Delivery Challenge* (2016, updated insights 2022). Industry benchmark: last-mile = 40–53% of total supply chain cost. [mckinsey.com](https://www.mckinsey.com)
- **Statista** — *Last-mile delivery cost per parcel, Europe 2023*. Used to calibrate €3–5 cost/delivery range. [statista.com](https://www.statista.com)
- **DHL Supply Chain / Deutsche Post Annual Report 2023** — OTD benchmarks and first-attempt delivery success rates for Germany. [dhl.com/global](https://www.dhl.com/global-en/home/press/press-archive/2023.html)
- **Bundesvereinigung Logistik (BVL)** — *Trends and Strategies in Logistics 2024*. German logistics sector KPI context. [bvl.de](https://www.bvl.de)
- **Capgemini Research Institute** — *The Last-Mile Delivery Challenge Report (2019)*. Failure reason taxonomy (recipient absent, wrong address, access issues) used to structure root cause analysis. [capgemini.com](https://www.capgemini.com/research/the-last-mile-delivery-challenge/)

---

## 💼 Business Context

Last-mile delivery represents 40–50% of total supply chain cost. This dashboard was built to answer three operational questions:

1. Where are we losing on-time performance — and why?
2. Which routes are cost-efficient vs cost-risky?
3. What does the trend in cost-per-delivery signal for margin?

---

## 📁 Files

```
├── Project1_Logistics_KPI_Dashboard.html   # Full interactive dashboard
└── README.md
```

---

## 👤 Author

**Kumar Aditya**  
M.A. International Management · SRH University, Campus Berlin  
[LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/your-handle)  

*Background: Data & Operations Analyst Intern at Spirka Technologies (logistics/supply chain); Strategy Consultant at sdw Berlin.*
