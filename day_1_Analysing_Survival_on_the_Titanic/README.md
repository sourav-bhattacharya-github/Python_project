# Day 1: Analysing Survival on the Titanic

Welcome to **Project Day 1** of the _Twenty Projects in Twenty Days_ series. In this project, you’ll explore the iconic **Titanic dataset**, learning how to perform **Exploratory Data Analysis (EDA)** and understand the key factors influencing survival aboard the RMS Titanic.

---

## 📝 Table of Contents

- [Objective](#objective)
- [Dataset Overview](#dataset-overview)
- [Setup](#setup)
- [Project Structure](#project-structure)
- [Steps to Approach](#steps-to-approach)
- [Key Learnings](#key-learnings)
- [Pro Tips & Best Practices](#pro-tips--best-practices)
- [Possible Extensions](#possible-extensions)
- [Real-World Relevance](#real-world-relevance)
- [Acknowledgements](#acknowledgements)

---

## Objective

Explore and analyze Titanic passenger data to understand the patterns between personal attributes (age, gender, class, fare, etc.) and survival outcomes. Learn how to:

- Load, inspect, and clean real-world tabular data
- Use data visualization to uncover insights
- Transform and engineer useful features for further modeling

---

## Dataset Overview

Typically, the dataset includes:

- **PassengerId** – Unique passenger identifier
- **Survived** – Survival status (0 = No, 1 = Yes)
- **Pclass** – Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**, **Sex**, **Age**, **SibSp**, **Parch**, **Ticket**, **Fare**, **Cabin**, **Embarked**

These fields allow analysis of demographics, fare class, family relations, and boarding location as factors in survival.

---

## Setup

Ensure you have the following installed:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```
