[README.md](https://github.com/user-attachments/files/27899153/README.md)
# 🏥 Emergency Ward Hospital Analytics Dashboard
### Power BI | Healthcare Analytics | Hospital Operations KPIs

---

## 📌 Project Overview

This Power BI dashboard provides a comprehensive view of Emergency Ward operations for hospital administrators and healthcare analysts. Built on **19 months of real-world ER data (April 2023 – October 2024)**, it tracks patient flow, wait times, satisfaction levels, referral patterns, and admission trends — enabling data-driven decisions in high-pressure clinical environments.

The dashboard helps healthcare leadership answer critical questions:
- How many patients are being seen each day, week, and month?
- Are wait times within acceptable clinical thresholds?
- What is the patient satisfaction score — and where are the gaps?
- Which hours and days experience the highest patient load?
- What is the gender-wise, age-wise, and race-wise patient breakdown?

---

## 📊 Dashboard Pages

The report contains **4 interactive pages**, each serving a different analytical purpose:

---

### 1. 📅 Monthly View
Tracks all key KPIs on a **month-by-month basis** with a YY-MM slicer for easy navigation. Includes patient admission status, age group distribution, department referrals, race breakdown, gender split, % seen within 30 minutes, and a day-hour heatmap.

> **Sample snapshot — February 2024:** 431 patients | Avg Wait: 36.7 Min | Avg Satisfaction: 4.72 | Referred: 179

![Monthly View](screenshots/monthly_view.png)

---

### 2. 📋 Consolidated View
A **full-period overview (April 2023 – October 2024)** summarising all metrics in one place. Ideal for leadership dashboards and executive reporting. Shows total-level KPIs, referral volumes, age distribution, gender and race breakdowns, and the complete day-hour heatmap across 9,216 patients.

> **Total period:** 9K patients | 35.3 Min avg wait | 4.99 avg satisfaction | 4K referred

![Consolidated View](screenshots/consolidated_view.png)

---

### 3. 👤 Patient Details
A **drill-down table page** listing individual patient records with columns for Patient ID, Full Name, Gender, Age, Race, Wait Time, Department Referral, and Admission Status. Supports filtering by date range for granular operational review.

![Patient Details](screenshots/patient_details.png)

---

### 4. 💡 Key Takeaways
An **insights summary page** written for stakeholder presentations. Highlights the most critical findings from the dataset in readable narrative form — covering wait time analysis, departmental referrals, peak busy periods, patient demographics, race distribution, and admission patterns.

![Key Takeaways](screenshots/key_takeaways.png)

---

## 📈 Key Metrics & Findings

| KPI | Value |
|-----|-------|
| **Total Patients** | 9,216 (April 2023 – October 2024) |
| **Avg Wait Time** | 35.3 minutes |
| **Avg Satisfaction Score** | 4.99 / 10 |
| **Total Patients Referred** | ~4K |
| **% Seen Within 30 Min** | 59.32% (within target) |
| **Admitted** | 4,612 (50.04%) |
| **Not Admitted** | 4,604 (49.96%) |
| **Top Referral Dept** | General Practice (1,840 cases) |
| **Busiest Day** | Monday (1,377 patients) |
| **Busiest Hours** | 11 AM, 7 PM, 1 AM, 11 PM |
| **Largest Age Group** | 30–39 Years (1,200 patients) |
| **Largest Race Group** | White (2,571 patients) |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Power BI Desktop** | Dashboard design, data modeling, and visualization |
| **DAX (Data Analysis Expressions)** | Custom KPI calculations and measures |
| **Power Query (M Language)** | Data transformation and cleaning |
| **Excel / CSV** | Source data format |

---

## 📁 Repository Structure

```
Emergency-Ward-Hospital-Analytics-PowerBI/
│
├── Emergency_Ward.pbix          # Main Power BI dashboard file
├── README.md                    # Project documentation (this file)
│
└── screenshots/                 # Dashboard page screenshots
    ├── monthly_view.png         # Page 1 — Monthly KPI view
    ├── consolidated_view.png    # Page 2 — Full period overview
    ├── patient_details.png      # Page 3 — Individual patient table
    └── key_takeaways.png        # Page 4 — Insights summary
```

---

## 🚀 How to Use

1. **Download** the `Emergency_Ward.pbix` file from this repository
2. **Open** it in [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free to download)
3. **Explore** each of the 4 report pages using the navigation buttons on the left menu
4. **Use the date slicer** (top right) to filter by any time period between April 2023 – October 2024
5. **Use the YY-MM dropdown** on the Monthly View to switch between months
6. **Publish** to Power BI Service if you want to share it online with your team

---

## 💼 Domain

**Healthcare Analytics** | Hospital Operations | Clinical KPIs | Emergency Medicine | Patient Flow Analysis

This project demonstrates skills applicable to roles such as:
- Data Analyst (Healthcare / Hospital sector)
- Business Intelligence Developer
- Power BI Developer
- Healthcare Data Analyst
- Clinical Reporting Analyst

---

## 🔗 Connect With Me

| Platform | Link |
|----------|------|
| **LinkedIn** | https://www.linkedin.com/in/kumar97roshan/ |
| **Portfolio** | https://kumar-roshan-bidev-vh64ira.gamma.site/ |
| **Email** | kumar97roshan@gmail.com |
| **Phone** | +918936827737 |

---

## 📄 License

This project is for portfolio and educational purposes. The dataset used is synthetic/anonymized and does not represent real patient data.

---

> ⭐ If you found this project useful or interesting, please consider starring the repository — it helps others discover it!
