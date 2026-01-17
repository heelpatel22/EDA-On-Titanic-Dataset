# 🛳️ Titanic Survival Analysis — Exploratory Data Analysis (EDA)

This project performs an in-depth **Exploratory Data Analysis (EDA)** on the famous **Titanic Dataset**, exploring survival patterns based on passenger demographics, ticket class, family structure, and more.

---

## 🎯 Objectives

The analysis aims to:

- Understand the distribution of key passenger features
- Explore the relationships between **survival** and:
  - Gender
  - Passenger Class
  - Age
  - SibSp (Siblings/Spouses)
  - Parch (Parents/Children)
  - Embarked location
- Identify data quality issues (e.g., missing values)
- Visualize insights using charts and statistical summaries

---

## 🧠 Dataset Information

This project uses the **Titanic Passenger Data** typically found on Kaggle:

Feature | Description
--- | ---
Survived | Survival (0 = No, 1 = Yes)
Pclass | Passenger Class (1/2/3)
Name | Name
Sex | Male/Female
Age | Age in years
SibSp | # of siblings/spouses aboard
Parch | # of parents/children aboard
Ticket | Ticket number
Fare | Ticket fare
Cabin | Cabin number
Embarked | Port of Embarkation (C, Q, S)

---

## 🔍 Key Findings & Insights

Some high-level insights uncovered in the notebook:

- **Female passengers had a much higher survival rate** compared to males.
- **1st class passengers** were significantly more likely to survive.
- Many **Age values were missing**, requiring careful handling.
- Having **family members onboard** influenced survival chances.
- **Embarkation point (S, C, Q)** showed noticeable survival differences.

> Detailed visualizations and statistics are available in the notebook.

---

## 📊 Visualizations Used

The notebook includes:

- Count plots
- Histograms
- KDE plots
- Boxplots
- Crosstabs & heatmaps
- Pie charts (survival proportions)

---

## 🛠️ Technologies & Libraries

The following libraries were used:

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
