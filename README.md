# 📊 ESG Risk Analysis of S&P 500 Companies

> A comprehensive Power BI dashboard analyzing Environmental, Social, and Governance (ESG) risk across 500+ publicly listed companies in the S&P 500 index.

---

## 📌 About This Project

This project delivers an end-to-end ESG risk analysis of S&P 500 companies using Microsoft Power BI. It evaluates ESG exposure at both the company and sector level, breaks down risk across the three ESG pillars (Environmental, Social, Governance), and maps the relationship between controversy severity and overall risk scores — providing actionable intelligence for responsible investment decision-making.

The dashboard is designed to support ESG due diligence, portfolio screening, regulatory reporting, and alignment with frameworks such as **UN PRI** and **SEBI ESG disclosure norms**.

---

## 🔍 Key Findings

| Metric | Value |
|---|---|
| Avg Total ESG Risk Score | 21.53 |
| Avg Environment Risk Score | 5.74 |
| Avg Social Risk Score | 9.07 |
| Avg Governance Risk Score | 6.73 |
| Highest Risk Company | OXY – Occidental Petroleum (42) |
| Lowest Risk Company | HAS – Hasbro |
| % Low Risk Companies | 43.7% (188 companies) |
| % Severe Risk Companies | 1.3% (3 companies) |

### 🏭 Sector-Level ESG Risk Rankings

| Sector | Avg ESG Score | Risk Profile |
|---|---|---|
| Energy | 32.34 | 🔴 Highest |
| Basic Materials | 26.72 | 🔴 High |
| Utilities | 26.71 | 🔴 High |
| Consumer Defensive | 25.45 | 🟠 Moderate-High |
| Industrials | 24.01 | 🟠 Moderate |
| Financial Services | 21.19 | 🟡 Moderate |
| Healthcare | 20.58 | 🟡 Moderate |
| Communication Services | 19.41 | 🟡 Moderate |
| Consumer Cyclical | 19.23 | 🟡 Moderate |
| Technology | 16.92 | 🟢 Low |
| Real Estate | 13.09 | 🟢 Lowest |

### ⚠️ Controversy Level vs ESG Risk

| Controversy Level | Avg ESG Risk Score | vs. No-Controversy Baseline |
|---|---|---|
| Severe | 36.75 | +127% |
| High | 30.07 | +86% |
| Significant | 24.20 | +50% |
| Moderate | 21.96 | +36% |
| Low | 18.89 | +17% |
| None | 16.16 | Baseline |

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** — Dashboard design, data modeling, DAX measures
- **Power Query** — Data cleaning and transformation
- **DAX (Data Analysis Expressions)** — Custom KPI calculations
- **Dataset** — Publicly available S&P 500 ESG Risk Scores (500+ companies, 11 GICS sectors)

---

## 📐 Methodology

1. **Data Import** — ESG risk score dataset loaded into Power BI Desktop
2. **Data Cleaning** — Power Query used to handle ~73 missing pillar records (~14.6%), excluded from pillar averages but retained in count-based visuals
3. **DAX Measures Created:**
   - `% High Risk Companies` — percentage of High or Severe ESG risk companies
   - `Max ESG Company` — company with the highest total ESG risk score
   - `Min ESG Company` — company with the lowest total ESG risk score
4. **Dashboard Design** — Cross-filtering, sector drill-downs, and controversy-level segmentation

---

## 💡 Key Insights & Recommendations

- **Underweight Energy & Basic Materials** in ESG-mandated portfolios (scores: 32.34 and 26.72)
- **Overweight Technology & Real Estate** as ESG risk-adjusted alternatives
- **Use controversy level as a pre-screening filter** — Severe controversy companies score 127% above no-controversy peers
- **Flag 50 High-risk and 3 Severe-risk companies** for quarterly ESG review
- Social risk is the dominant ESG pillar, contributing **42%** of average total risk — focus engagement on workforce practices and human rights

---

## 📋 ESG Risk Category Distribution

| Category | Count | % of S&P 500 |
|---|---|---|
| Negligible | 6 | 1.4% |
| Low | 188 | 43.7% |
| Medium | 183 | 42.6% |
| High | 50 | 11.6% |
| Severe | 3 | 0.7% |

---

## 📄 Report

A detailed written report (`ESG_Risk_Analysis_Report.pdf`) accompanies this dashboard, covering the executive summary, full methodology, findings, and investment recommendations.
[View Full Report](ESG_Risk_Analysis_Report.pdf)
---
## Dashboard
<img width="1156" height="653" alt="Screenshot 2026-04-05 030456" src="https://github.com/user-attachments/assets/6e37927a-bdee-475c-a09c-61c1103759c3" />
