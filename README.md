# 🦠 COVID-19 Italy — Excel Analysis & Strategic Report (2020–2025)

> End-to-end Excel analysis of Italy's COVID-19 pandemic using open government data, with a strategic recommendation report delivered to a simulated pharmaceutical client (XYFARMA).

---

## 📌 Project Overview

This project was developed during a Build Week as part of the Epicode Data Analyst programme. Working as **Team 2 (ALF Company)**, the team analysed the evolution of the COVID-19 pandemic in Italy from 2020 to 2025, combining two official open datasets: regional contagion data and vaccination campaign records.

The final output is a structured Excel workbook with pivot tables and a 6-page visual report, plus a written strategic recommendation to XYFARMA on whether to invest in a new vaccine.

---

## 📊 Dataset at a Glance

| Metric | Value |
|---|---|
| Total records | 63,019 rows |
| Time period | 2020 – 2025 |
| Regions covered | 21 Italian regions |
| Data sources | 2 (Ministry of Health + Civil Protection Dept.) |

### Data Sources

| Dataset | Source | License |
|---|---|---|
| COVID-19 vaccinations (2020–2025) | Ministero della Salute / PCM | CC-BY 4.0 |
| COVID-19 regional trend data | Dipartimento Protezione Civile | CC-BY 4.0 |

---

## 🗂️ Repository Structure

```
covid19-italy-excel-analysis/
│
├── 📂 data/
│   └── covid_analysis_xlsx.xlsx     # Unified dataset + pivot tables
│
├── 📂 reports/
│   └── REPORT_FINALE_COVID-19.pdf   # 6-page visual report for XYFARMA
│
└── 📄 README.md
```

---

## 📋 Workbook Structure

| Sheet | Description |
|---|---|
| `Unione Vaccini_Andamento_` | Unified dataset: contagion + vaccination data by region and year |
| `MASCHERA` | Dynamic search mask for filtering by region and year |
| `PIVOT_CONTAGIATI` | Pivot table: annual contagion trend by region |
| `PIVOT_DEC-VAC` | Pivot table: deaths vs vaccinations ratio by region |
| `Pivot_Generale` | Summary pivot: all key KPIs by year |

---

## 🔍 Key Findings

### Contagion Trend (Italy, 2020–2025)

| Year | New Cases | Notes |
|---|---|---|
| 2020 | 902,940 | Pandemic onset |
| 2021 | 1,004,738 | First wave of vaccines |
| 2022 | 3,124,428 | Peak — highest recorded |
| 2023 | 479,725 | Sharp decline |
| 2024 | 272,058 | Stabilisation |
| 2025 | 218,386 | Endemic level |

### Deaths vs Vaccinations
- Mortality ratio in 2022: **65.76 infections per death** — evidence of vaccine effectiveness
- Mortality ratio in 2025: **4,747 infections per death** — near-total risk elimination
- Regions with highest contagion/vaccination ratio: **Emilia-Romagna (5.10)**, **Abruzzo (5.05)**

### Most Affected Regions
- **2020 peak:** Lombardia (164,406), Campania (104,786), Veneto (104,022)
- **2025 peak:** Lazio (88,813), Piemonte (59,905) — anomalous spikes suggesting new variants

---

## 📑 Strategic Report Summary

The report was delivered to a simulated pharmaceutical client (XYFARMA) with the following recommendation:

> **Developing a new mass-market COVID-19 vaccine is not currently justified.** The epidemiological situation has stabilised into an endemic pattern. Mortality has dropped drastically (ratio of 4,750:1 in 2025). Vaccination campaigns have already shifted from mass immunisation to selective booster logic.
>
> **Recommendation:** Focus on targeted booster campaigns for vulnerable groups (elderly, immunocompromised, healthcare workers) and maintain ongoing surveillance for new variants, particularly in Lazio and Piemonte.

---

## 🛠️ Tech Stack

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?logo=microsoft-excel&logoColor=white)

- **Microsoft Excel** — data merging, pivot tables, dynamic charts, search mask
- **Data processing:** `VLOOKUP`, `SUMIF`, `AVERAGEIF`, `YEAR()`, conditional formatting
- **Visualisations:** line charts, column charts, ratio tables with conditional colour coding

---

## 👥 Team

Developed by **Team 2 — ALF Company** during Epicode Build Week (Excel Module).

---

## 📄 License

Data sourced from Italian government open data repositories under CC-BY 4.0 licence. Project developed for academic purposes.
