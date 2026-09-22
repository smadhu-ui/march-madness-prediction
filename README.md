# 🏀 March Metrics | March Madness Prediction

### Brandeis Datathon 2026

> **Predicting March Madness Through Data & Analytics**

A machine learning project developed for the **Brandeis Datathon 2026** to predict NCAA March Madness tournament outcomes and identify the key factors associated with tournament success.

---

## 📌 Project Overview

March Madness is known for its unpredictability. While higher-seeded teams often perform well, upsets make tournament outcomes difficult to predict.

Our goal was to use **historical tournament data, team performance metrics, and machine learning** to answer two key questions:

- Can we predict NCAA tournament outcomes using historical team performance?
- What factors are most important in determining tournament success?

---

## 🎯 Problem & Approach

We combined multiple datasets containing team statistics and performance metrics.

Our workflow included:

- Cleaning and preparing historical tournament data
- Removing potential data leakage
- Creating matchup-level difference features (**Team A – Team B**)
- Analyzing historical seed performance
- Investigating tournament upset patterns
- Training and comparing classification models
- Using model-predicted probabilities to generate tournament predictions

---

## 📊 Exploratory Analysis

### 🌱 Seed Performance

Our analysis showed that:

- Higher seeds generally achieve higher win rates
- Seeds **1–4** dominate many early tournament rounds
- Lower seeds (**10–16**) rarely advance deep into the tournament
- Seeding is important, but does not fully determine tournament outcomes

### ⚡ Tournament Upsets

One of our key findings was the level of unpredictability in March Madness:

- Approximately **28% of tournament games** in our analysis were upsets
- Mid-seed matchups showed substantial unpredictability
- Smaller seed differences tended to produce less predictable outcomes
- Larger seed gaps generally resulted in more predictable outcomes

---

## 🤖 Machine Learning Models

We developed predictive models using matchup-level features derived from historical tournament data.

| Model | Accuracy |
|---|---:|
| Logistic Regression | **71%** |
| Random Forest | **76%** |

### 🏆 Best Model — Random Forest

The **Random Forest model achieved 76% accuracy**, outperforming Logistic Regression.

Random Forest allowed us to capture more complex and non-linear relationships between team characteristics and tournament outcomes.

---

## 🔍 Key Predictive Drivers

Our model highlighted three important factors associated with tournament success:

### 🏀 Offensive Efficiency
Teams with stronger offensive performance were more likely to succeed.

### 🛡️ Defensive Strength
Strong defensive performance helped distinguish successful tournament teams.

### ⭐ Team Talent
Talent metrics provided additional predictive information beyond tournament seeding.

Overall, our analysis suggested that **efficiency and talent can provide valuable information beyond seed alone**.

---

## 🔮 2026 Tournament Predictions

Using model-predicted win probabilities along with efficiency and talent metrics, we identified the following Final Four:

| Rank | Team |
|---:|---|
| 1 | Tennessee |
| 2 | St. John's |
| 3 | Michigan State |
| 4 | Arizona |

### 🏆 Predicted Champion: Tennessee

These predictions are probabilistic and based on relationships identified from historical tournament data.

---

## 💡 Key Takeaways

- 🌱 Higher seeds perform strongly, but seed alone does not determine outcomes
- ⚡ Upsets occurred in approximately **28%** of tournament games analyzed
- 📊 Efficiency and talent provided useful information beyond seeding
- 🤖 Random Forest achieved **76% prediction accuracy**
- 🏀 Machine learning can turn historical sports data into probability-based tournament predictions

---

## 🛠️ Tools & Skills

**Programming & Analytics**

`Python` • `Pandas` • `Scikit-learn` • `Machine Learning`

**Modeling**

`Random Forest` • `Logistic Regression` • `Classification` • `Predictive Modeling`

**Data Skills**

`Data Cleaning` • `Feature Engineering` • `Exploratory Data Analysis` • `Data Visualization`

---

## 📂 Explore the Project

### 📓 Machine Learning Notebook

View the complete analysis, feature engineering, model development, evaluation, and tournament predictions:

➡️ **[View Jupyter Notebook](./march_madness_prediction.ipynb)**

### 📊 Datathon Presentation

View our final Brandeis Datathon presentation:

➡️ **[View Datathon Presentation](./March%20Metric%20(Datathon)%20(2).pdf)**

---

## 👥 Team

**Suhani Madhu**  
MS in Business Analytics  
Brandeis University

**Vaishnavi Dave**  
MS in Business Analytics  
Brandeis University

---

## 📈 Project Highlights

**76% Random Forest Accuracy** • **~28% Upset Rate** • **Final Four Predictions** • **Tennessee Predicted Champion**

---

### 🏀 From bracket chaos to data clarity — decoding March Madness with analytics.
