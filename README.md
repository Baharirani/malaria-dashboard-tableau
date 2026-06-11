# malaria-dashboard-tableau
# 🦟 Global Malaria Trends — Interactive Tableau Dashboard

![Tableau](https://img.shields.io/badge/Tool-Tableau-blue) ![Data Visualisation](https://img.shields.io/badge/Field-Data%20Visualisation%20%7C%20Public%20Health-green) ![WHO](https://img.shields.io/badge/Data-WHO%20Dataset-orange)

## 📌 Project Overview

This project presents an **interactive Tableau dashboard** analysing global malaria trends using WHO data from 2000 to the present. The dashboard visualises geographical distribution, incidence rates, mortality trends, and regional patterns to support public health decision-making and awareness.

---

## 🎯 Objectives

- Design a clear and interactive data visualisation for a global health dataset
- Analyse malaria incidence and mortality trends across regions and time
- Apply advanced Tableau features, including LOD calculations and geographic mapping
- Communicate complex public health data in an accessible and actionable format

---

## 📂 Dataset

| Dataset | Description |
|---|---|
| WHO Malaria Dataset | Global malaria incidence, mortality, and case data by country (2000–present) |
| Source | World Health Organisation (WHO) |
| Format | Structured CSV with country, year, region, and case metrics |

---

## 🛠️ Methods & Tools

| Category | Tools / Methods |
|---|---|
| Visualisation Tool | Tableau Desktop / Tableau Public |
| Data Preparation | Data cleaning, reshaping, and null handling |
| Advanced Features | LOD (Level of Detail) Expressions, calculated fields |
| Chart Types | Choropleth maps, line charts, bar charts, heatmaps, KPI cards |
| Interactivity | Filters, parameters, drill-down views, dashboard actions |

---

## 📊 Dashboard Features

- 🗺️ **World Map** — Choropleth map showing malaria incidence by country
- 📈 **Trend Lines** — Year-on-year malaria cases and deaths from 2000 to present
- 🌍 **Regional Comparison** — Side-by-side comparison of WHO regions
- 🔢 **KPI Cards** — Key statistics: total cases, total deaths, highest-risk regions
- 🎛️ **Interactive Filters** — Filter by year, region, country, and metric type

---

## 💡 Key Findings

- Sub-Saharan Africa accounts for the vast majority of global malaria cases and deaths
- Significant progress in reducing malaria mortality was achieved between 2000 and 2015
- Progress has slowed or reversed in some regions after 2015, highlighting ongoing challenges
- Children under 5 and pregnant women remain the most vulnerable populations
- Geographic visualisation reveals clear regional disparities in access to treatment

---

## 🗂️ Project Structure

```
malaria-dashboard-tableau/
│
├── data/
│   └── who_malaria_data.csv       # Cleaned WHO malaria dataset
├── dashboard/
│   └── malaria_dashboard.twbx     # Tableau packaged workbook
├── screenshots/
│   ├── world_map.png              # Choropleth map view
│   ├── trend_lines.png            # Year-on-year trend chart
│   └── regional_comparison.png    # Regional breakdown view
└── README.md
```

---

## 🖥️ How to View the Dashboard

**Option 1 — Tableau Public (recommended):**
Open the dashboard directly on Tableau Public: https://public.tableau.com/app/profile/bahar.irani1397/viz/Bahar_Irani/Dashboard1

**Option 2 — Tableau Desktop:**
```bash
# Clone the repository
git clone https://github.com/baharirani/malaria-dashboard-tableau.git
cd malaria-dashboard-tableau

# Open the Tableau workbook
# Open Tableau Desktop and load: dashboard/malaria_dashboard.twbx
```

---

## 📚 Context

This project was completed as part of an **MSc in Data Analytics** (Data Visualisation module) at the Berlin School of Business and Innovation (BSBI), Berlin (2025).

---

## 👩‍💻 Author

**Bahar Irani**
MSc Data Analytics | Data Analyst
📧 iranibahhar@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/bahar-irani-1740952b0)
