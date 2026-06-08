# 📊 Excel Projects — Market Research & Analytics

> A curated collection of Excel-based projects covering consumer research, sales analytics, SEO reporting, and business intelligence — built as part of my MBA specialisation in Market Research & Analytics.

---

## 👤 About This Repository

This repository showcases my hands-on work with **Microsoft Excel** for real-world market research and data analytics use cases. Each project solves a specific business problem using Excel's analytical capabilities — from pivot tables and dashboards to statistical modelling and automated reporting.

Projects cover a range of domains including consumer research, e-commerce analytics, SEO reporting, and business intelligence — built as part of my MBA specialisation in Market Research & Analytics.

---

## 📁 Project Index

| # | Project | Domain | Key Features |
|---|---------|--------|--------------|
| 01 | [Competitor Price & Review Tracker](#-01-competitor-price--review-tracker) | Market Research | Pivot tables, conditional formatting, trend charts |
| 02 | [Keyword Research Scoring Sheet](#-02-keyword-research-scoring-sheet) | SEO Analytics | Weighted scoring, drop-downs, dynamic ranking |
| 03 | [Customer Sentiment Analysis Tracker](#-03-customer-sentiment-analysis-tracker) | Consumer Insights | Data validation, category tagging, summary dashboard |
| 04 | [Sales & Revenue Dashboard](#-04-sales--revenue-dashboard) | Business Analytics | Interactive slicers, KPI cards, time-series charts |
| 05 | [Market Segmentation Model](#-05-market-segmentation-model) | Market Research | RFM scoring, customer clustering, segment profiling |
| 06 | [SEO Audit & Listing Health Tracker](#-06-seo-audit--listing-health-tracker) | E-commerce SEO | Audit checklist, score calculator, gap analysis |
| 07 | [Survey Data Analyser](#-07-survey-data-analyser) | Primary Research | Frequency tables, cross-tabs, weighted averages |
| 08 | [Monthly Marketing Report Template](#-08-monthly-marketing-report-template) | Reporting | Auto-calculated KPIs, charts, executive summary |

---

## 🗂️ Project Details

### 📌 01. Competitor Price & Review Tracker

**Business Problem:** Track competitor brands across e-commerce platforms for price changes and customer rating trends.

**What It Does:**
- Logs competitor SKUs, prices, ratings, and review counts across Amazon, Myntra & Ajio
- Pivot table summarises average price and rating by brand and platform
- Conditional formatting flags price drops and rating dips automatically
- Trend line charts show week-on-week movement

**Excel Features Used:**
`Pivot Tables` `Conditional Formatting` `VLOOKUP / XLOOKUP` `Line Charts` `Data Validation`

**Folder:** [`/01-competitor-tracker/`](./01-competitor-tracker/)

---

### 📌 02. Keyword Research Scoring Sheet

**Business Problem:** Prioritise the best keywords for an apparel brand targeting a specific region — balancing search volume, competition, and commercial intent.

**What It Does:**
- Inputs: keyword, search volume, competition score, CPC, intent type
- Custom weighted scoring formula ranks keywords automatically
- Drop-down filters by intent (informational / transactional / navigational)
- Top 20 keywords highlighted with conditional colour bands

**Excel Features Used:**
`Weighted Scoring Formula` `Drop-down Lists` `IF / IFS` `RANK` `Conditional Formatting` `Named Ranges`

**Folder:** [`/02-keyword-scoring/`](./02-keyword-scoring/)

---

### 📌 03. Customer Sentiment Analysis Tracker

**Business Problem:** Organise and categorise raw customer review data from multiple e-commerce platforms into structured, actionable insights.

**What It Does:**
- Review data entry with structured columns: platform, product, rating, review text, sentiment, category
- Manual + formula-assisted sentiment tagging (Positive / Neutral / Negative)
- Category classification: Fit, Fabric, Delivery, Price, Design
- Summary dashboard shows sentiment split and top complaint themes by platform

**Excel Features Used:**
`Data Validation` `COUNTIF / COUNTIFS` `Pivot Charts` `Slicer` `Dashboard Layout`

**Folder:** [`/03-sentiment-tracker/`](./03-sentiment-tracker/)

---

### 📌 04. Sales & Revenue Dashboard

**Business Problem:** Provide a single-view interactive dashboard for monthly sales performance tracking.

**What It Does:**
- Connects to raw sales data sheet (product, region, channel, revenue, units)
- Interactive slicers filter by month, product category, and region
- KPI cards show total revenue, units sold, avg order value, and growth %
- Bar + line combo chart shows revenue vs target over time

**Excel Features Used:**
`Pivot Tables` `Pivot Charts` `Slicers` `KPI Cards` `Dynamic Named Ranges` `GETPIVOTDATA`

**Folder:** [`/04-sales-dashboard/`](./04-sales-dashboard/)

---

### 📌 05. Market Segmentation Model

**Business Problem:** Segment customers based on purchase behaviour to identify high-value vs at-risk customer groups.

**What It Does:**
- RFM (Recency, Frequency, Monetary) scoring for each customer
- Percentile-based scoring assigns R, F, M scores (1–5)
- Combined RFM score maps to 6 segments: Champions, Loyal, At-Risk, Lost, New, Potential
- Segment summary table with count, avg revenue, and recommended action

**Excel Features Used:**
`PERCENTILEIF` `Nested IF` `VLOOKUP` `Pivot Summary` `Conditional Formatting` `Bar Charts`

**Folder:** [`/05-market-segmentation/`](./05-market-segmentation/)

---

### 📌 06. SEO Audit & Listing Health Tracker

**Business Problem:** Audit product listings on Flipkart/Amazon for SEO completeness and identify optimisation gaps.

**What It Does:**
- Checklist-based audit: title length, keyword presence, image count, bullet points, A+ content, ratings
- Auto-calculates a listing health score (0–100) per product
- Color-coded gap analysis shows exactly what's missing per listing
- Priority matrix ranks which listings to fix first (high traffic + low score)

**Excel Features Used:**
`Checklist with Checkboxes` `Scoring Formula` `Conditional Formatting` `IF / AND / OR` `Priority Matrix`

**Folder:** [`/06-seo-audit/`](./06-seo-audit/)

---

### 📌 07. Survey Data Analyser

**Business Problem:** Process and summarise primary research survey responses efficiently.

**What It Does:**
- Accepts raw survey export (Likert scale, MCQ, open-ended coded responses)
- Frequency tables and percentage distributions for each question
- Cross-tabulation: response patterns by demographics (age group, gender, location)
- Weighted average NPS and satisfaction scores with interpretation guide

**Excel Features Used:**
`COUNTIF / COUNTIFS` `Cross-tabulation` `Weighted Average` `Frequency Distribution` `Stacked Bar Charts` `Text Coding`

**Folder:** [`/07-survey-analyser/`](./07-survey-analyser/)

---

### 📌 08. Monthly Marketing Report Template

**Business Problem:** Automate monthly marketing performance reporting so teams spend less time on formatting and more on insights.

**What It Does:**
- Input sheet: paste raw data (traffic, leads, conversions, ad spend, revenue)
- Summary sheet: auto-calculates CAC, ROAS, CTR, conversion rate, MoM growth
- Executive summary tab with key highlight cards and commentary prompts
- One-click chart refresh on all visuals

**Excel Features Used:**
`Linked Cells` `Dynamic Charts` `Named Ranges` `KPI Formulas` `Data Tables` `Print-ready Layout`

**Folder:** [`/08-marketing-report-template/`](./08-marketing-report-template/)

---

## 🧰 Excel Skills Demonstrated

| Category | Skills |
|----------|--------|
| **Formulas** | VLOOKUP, XLOOKUP, INDEX-MATCH, IF/IFS, COUNTIFS, SUMIFS, AVERAGEIFS, RANK, PERCENTILE |
| **Data Tools** | Pivot Tables, Slicers, Power Query, Data Validation, Named Ranges |
| **Visualisation** | Bar, Line, Combo, Pie, Scatter, Waterfall charts; Dashboard layouts |
| **Analytics** | RFM Segmentation, Weighted Scoring, Cross-tabulation, Frequency Analysis |
| **Automation** | Linked sheets, Dynamic ranges, Formula-driven KPI cards |
| **Formatting** | Conditional formatting, Print layouts, Executive-ready design |

---

## 🚀 How to Use These Projects

```
1. Clone or download this repository
   git clone https://github.com/rj-mra/excel-projects.git

2. Navigate to any project folder

3. Open the .xlsx file in Microsoft Excel (2016 or later recommended)

4. Each file has a README tab inside explaining the sheets and how to use them

5. Sample data is included in every project — replace with your own data to use
```

> **Note:** All projects use dummy/anonymised data. No real customer or business data is included.

---

## 📂 Repository Structure

```
excel-projects/
│
├── 01-competitor-tracker/
│   ├── competitor-price-review-tracker.xlsx
│   └── screenshot.png
│
├── 02-keyword-scoring/
│   ├── keyword-research-scoring-sheet.xlsx
│   └── screenshot.png
│
├── 03-sentiment-tracker/
│   ├── customer-sentiment-tracker.xlsx
│   └── screenshot.png
│
├── 04-sales-dashboard/
│   ├── sales-revenue-dashboard.xlsx
│   └── screenshot.png
│
├── 05-market-segmentation/
│   ├── rfm-market-segmentation-model.xlsx
│   └── screenshot.png
│
├── 06-seo-audit/
│   ├── seo-listing-audit-tracker.xlsx
│   └── screenshot.png
│
├── 07-survey-analyser/
│   ├── survey-data-analyser.xlsx
│   └── screenshot.png
│
├── 08-marketing-report-template/
│   ├── monthly-marketing-report-template.xlsx
│   └── screenshot.png
│
└── README.md
```

---

## 🏷️ Repository Topics

`excel` `market-research` `data-analytics` `dashboard` `pivot-tables` `rfm-analysis`
`seo` `consumer-insights` `business-intelligence` `reporting` `mba-projects`

---

## 👨‍💼 About Me

**Rishabh Joshi** — MBA
- 🎓 Specialisation in Marketing
- 🔍 Interests: Consumer Insights · Market Analysis · Business Intelligence · Data Automation · Data Analysis
- 📍 Dehradun, Uttarakhand, India

🔗 [LinkedIn](https:// www.linkedin.com/in/rj-mra) · [GitHub Profile](https://github.com/rj-mra) · [All Repositories](https://github.com/rj-mra?tab=repositories)

---

## 📄 License

This repository is for educational and portfolio purposes. Feel free to use these templates for your own learning — attribution appreciated but not required.

---

<p align="center">
  <i>Built with 📊 Excel · Driven by 🔍 Market Research · Designed for 💡 Decision Making</i>
</p>

