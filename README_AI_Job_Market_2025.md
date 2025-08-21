
# 📘 AI Job Market & Salary Analysis 2025

🚀 _Exploratory Data Analysis (EDA) project to uncover salary trends, skill demand, and geographic hiring patterns in the AI job market._

📍 **Author**: Lauris Olivares  
🛠️ **Tools**: Python, Pandas, Seaborn, Matplotlib, Google Colab  
📁 **Dataset**: [Kaggle - AI Job Market & Salary Analysis 2025](https://www.kaggle.com/datasets/)  
📅 **Timeframe**: April 2025  
🌍 **Scope**: Global (USA, UK, Germany, India, Canada, etc.)

---

## 📑 Table of Contents

1. [Objectives](#objectives)
2. [Project Scope](#project-scope)
3. [Why This Matters](#why-this-matters)
4. [Data Cleaning & Transformation](#data-cleaning--transformation)
5. [Visual Insights](#visual-insights)
   - [Top AI Skills](#top-ai-skills)
   - [Job Distribution by Country and Experience](#job-distribution)
   - [Salary Ranges by Experience and Country](#salary-insights)
6. [My Skills vs. Market](#my-skills-vs-market)
7. [Conclusions](#conclusions)
8. [Next Steps](#next-steps)
9. [Gallery](#gallery)

---

## 🎯 Objectives

- Practice core components of the ETL process (mainly **Extract** and **Transform**).
- Clean, standardize, and enrich the dataset.
- Analyze AI job trends (salary, skills, seniority).
- Build clear visualizations for storytelling.
- Host on GitHub and run on Google Colab.

---

## 📌 Project Scope

**Dataset**: Kaggle AI job postings  
**Coverage**: Up to April 2025  
**Geographic**: Global (top 5 countries by demand)

This scope helps answer:

- 🧠 What are the most requested AI skills?
- 🌍 Where are jobs concentrated?
- 💰 How do salaries vary by experience and region?

---

## 💡 Why This Matters

In today’s data-driven world, extracting insights from raw job data empowers both professionals and recruiters to **navigate the landscape confidently**.

This project simulates real-world data tasks expected from **Data Engineers and Analysts**, including:

- Structuring workflows
- Cleaning inconsistent inputs
- Deriving strategic insights

---

## 🧹 Data Cleaning & Transformation

The dataset was cleaned by:

- Removing duplicates and nulls
- Standardizing categorical variables (experience, type, size)
- Splitting multi-skill fields
- Preparing for grouped visualizations

---

## 📊 Visual Insights

### 🔝 Top AI Skills

![Top 10 AI Skills](./outputs/top_10_ai_skills.png)

**Key Insights**:
- Python is the most dominant AI skill, followed by SQL.
- Deep learning tools (TensorFlow, PyTorch) and orchestration (Kubernetes) are heavily valued.
- Git, Linux, GCP, and Java remain highly relevant in backend AI pipelines.

---

### 🌍 Job Distribution

![AI Jobs by Country & Experience](./outputs/ai_jobs_by_country_exp.png)

**Insights**:
- The US shows strong demand across all experience levels.
- India leads in entry-level roles, ideal for new graduates or early professionals.
- UK and Switzerland are more focused on experienced or senior candidates.

---

### 💸 Salary Insights

#### Experience Level

![Salary by Experience](./outputs/ai_salary_range_by_experience.png)

**Insights**:
- Salaries rise sharply with seniority.
- Mid-level roles already offer moderate to high salaries in most regions.
- Entry-level salaries cluster around the moderate range.

#### By Country

![Salary by Country](./outputs/ai_salary_range_by_top_5_countries.png)

**Insights**:
- US and Switzerland offer the highest AI salaries.
- India and Germany lean toward moderate salary ranges.
- UK shows a broader range, likely due to more diverse roles.

#### Combined Distribution

![Jobs by Country and Salary](./outputs/ai_jobs_Count_by_country_and_salary.png)

**Insights**:
- US has the most jobs in the high-salary bracket.
- India dominates job volume but most are in moderate or low ranges.
- Canada offers a balanced spread of salary tiers.

---

## 💻 My Skills vs Market

| Rank | Skill       | Demand | My Skill Level     |
|------|-------------|--------|---------------------|
| 1    | Python      | High   | ✅ Advanced         |
| 2    | SQL         | High   | ✅ Intermediate     |
| 3    | TensorFlow  | High   | ❌ Not started      |
| 4    | Kubernetes  | High   | 🟡 Learning         |
| 5    | PyTorch     | High   | ❌ Not started      |
| 6    | Scala       | Mid    | ❌ Not started      |
| 7    | Linux       | Mid    | ✅ Advanced         |
| 8    | Java        | Mid    | ❌ Not started      |
| 9    | Git         | Mid    | ✅ Comfortable      |
| 10   | GCP         | Mid    | ✅ Course completed |

This comparison helps plan **my next learning steps**.

---

## 📌 Conclusions

The EDA reveals a clear picture:

- Strong AI job market growth in the US, India, and UK.
- Demand varies significantly by role, region, and experience.
- Key tech stack: Python, SQL, TensorFlow, and GCP.

**This type of analysis is especially useful for job seekers and data professionals (myself included)** who want to identify where their skills are most needed and what tools to focus on.

---

## 🔄 Next Steps

✔️ Deepen knowledge in PyTorch, TensorFlow, and Scala  
✔️ Start building pipelines or simple ETL with real-world data  
✔️ Use Airflow or Prefect for orchestration  
✔️ Begin web scraping or API data ingestion  
✔️ Explore BigQuery or AWS Athena for querying at scale

---

## 🖼️ Result Gallery

| Chart | Description |
|-------|-------------|
| 📊 Top Skills | ![Top Skills](./outputs/top_10_ai_skills.png) |
| 🌍 Job by Experience & Country | ![Country-Experience](./outputs/ai_jobs_by_country_exp.png) |
| 💰 Salary by Country | ![Salary Country](./outputs/ai_salary_range_by_top_5_countries.png) |
| 💼 Salary by Experience | ![Salary Exp](./outputs/ai_salary_range_by_experience.png) |
