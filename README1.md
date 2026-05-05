# Visualization in Power BI using Sample Data

This project analyzes **People Analytics** using sample employee data, exploring key dimensions — Income, Gender Diversity, Country, and Performance — to uncover actionable business insights. The report is built in Power BI Desktop and covers four dedicated dashboard pages.

---

## Table of Contents

- [Report Pages](#report-pages)
  - [Training Details](#training-details)
  - [Gender Diversity](#gender-diversity)
  - [Demographics](#demographics)
  - [Employee Performance](#employee-performance)
- [Key Insights](#key-insights)
- [Data Source](#data-source)
- [Technologies Used](#technologies-used)
- [Prerequisites & How to Open](#prerequisites--how-to-open)
- [Project Structure](#project-structure)

---

## Report Pages

### Training Details

![image](https://github.com/user-attachments/assets/03b52463-b4e6-4cc3-9ecd-061a71ce9419)

This dashboard provides a comprehensive view of employee learning and development activity across the organization. It tracks training enrollment versus completion counts, average training hours per employee, and a breakdown of courses by category (e.g., technical, compliance, leadership). Department-level bar charts highlight which teams are investing the most in upskilling, while a trend line shows how training completion has evolved over time. KPI cards surface top-line numbers — total employees trained, overall completion rate, and total training hours logged — giving HR teams a quick pulse on workforce development health.

---

### Gender Diversity

![image](https://github.com/user-attachments/assets/86615c11-fd59-457d-8cc2-39b957dedc80)

This page focuses on representation and equity across the workforce. A donut chart displays the overall male/female split at a glance, while stacked bar charts break the ratio down by department, level, or location to reveal where imbalances are concentrated. Trend visuals show how diversity has changed quarter-over-quarter or year-over-year, helping organizations track progress against hiring and inclusion targets. KPI cards highlight key figures such as diversity index score, headcount by gender, and the gender split among leadership roles — making it easy to identify gaps and drive evidence-based DE&I initiatives.

---

### Demographics

![image](https://github.com/user-attachments/assets/d749da0f-9449-4a19-af3a-344921f4c0bc)

The Demographics page maps the composition of the workforce across multiple dimensions. A geographic map visual shows employee distribution by country or region, giving a global view of talent spread. Supporting charts break down the workforce by age group (histogram), years of tenure, education level, and marital status. Together these visuals answer questions like "Where is our workforce concentrated?", "How experienced is our average employee?", and "What does our pipeline look like in terms of education background?" KPI cards display total headcount, average age, and average tenure, providing a snapshot of the workforce at any point in time.

---

### Employee Performance

![image](https://github.com/user-attachments/assets/6beb2025-1438-408a-bed6-615adc0f14a5)

This dashboard evaluates individual and team-level performance across the organization. A bar chart shows the distribution of performance ratings (e.g., Exceeds Expectations, Meets Expectations, Needs Improvement), while department-level breakdowns reveal which teams have the highest concentration of top performers. A scatter plot explores the relationship between performance scores and compensation, highlighting potential pay-for-performance misalignments. Performance trend lines over time help identify whether scores are improving or declining. KPI cards surface average performance score, percentage of high performers, and attrition risk indicators — equipping managers and HR partners with the data needed for talent reviews and succession planning.

---

## Key Insights

- Training completion rates vary significantly by department, pointing to opportunities for more targeted L&D investment in lower-performing teams.
- Gender representation gaps are most visible at senior levels, suggesting that mentorship and promotion pipelines need attention.
- A large portion of the workforce is clustered in a mid-tenure range (3–7 years), which may indicate retention risk if engagement is not actively managed.
- High-performing employees are not always the highest-compensated, indicating a potential misalignment between pay bands and performance outcomes.
- Geographic workforce distribution is concentrated in a small number of countries, which may present diversity and business-continuity risks.

---

## Data Source

This report uses **sample / anonymized People Analytics data**. The dataset includes the following fields:

| Field | Description |
|---|---|
| Employee ID | Unique identifier per employee |
| Department | Business unit or team |
| Gender | Employee gender |
| Country / Region | Work location |
| Age | Employee age |
| Tenure (Years) | Years with the organization |
| Education Level | Highest qualification |
| Training Status | Enrolled / Completed / Not Started |
| Training Hours | Total hours of training completed |
| Performance Rating | Annual review rating |
| Salary / Income | Compensation band or value |

---

## Technologies Used

| Tool | Purpose |
|---|---|
| Power BI Desktop | Report design, data modelling, and publishing |
| DAX | Calculated columns, measures, and KPI logic |
| Power Query (M) | Data transformation and cleaning |

---

## Prerequisites & How to Open

1. Download and install **Power BI Desktop** (free) from [microsoft.com/en-us/power-bi](https://www.microsoft.com/en-us/power-bi/desktop)
2. Clone or download this repository
3. Open `People_AnalyticsR2.pbix` in Power BI Desktop
4. Navigate between report pages using the tabs at the bottom of the canvas:
   - Training Details
   - Gender Diversity
   - Demographics
   - Employee Performance

> No credentials or data gateway are required — the report uses embedded sample data.

---

## Project Structure

```
BI-Reports/
├── People_AnalyticsR2.pbix   # Power BI report file (open in Power BI Desktop)
└── README.md                 # Project documentation (this file)
```
