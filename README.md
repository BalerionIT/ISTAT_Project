# La Fertilità in Europa 🇪🇺

This project explores the **factors influencing the decision to have children** across twelve European countries. Based on a large-scale Eurostat-funded survey (76,120 respondents), it combines **descriptive statistics**, **multivariate analysis**, and **logistic regression models** to identify key drivers of fertility decisions.

> Authors:  
> Antonella Convertini & Valeria Riccardo  
> Master's Degree in Data Science for Economics – UNIMI

---

## 📌 Objectives

- Understand which factors influence the intention to have children.
- Examine how such factors vary by **gender**, **age**, and **employment**.
- Identify **policy recommendations** that could support fertility rates in Europe.

---

## 🧾 Data Source

- **Survey dataset** from [Eurostat](https://ec.europa.eu/eurostat), with respondents from 12 European countries.
- Total observations: **76,120 individuals**

---

## 📂 Project Structure


ISTAT/

├── La fertilità in Europa.pdf # Final presentation/report of findings

├── ISTAT project.R # R script used for data cleaning and modeling

└── README.md # This file


---

## 🔍 Analytical Approach

### 1. Exploratory Data Analysis (EDA)
- Demographic breakdown: gender, age, country of birth/residence
- Missing data analysis
- Cramér's V correlation analysis
- Visualization of age and fertility intent distribution

### 2. Logistic Regression Modeling
A **binary logistic regression** was applied in two phases:
- **General model** using all data
- **Gender-specific models** to highlight differences

Features grouped using **Multiple Correspondence Analysis (MCA)** into:
- 🧑‍💼 Employment and work conditions  
- ❤️ Relationship quality  
- 👶 Impact of children on lifestyle  
- 🧠 Personal values and religiosity  

---

## 📈 Key Findings

### ✅ Demographics
- Younger age groups showed higher intent to have children.
- A majority, regardless of gender, expressed a desire to become parents.

### ✅ Employment
- **Full-time employment** positively associated with fertility intentions.
- **Unemployment and job insecurity** negatively impacted willingness to have children.

### ✅ Relationship Dynamics
- **Stable relationships** (marriage/cohabitation) strongly increased fertility intent.
- **Unequal domestic labor**, especially in women, had a negative effect.

### ✅ Lifestyle Constraints
- The perception of **parenthood as a barrier** to personal goals lowered fertility intent.
- **Loneliness and lack of familial support** were particularly important for women.

### ✅ Values and Religion
- **Traditional and conservative views** (e.g., family-first ideology) correlated with higher fertility.
- **Religiosity** impacted men more than women in fertility-related choices.

---

## 📌 Conclusions

- Fertility decisions in modern Europe are influenced by **more than financial stability**.
- Emotional well-being, gender equality, and supportive social structures play a crucial role.
- Parenthood is increasingly seen as a **personal life choice** rather than a societal duty.

---

## 📢 Policy Recommendations

1. **Economic Security & Labor Stability**
   - Promote permanent job contracts and fiscal incentives.

2. **Work-Life Balance Policies**
   - Extended parental leave, affordable childcare, and flexible working hours.

3. **Support for Late Parenthood**
   - Access to fertility treatments and destigmatization of older parents.

4. **Promote Gender Equality**
   - Fair division of caregiving duties and domestic responsibilities.

---

## 🛠 Requirements

To run the analysis:

### 📦 R Dependencies

```r
install.packages("tidyverse")
install.packages("ggplot2")
install.packages("factoextra")  # for MCA
install.packages("dplyr")
install.packages("readr")
install.packages("caret")       # for logistic regression evaluation

