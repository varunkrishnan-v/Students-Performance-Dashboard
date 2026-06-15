# AI Usage Impact on Student Academic Performance | SQL & Power BI

##  Project Overview

This project analyzes the relationship between Generative AI usage and student academic performance using **SQL, MySQL, and Power BI**.

The objective is to understand how factors such as **weekly GenAI usage, prompt engineering skills, skill retention, and burnout risk** relate to changes in student GPA across different academic disciplines.

The project follows an end-to-end analytics workflow:

**Kaggle CSV → MySQL → SQL Analysis → Power BI Dashboard**

---

##  Objectives

- Analyze the impact of Generative AI usage on student academic performance.
- Compare pre-semester and post-semester GPA across different majors.
- Examine the relationship between AI usage hours and academic outcomes.
- Evaluate the influence of prompt engineering skills on GPA.
- Understand burnout risk distribution among students.
- Identify trends in AI adoption across different years of study.

---
- ##  Tools & Technologies

- **Kaggle** – Source of the dataset
- **CSV** – Raw data format
- **MySQL** – Relational database management system used for data storage and management
- **SQL** – Data querying, exploration, and KPI calculations
- **Power BI** – Dashboard development and interactive visualizations

---

##  Dataset Information

- **Source:** Kaggle
- **Format:** CSV (.csv)
- **Records:** 9,860 students
- **Key Features:**
  - Student_ID
  - Major_Category
  - Year_of_Study
  - Weekly_GenAI_Hours
  - Pre_Semester_GPA
  - Post_Semester_GPA
  - Skill_Retention_Score
  - Prompt_Engineering_Skill
  - Burnout_Risk_Level

> **Note:** The dataset is intended for educational and analytical purposes only.

---

##  SQL Analysis

The dataset was imported into MySQL and analyzed using SQL queries.

### Key SQL Functions Used

- `COUNT()`
- `AVG()`
- `ROUND()`
- `GROUP BY`

### Example Queries

#### Total Students

```sql
SELECT COUNT(*) AS Total_Students
FROM student_dataset;
