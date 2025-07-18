# 📊 Analyzing Students' Mental Health – SQL Project

## 👋 Overview

This project explores how the **length of stay** impacts the **mental health** of **international students**, using structured SQL queries to extract insights from a student survey dataset. 

It was completed as part of the [DataCamp Data Analyst Track](https://www.datacamp.com/), and executed in a notebook-based SQL environment.

---

## 🎯 Objective

The goal of this analysis was to investigate whether **duration of stay** influences mental health indicators — specifically:

- **PHQ-9** (Depression Test)
- **SCS** (Social Connectedness Scale)
- **ASISS** (Acculturative Stress)

We grouped students by their `stay` length and returned aggregate measures of their mental health scores.

---

## 🔍 Key Insights

- There appears to be a **correlation between longer stays and improved scores** across certain tests (notably SCS and PHQ).
- Students with **shorter stays** tended to have **higher average acculturative stress** and **lower social connectedness**, suggesting challenges with adjustment.
- Conversely, students who stayed **longer** generally reported **lower depression and stress scores**, indicating possible emotional adaptation over time.

These patterns can inform **mental health policy** and **support services** tailored to international students during critical early months of their relocation.

---

## 🛠️ Tools & Skills Demonstrated

### 📌 Technical Skills

- **SQL**
  - Aggregate functions: `AVG()`, `COUNT()`, `ROUND()`
  - Filtering with `WHERE`
  - Grouping with `GROUP BY`
  - Sorting with `ORDER BY`
  - Aliasing and formatting output

- **Data Cleaning & Filtering**
  - Filtered by `inter_dom = 'Inter'` to focus on international students only
  - Rounded averages to **2 decimal places** for clear readability

### 📌 Analytical Thinking

- Used grouping logic to compare cohorts based on stay duration
- Derived quantitative insights to support qualitative assumptions about adjustment periods
- Identified potential focus areas for student wellbeing services

---

## 📁 Output Sample

| stay | count_int | average_phq | average_scs | average_as |
|------|-----------|-------------|-------------|------------|
| 10   |     1     |    13.00    |    32.00    |   50.00    |
| 6    |     3     |     6.00    |    38.00    |   58.67    |
| 2    |    39     |     8.28    |    37.08    |   77.67    |
| 1    |    95     |     7.48    |    38.11    |   72.80    |

*(Table includes only international students, grouped by `stay`, sorted descending)*

---

## 💼 About Me

**Mitchel Hand** – Aspiring Data Analyst

I'm currently developing my technical skill set through real-world projects, bootcamps, and platforms like DataCamp. I'm passionate about using data to solve meaningful problems and make evidence-based decisions.

> 💬 If you're an employer or recruiter looking for a data-driven thinker with a proactive learning mindset — I'd love to connect!

---

## 📫 Contact

- 🔗 [LinkedIn](https://www.linkedin.com/in/mitchel-hand/))
- 💼 [Portfolio](https://sites.google.com/view/mitchel-hand-portfolio/home)

---

## ✅ Status

✔️ Project Completed – Ready for review and feedback.
