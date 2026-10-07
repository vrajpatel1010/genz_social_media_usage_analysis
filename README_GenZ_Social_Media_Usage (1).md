# Gen-Z Social Media Usage — Power BI Analytics Project

## 📊 Project Overview

**Gen-Z Social Media Usage** is an end-to-end **Power BI data analytics project** that explores how Gen-Z users interact with social media and how usage patterns relate to wellbeing, sleep habits, demographics, and platform preferences.

The project combines a **1-million-row dataset**, data preparation, a Power BI data model, DAX measures, interactive slicers, and multiple analytical report pages.

## 🔗 Project Resources

### 📊 Gen-Z Social Media Usage
This is my complete **end-to-end data analytics project**, covering data preparation, transformation, data modelling, DAX analysis, KPI development, and interactive dashboard development:

**[Open Power BI Dashboard](<https://drive.google.com/file/d/1ZsOFvfiYx69F6UrLjU9unCoJMI3JRPy_/view?usp=drive_link>)**

> The project contains the complete analytical workflow with interactive report pages, KPIs, slicers, analytical visuals, data modelling, and Gen-Z social-media usage insights.

### 🗂️ Source Dataset
The dataset used to build this Power BI project is available here:

**[Download / View Source Dataset](<https://drive.google.com/file/d/1p8tib0MZG_LU05XxKdekq20_3nyIM2JW/view?usp=sharing>)**

> The source dataset contains approximately **1,000,000 records** used for Power Query transformation, data modelling, DAX analysis, and dashboard development.

---

### Main questions answered

- Which social-media platforms and purposes dominate Gen-Z attention?
- How do daily usage hours and session length vary across platforms and user segments?
- How is night-time usage related to mental-health scores?
- How does screen time before sleep vary across users?
- How do age, gender, and country influence social-media behaviour?
- Which segments show higher usage intensity or lower wellbeing scores?

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query** — data cleaning and transformation
- **DAX** — calculated measures and analytical KPIs
- **Microsoft Excel / CSV** — source-data compatible workflow
- **Data Visualization** — interactive charts, cards, tables, maps, heatmaps, and scorecards

---

## 📁 Project Files

```text
├── genz_social_media_usage_v4.pbix
├── genz_social_media_usage_1M.csv
└── README.md
```

### File descriptions

| File | Description |
|---|---|
| `genz_social_media_usage_v4.pbix` | Main Power BI report containing the data model, DAX measures, visuals, filters, and dashboard pages |
| `genz_social_media_usage_1M.csv` | Source dataset containing approximately 1 million Gen-Z social-media usage records |
| `README.md` | Project documentation |
| [Power BI Dashboard](https://drive.google.com/file/d/1ZsOFvfiYx69F6UrLjU9unCoJMI3JRPy_/view?usp=drive_link) | Online access to the completed Power BI dashboard |
| [Source Dataset](https://drive.google.com/file/d/1p8tib0MZG_LU05XxKdekq20_3nyIM2JW/view?usp=sharing) | Google Drive link to the dataset used in the project |

---

## 📈 Power BI Report Pages

The Power BI report contains **7 pages**:

### 1. Cover
Project introduction and navigation to the analytical sections.

### 2. Executive Summary
Provides a high-level view of:
- Total users
- Average daily usage
- Average session duration
- Mental-health score
- Night usage
- Platform and purpose distribution
- Usage trends and user segments

### 3. Platform Analysis
Compares social-media platforms using:
- Daily usage
- Session duration
- Mental-health score
- User count
- Purpose
- Gender
- Platform positioning

### 4. Wellbeing & Sleep
Focuses on:
- Night-time social-media usage
- Screen time before sleep
- Mental-health score
- Usage intensity
- Bedtime screen categories
- Relationship between usage behaviour and wellbeing

### 5. Audience & Geography
Analyzes:
- Country-level distribution
- Age groups
- Gender
- Platform usage
- Number of platforms used
- Geographic differences in behaviour

### 6. Heatmaps & Scorecards
Provides a more detailed analyst view using:
- Colour-scaled matrices
- Age × usage analysis
- Usage categories
- Gender comparisons
- Drill-down tables
- Scorecards

### 7. Project Brief
Documents:
- Project objective
- Data model
- KPI definitions
- Report navigation
- Suggested insights and recommendations
- Project limitations

---

## 🗂️ Dataset

The source file contains **1,000,000 records** and **12 original columns**.

### Dataset columns

| Column | Description |
|---|---|
| `age` | Age of the respondent |
| `gender` | Gender category |
| `country` | Country of the respondent |
| `daily_usage_hours` | Average social-media usage per day in hours |
| `primary_platform` | Main social-media platform used |
| `num_platforms_used` | Number of social-media platforms used |
| `purpose` | Main reason for using social media |
| `avg_session_minutes` | Average duration of a social-media session |
| `night_usage` | Indicates whether the user uses social media at night |
| `mental_health_score` | Mental-health / wellbeing score |
| `addiction_level` | Categorized social-media addiction level |
| `screen_time_before_sleep` | Screen time before sleeping |

---

## 🌍 Dataset Coverage

The dataset includes:

### Countries
- India
- USA
- Canada
- UK
- Germany
- Brazil
- Australia

### Primary Platforms
- Instagram
- YouTube
- TikTok
- Twitter
- Snapchat

### Main Purposes
- Entertainment
- Socializing
- Education
- News
- Content Creation

### Addiction Levels
- Low
- Medium
- High

### Gender Categories
- Female
- Male
- Other

---

## 🧩 Data Model

The Power BI report uses a **star-schema-oriented model**.

### Main fact table

`genz_social_media_usage_1M`

### Dimension tables

- `DimCountry`
- `DimPlatform`
- `DimGender`
- `DimPurpose`

### Derived fields

The report also uses calculated / derived fields such as:

- **Age Group**
- **Usage Category**
- **Bedtime Screen Category**

### Data workflow

```text
CSV Source
    ↓
Power Query Cleaning & Transformation
    ↓
Data Model / Star Schema
    ↓
DAX Measures
    ↓
Interactive Visualizations
    ↓
Power BI Dashboard
```

---

## 📌 Key KPIs

The report includes DAX-driven KPIs such as:

| KPI | Definition |
|---|---|
| **Total Users** | Number of respondents |
| **Average Daily Usage** | Average daily social-media usage in hours |
| **Average Session Time** | Average session duration in minutes |
| **Average Mental Health Score** | Mean wellbeing score |
| **Night Usage %** | Percentage of users active at night |
| **Average Screen Time Before Sleep** | Average screen exposure before sleep |
| **Average Platforms Used** | Average number of platforms used per respondent |
| **Average Age** | Average respondent age |

---

## 🔍 Example Dataset Profile

Based on the supplied 1-million-row dataset:

- **1,000,000** total records
- **7** countries
- **5** primary platforms
- **5** main usage purposes
- **3** gender categories
- **3** addiction-level categories
- Average daily usage: approximately **3.51 hours**
- Average session duration: approximately **25.09 minutes**
- Average mental-health score: approximately **7.17 / 10**
- Approximately **60%** of records indicate night-time usage

These figures describe the supplied dataset and can change if the source data is replaced or updated.

---

## 📊 Analytical Highlights

The dataset allows analysis of several important patterns.

For example, the supplied data shows a strong **negative statistical association** between daily social-media usage hours and the mental-health score. This should be interpreted as an association in the dataset, **not as evidence that social-media usage causes poorer mental health**.

The dashboard allows this relationship to be explored interactively by filtering by:

- Gender
- Age group
- Country
- Platform
- Purpose
- Usage category
- Addiction level
- Bedtime screen category

---

## 🎛️ Interactivity

The report includes interactive navigation and filters/slicers.

Users can explore the data by combinations of:

```text
Gender
Age
Platform
Purpose
Country
```

Filters can be used to move from the overall Gen-Z population to specific audience segments.

---

## 💡 Suggested Business / Analytical Insights

The dashboard can be used to identify:

1. **Top platforms** by audience size and usage intensity.
2. **Dominant purposes** for social-media usage.
3. **High-usage segments** that may require closer analysis.
4. **Night-time usage patterns** across demographic groups.
5. **Bedtime screen exposure** and its relationship with wellbeing scores.
6. **Age × usage segments** with comparatively lower mental-health scores.
7. **Country-level differences** in social-media behaviour.
8. Platform-specific opportunities for wellbeing campaigns and user-engagement strategies.

---

## 🚀 How to Use

### 🔗 Online Resources

- **Gen-Z Social Media Usage — End-to-End Project:** [Open Project Dashboard](https://drive.google.com/file/d/1ZsOFvfiYx69F6UrLjU9unCoJMI3JRPy_/view?usp=drive_link)
- **Source Dataset:** [View / Download Dataset](https://drive.google.com/file/d/1p8tib0MZG_LU05XxKdekq20_3nyIM2JW/view?usp=sharing)

### Requirements

Install **Microsoft Power BI Desktop**.

### Steps

1. Download or clone this repository.
2. Open:

```text
genz_social_media_usage_v4.pbix
```

3. Review the report pages using the navigation buttons.
4. Use the available slicers to filter the analysis.
5. If replacing the source data, ensure the new dataset keeps the expected column names and compatible data types.
6. Refresh the Power BI model after updating the source.

---

## 🧠 Skills Demonstrated

This project demonstrates practical skills in:

- Data cleaning
- Data transformation
- Exploratory data analysis
- Data modelling
- Star schema design
- DAX measures
- KPI development
- Interactive dashboard design
- Data visualization
- Demographic analysis
- Behavioural analysis
- Wellbeing and usage analysis
- Business storytelling with data

---

## ⭐ Project Purpose

This project was created as a portfolio-ready demonstration of an **end-to-end data analytics workflow in Power BI**, from raw data preparation to interactive dashboard development and insight generation.

If you find the project useful, consider giving the repository a ⭐.
