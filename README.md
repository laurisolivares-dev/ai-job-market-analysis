## 📘 AI Job Market & Salary Analysis 2025

This project explores the Artificial Intelligence job market in 2025, focusing on salary trends, skills demand, experience levels, and geographic hiring patterns. It is an Exploratory Data Analysis (EDA) project — combining data cleaning, transformation, and visual storytelling to derive actionable insights from real-world job postings.

It is my second data project. While the first introduced me to foundational EDA, this one deepens my skills in structuring an end-to-end analysis using Pandas, visual tools, and public datasets. My goal is to keep growing toward a future role as a Data Engineer.

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

* Practice core components of the ETL process (mainly **Extract** and **Transform**) using Python and Pandas.
* Clean, standardize, and enrich data for reliable interpretation.
* Analyze job market trends such as salary range, skill demand, and experience levels.
* Build visualizations to communicate findings effectively.
* Use a cloud-based, open-source workflow with Google Colab and GitHub.

---

## 📦 Project Scope

**Dataset**: Kaggle AI job postings  
**Coverage**: Up to April 2025  
**Geographic**: Global (top 5 countries by demand)

This scope helps answer:

- 🧠 What are the most requested AI skills?
- 🌍 Where are jobs concentrated?
- 💰 How do salaries vary by experience and region?

---

## 🔧 Tools & Technologies

* **Python**: Core programming language
* **Pandas**: For cleaning, transforming, and analyzing data
* **Matplotlib & Seaborn**: To visualize job market patterns
* **Google Colab**: Online Jupyter-based development environment
* **GitHub**: Version control and project sharing
* **HTML (DataFrames)**: For styled output visualization in tables

---

## 🔎 Key Analyses Conducted

* Standardization of experience level, employment type, and company size data
* Top 10 most in-demand AI skills (based on required\_skills field)
* Distribution of AI job offers by country and experience level
* Salary range analysis categorized by percentiles (Low, Moderate, High)
* Cross-comparison of salary ranges by country and by experience

---

## 🌱 Why This Matters

In today’s data-driven world, the ability to analyze messy, real-world datasets — cleaning, transforming, and drawing meaningful conclusions — is essential for any aspiring Data Engineer.

This project demonstrates not only technical proficiency, but also data storytelling — a key skill for communicating findings in business or research environments.

> As a professional in transition, especially coming from Venezuela and rebuilding my career path in a new country, this project represents my commitment to adapting and thriving in the global data ecosystem.

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
- Switzerland  shows strong demand across all experience levels.
- The United Kingdom and The United States leads in entry-level roles, ideal for new graduates or early professionals.
- Canada maintains a balanced distribution, offering opportunities for both entry-level and experienced professionals.
- Singapore, though smaller in volume, shows notable demand for mid-level professionals.

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

---

📍 **Author**: Lauris Olivares  
🛠️ **Tools**: Python, Pandas, Seaborn, Matplotlib, Google Colab  
📁 **Dataset**: [Kaggle - AI Job Market & Salary Analysis 2025](https://www.kaggle.com/datasets/)  
📅 **Timeframe**: April 2025  
🌍 **Scope**: Global (USA, UK, Singapore, Switzerland, Canada, etc.)

🧠 *Thank you for visiting this project. You can explore the complete analysis in the main notebook or browse the exported results in the outputs folder.*  
📬 *I’m open to feedback and collaboration opportunities.*
