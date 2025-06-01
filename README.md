# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project is part of **Task 02** from SkillCraft Technology, focusing on data cleaning and exploratory data analysis (EDA) using the **Titanic dataset**. The goal is to explore relationships between variables, identify patterns, and discover insights from the data.

---

## 📂 Dataset Information

- **Dataset:** Titanic - Machine Learning from Disaster
- **Source:** Seaborn's built-in dataset (or Kaggle: https://www.kaggle.com/c/titanic/data)
- **Features include:**
  - `survived`, `pclass`, `sex`, `age`, `sibsp`, `parch`, `fare`, `embarked`, etc.

---

## 📌 Objectives

- Clean the dataset by handling missing values and dropping irrelevant features.
- Explore data visually to uncover insights.
- Understand the impact of features like gender, class, and age on survival.

---

## 🧪 Tasks Performed

### ✅ Data Cleaning
- Dropped irrelevant columns: `deck`, `embark_town`
- Handled missing values:
  - `age` filled with median
  - `embarked` filled with mode

### 📊 Exploratory Data Analysis (EDA)
- Survival distribution
- Survival by gender
- Age distribution of passengers
- Survival by passenger class
- Correlation heatmap
- Pairplot of numeric features by survival outcome

---

## 🖼️ Visualizations

- **Bar plots** for survival count, gender, and class
- **Histogram** for age distribution
- **Heatmap** showing feature correlations
- **Pairplot** comparing numerical features by survival outcome

---

## 📌 Key Insights

- Women had a significantly higher survival rate than men.
- Passengers in higher classes (1st class) had better survival odds.
- Younger passengers (children) had better chances of survival.
- Fare and class showed moderate correlation with survival.

---

## 🛠️ Tech Stack

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook
