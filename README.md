# 📊 Data Professional Survey Breakdown (Power BI Dashboard)

This project analyzes the background of data professionals using survey data. It includes visual insights on job titles, average salaries, favorite programming languages, and job satisfaction levels.

---

## 📌 Dashboard Preview

![Dashboard Screenshot](Screenshot 2025-07-16 180043.png?raw=true)

---

## 🧩 Project Highlights

- **Dataset:** Based on survey responses from 630 data professionals
- **Objective:** To explore the demographics, skills, and sentiments of people in data roles
- **Data Source:** Provided via `.csv` file (included in repo)

---

## 🧹 Data Wrangling Steps

Performed inside Power BI (Power Query Editor):
- Removed null and duplicate values
- Renamed columns for better readability
- Split and formatted date fields
- Re-coded categorical responses (e.g., job roles, difficulty levels)

---

## 📈 Key Visuals in Dashboard

- **🌍 Countries of Survey Takers** – Treemap by country
- **💼 Average Salary by Job Title** – Bar chart comparison
- **📊 Favorite Programming Languages** – Stacked bar chart by job title
- **📘 Difficulty to Break Into Data** – Donut chart
- **😀 Happiness Metrics:**
  - Work-Life Balance (Avg: 5.74)
  - Salary Satisfaction (Avg: 4.27)
- **📌 Summary Cards:**
  - Count of Unique Respondents: **630**
  - Average Age: **29.87 years**

---

## 📁 Project Structure

```bash
powerbi-data-professional-survey/
├── Data_Professional_Survey.pbix       # Power BI dashboard
├── data/
│   └── survey_results.csv              # Source data
├── screenshots/
│   └── dashboard.png                   # Dashboard preview image
└── README.md                           # Project documentation
