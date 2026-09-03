#  Social Media Impact on Teen Mental Health

A Power BI analytics project exploring how social media usage patterns relate to stress, anxiety, sleep, and addiction levels among teenagers aged 13–19.

---

##  Overview

This project analyzes survey data from 1,200 teenagers to understand the relationship between social media usage (Instagram, TikTok, or both) and key mental health and lifestyle indicators including stress, anxiety, depression, sleep, addiction, and social interaction levels.

The analysis is presented across three interactive Power BI dashboard, each focusing on a different angle of the data: an overview summary, platform-specific behavioral patterns, and mental health/lifestyle trends by age.

---

##  Objectives

- Measure overall levels of stress, anxiety, depression, and addiction among teen social media users.
- Compare behavioral and mental health differences across platforms (Instagram, TikTok, Both).
- Examine how age affects daily social media usage, stress, and sleep.
- Explore the relationship between screen time and sleep duration.
- Break down patterns by gender and social interaction level (High / Medium / Low).

---

##  Dashboard Pages

### 1. Teen Mental Health Dashboard (Overview)
High-level KPIs and filters for the full dataset.

- **Filters:** Gender, Age, Platform Usage, Social Interaction Level
- **KPIs:** Total Students (1,200), Average Stress (5.45), Average Depression (0.03), Average Anxiety (5.64)
- **Visuals:**
  - Addiction Level by Platform (bar chart)
  - Gender Distribution (donut chart — Male 51.2%, Female 48.8%)
  - Average Stress Level (gauge)
  - Total Students by Platform Usage (category comparison)

### 2. Social Media Analysis
Focuses on platform-level usage behavior.

- Social Media Hours vs. Sleep Hours (bubble chart by platform)
- Average Daily Social Media Hours by Age (line chart, ages 13–19)
- Average Addiction Level by Platform and Gender (stacked area chart)
- Total Students by Platform Usage and Social Interaction Level (100% stacked bar)

### 3. Mental Health & Lifestyle Analysis
Focuses on age-based mental health and sleep trends.

- Average Stress Level by Age (bar chart)
- Stress Level and Sleep Hours by Age (combo chart)
- Sleep Hours by Age Across Platforms (small multiples: Both / Instagram / TikTok)
- Gender × Platform Stress Level matrix (table)

---

##  Key Insights

- **Stress peaks at age 14** (average stress of 6.2), the highest across all age groups.
- **Daily social media usage** is highest among 17-year-olds (4.76 hrs) and lowest among 18-year-olds (4.24 hrs).
- **TikTok users show slightly higher average addiction levels** (5.75) than Instagram (5.67) or combined users (5.49).
- **Male TikTok users** report the highest average stress by gender/platform combination (5.80).
- Students with **high social interaction levels** make up the largest share among Instagram users (37.71%), while **low interaction** is more common among "Both" platform users.
- Sleep hours remain relatively stable (around 6.3–6.5 hrs) across ages and platforms, with modest dips corresponding to stress spikes.

---

##  Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Data modeling, DAX measures, dashboard design |
| **DAX**            | Calculated KPIs (average stress, anxiety, depression, addiction) |
| **Power Query**    | Data cleaning and transformation |

---

##  Dataset

The dataset consists of survey responses from 1,200 teenagers (ages 13–19), capturing:

- Demographics: `gender`, `age`
- Platform behavior: `platform_usage`, `daily_social_media_hours`, `social_interaction_level`
- Mental health indicators: `stress_level`, `anxiety_level`, `depression`, `addiction_level`
- Lifestyle: `sleep_hours`

---

##  Future Improvements

- Add year-over-year or longitudinal survey data to track trends over time.
- Incorporate additional variables (screen-time app category, parental controls, academic performance).
- Publish an interactive Power BI Service report link for public viewing.
- Add statistical correlation analysis (e.g., correlation between screen time and stress).

--
