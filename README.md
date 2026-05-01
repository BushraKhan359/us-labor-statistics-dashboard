# 📊 Maven Careers — US Wage & Employment Dashboard

> An interactive Excel dashboard built for Maven Careers, a non-profit helping high school seniors explore career paths — enabling students to compare wages, employment, and industry trends across 48 US states from 2017 to 2020.

---

## 🖼️ Dashboard Preview

<!-- Add your dashboard screenshot here -->
![Maven Careers Dashboard](screenshots/dashboard.png)


https://github.com/user-attachments/assets/8d34d677-5c04-4804-948b-45d5c19302c3---

## 📌 Project Overview

**Client:** Maven Careers (non-profit career guidance organization)
**Role:** Research Analyst & Excel Dashboard Designer
**Tool:** Microsoft Excel
**Dataset:** US_Labor_Statistics.xlsx (BLS Data, 2018–2020)
**Period Covered:** 2018 – 2020 | 48 States | 10 Industries

The Head of Research needed a dashboard ready for an upcoming round of high school visits. The goal: let students explore real labor market data — wages, employment size, and state-by-state differences — and use it to inform their career choices.

The brief from Susy Salary (Head of Research):

> *"Can you please create a dashboard that seniors can use to explore wage and employment trends, and compare them across industries? A map showing differences across states would help a ton."*

---

## ✨ Key Features

- 🏭 **Industry Filter** — Select any of 10 industries; all visuals update instantly
- 📅 **Year Filter** — Toggle between 2018, 2019, and 2020 data
- 📈 **Wage & Employment Trend Chart** — Track how average wages and employee counts changed year-over-year for the selected industry
- 🏆 **Average Wage by Industry Bar Chart** — Ranked comparison of all 10 industries; selected industry highlighted
- 🍩 **Employee Share Donut Chart** — Shows the selected industry's share of total US employment
- 🗺️ **Interactive US State Map** — Toggle between Average Wage and Employees per 1,000 Capita across all 48 states
- 🔄 **Fully Dynamic** — Every chart, table, and KPI updates from two dropdowns

---

## 📊 Key Insights From the Data (2020)

| Industry | Avg Annual Wage | Employment Size |
|---|---|---|
| 🥇 Information | $88,539 | Smaller but high-value |
| 🥈 Finance | $86,439 | Large and stable |
| 🥉 Business Services | $72,152 | Largest employer |
| Manufacturing | $66,954 | Significant in Midwest |
| Construction | $62,639 | Strong regional variation |
| Natural Resources | $54,138 | High variance by state |
| Education & Health | $51,943 | Largest public sector |
| Trade & Transportation | $47,859 | Most employees nationally |
| Other Services | $38,994 | Broad and fragmented |
| 📉 Leisure & Hospitality | $22,791 | Lowest paid — nearly 4x gap vs. top |

**The 4x wage gap** between Information ($88K) and Leisure & Hospitality ($22K) is the single most powerful insight this dashboard surfaces for students — a data point that can genuinely shape a career decision.

---

## 🗺️ What the Map Shows

The state map supports two views toggled by a button:

- **Average Wage** — Which states pay the most for the selected industry? (Texas leads in Natural Resources at $117K; California leads Information)
- **Employees per 1,000 Capita** — Where is this industry most concentrated relative to population? Normalizing for population removes the California/Texas size bias and reveals smaller states with outsized industry presence.

---

## 🛠️ Tools & Techniques

| Skill | Application |
|---|---|
| Excel PivotTables | Aggregating wages and employment by industry, state, year |
| Data Validation | Industry and year dropdown selectors |
| AVERAGEIFS / SUMIFS | Dynamic KPI calculations across filtered dimensions |
| VLOOKUP | Pulling selected industry's employee share |
| Array Formulas | Powering the dynamic state map visualization |
| Conditional Formatting | Color-coded map intensity by state value |
| Named Ranges | Stable references across Data, Data Prep, and Dashboard sheets |
| Dynamic Chart Linking | All charts respond to filter changes without manual refresh |

---

## 📁 Repository Structure

```
us-labor-statistics-dashboard/
│
├── US_Labor_Statistics.xlsx        # Full workbook: Data + Data Prep + Dashboard
├── README.md                       # This file
├── PROJECT_BRIEF.md                # Original brief from Maven Careers
│
└── screenshots/
    └── dashboard.png               # Dashboard preview image
```

---

## 🚀 How to Use

1. **Download** `US_Labor_Statistics.xlsx`
2. **Open** in Microsoft Excel (2016 or later recommended)
3. **Enable content** if prompted
4. Use the **Industry dropdown** to select a career sector
5. Use the **Year toggle** to switch between 2018 / 2019 / 2020
6. Use the **Map toggle** to switch between Avg Wage and Employees per 1,000 Capita
7. All charts, the trend line, and the map update automatically

---

## 🎯 Design Philosophy

This dashboard was built for a 17-year-old who has never looked at labor statistics before.

That means no jargon. No axes that require a legend to decode. No charts that need a 10-minute walkthrough before the insight lands.

Every visual answers one question a student would actually ask:
- *"Which industry pays the most?"* → The wage bar chart answers this in 2 seconds
- *"Is this industry growing?"* → The trend chart shows it year-over-year
- *"Where in the US should I look for jobs in this field?"* → The map answers this at a glance

A dashboard that only makes sense to the person who built it has failed its user. This one doesn't need a guide.

---

## 👤 About

**Created by:** Bushra Khan

**Portfolio:** [thedataalchemist.co](http://thedataalchemist.co)

**LinkedIn:** [linkedin.com/in/bushra-nazeer-khan](https://www.linkedin.com/in/bushra-nazeer-khan/)

**GitHub:** [github.com/BushraKhan359](https://github.com/BushraKhan359)

Available for onsite roles in Karachi, Pakistan | Open to remote globally

---

*Built as part of a data analytics portfolio demonstrating Excel dashboard design, data storytelling, and stakeholder-focused visualization.*



