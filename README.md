# Data Professional Survey Breakdown

An interactive Power BI dashboard analyzing survey data from 630 data professionals, exploring salary trends, job satisfaction, career entry difficulty, and popular tools within the data industry.

![Dashboard Preview](./images/dashboard_preview.png)

## 📌 Overview

This project transforms raw survey responses into a clean, interactive dashboard that helps answer questions like:

- How much do data professionals earn, broken down by job title?
- How satisfied are professionals with their salary and work/life balance?
- How difficult is it to break into the data field, according to those already in it?
- Which programming languages are most popular among data professionals?
- Where in the world are survey respondents located?

## 🛠️ Tools Used

- **Power Query** — Data cleaning and transformation (handling missing values, standardizing formats, removing duplicates, fixing data types)
- **DAX** — Custom measures for KPIs and calculated metrics
- **Power BI Desktop** — Data modeling and dashboard design

## 🧹 Data Cleaning Process

Before visualization, the raw survey data was processed in Power Query to:
- Remove duplicate and incomplete entries
- Standardize inconsistent text values (e.g., country names, job titles)
- Convert data types (numeric, categorical) for accurate aggregation
- Group low-frequency categories into an "Other" bucket for cleaner visuals

## 📊 Dashboard Features

| Visual | Description |
|---|---|
| **Country of Survey Takers** | Treemap showing geographic distribution of respondents |
| **Average Salary by Job Title** | Horizontal bar chart comparing average salary across roles |
| **Favorite Programming Language** | Stacked bar chart of language popularity, broken down by job title |
| **Difficulty to Break Into Data** | Donut chart showing perceived entry difficulty |
| **Happiness Gauges** | Satisfaction scores for work/life balance and salary (0–10 scale) |
| **Job Title Slicer** | Interactive dropdown filter applied across the entire dashboard |

## 🔑 Key Insights

- **Python** is the dominant programming language among respondents, far ahead of R and other languages.
- **~43%** of respondents rated breaking into the data field as "neither easy nor difficult."
- **Salary satisfaction (4.27/10)** is noticeably lower than **work/life balance satisfaction (5.74/10)**, suggesting compensation may be a bigger pain point than workload for many professionals.
- The **United States** and a broad "Other" category make up the majority of respondents, followed by India, the UK, and Canada.

## 📁 Repository Structure

```
├── data/
│   └── survey_data_raw.csv
├── images/
│   └── dashboard_preview.png
├── README.md
├── dashboard.pbix
```

## 🚀 How to Use

1. Clone this repository
2. Open `dashboard.pbix` in Power BI Desktop
3. Use the **Job Title** slicer at the left top to filter the dashboard by role
4. Explore cross-filtering by clicking on any chart element (e.g., a country or job title)


## 📬 Contact

Feel free to connect or reach out with feedback:
- LinkedIn: [www.linkedin.com/in/mohamed-elshafie-a53232383]
- GitHub: [https://github.com/moshafie512]
