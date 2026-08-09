# 📊 Social Media vs Mental Health

## Overview
This project analyzes the relationship between **social media engagement** and **psychological outcomes** across different demographics. Using **SAP Analytics Cloud (SAC)**, the study explores how average daily time spent on platforms like Instagram, Facebook, Twitter, and YouTube correlates with mental health indicators such as distraction, anxiety, restlessness, sleep issues, and social comparison.

---

## 🎯 Objectives
- Examine demographic differences (age, gender, occupation status) in social media usage.
- Analyze correlations between **average daily time spent** and mental health indicators.
- Identify high‑risk groups (students, salaried workers, retired individuals).
- Use SAC’s visualization and predictive tools to uncover trends and forecast outcomes.

---

## 📂 Dataset
- **Source:** Kaggle – *Social Media vs Mental Health dataset*
- **Size:** 470 rows × 17 columns
- **Features:**
  - Demographics: Age, Gender, Occupation, Relationship Status
  - Measures: Average Time Spent, Distraction Likelihood, Restlessness, Anxious Thoughts, Depression Ratio, Sleep Issues, Social Comparison Orientation, etc.
- **Preprocessing:**
  - Converted age and time values into consistent formats
  - Removed irrelevant columns
  - Created calculated dimensions (e.g., Age Range buckets)

---

## ⚙️ Implementation (SAP Analytics Cloud)
- Imported dataset into SAC Modeler
- Defined dimensions: Age Range, Gender, Occupation, Relationship Status, Social Media Use
- Built measures: Average Time Spent, Anxiety, Depression Ratio, Sleep Issues, etc.
- Designed dashboards with:
  - **Demographic Analysis** (usage by age, gender, occupation)
  - **Mental Health Correlation** (time spent vs psychological outcomes)

---

## 📊 Visualizations
- **Bar Charts:** Average time spent per age range, anxious thoughts per social media use
- **Grouped Bar Charts:** Comparison of users vs non‑users across mental health indicators
- **KPI Cards:** Quick metrics (e.g., distraction likelihood, depression ratio)
- **Bubble Charts:** Validation seeking behavior by age/gender
- **Smart Predict & Forecasting:** Future trends in social media usage and mental health outcomes

---

## 🔑 Key Insights
- **18–24 age group** shows the highest average time spent on social media.
- **Female college students** recorded the most engagement and higher mental health challenges.
- Heavy users reported **greater distraction, restlessness, anxious thoughts, and sleep issues**.
- Predictive modeling suggests these trends will continue, especially among younger demographics.

---

## 🚀 Future Enhancements
- Expand dataset with more diverse demographics
- Integrate machine learning models for deeper predictive analysis
- Compare across different social media platforms
- Explore interventions for reducing negative psychological outcomes

---

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/social-media-vs-mental-health.git
