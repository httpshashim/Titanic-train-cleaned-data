# 🛳️ Titanic Dataset – Data Cleaning & Exploratory Data Analysis (EDA)

This project was completed as part of my Data Science Internship at **Prodigy InfoTech**. The aim is to clean the dataset and perform exploratory data analysis (EDA) to find patterns and insights using the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic/data).

---

## 📌 Objective

> **Task 2**: Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.

---

## 📁 Files in this Repository

| File Name              | Description |
|------------------------|-------------|
| `titanic_cleaned.csv`  | Cleaned version of the Titanic dataset |
| `titanic_charts.gsheet` or `.xlsx` | Google Sheets/Excel file with pivot tables and charts |
| `README.md`            | Project summary and documentation |
| `changelog.txt`        | Step-by-step record of what was done during cleaning and EDA |

---

## 🧹 Data Cleaning Steps

- Replaced all blank cells with `"null"` for consistency
- Extracted only the numeric part of mixed-format ticket values using `REGEXEXTRACT()` and `IFERROR()`
- Detected duplicate `PassengerId`s using `COUNTIF()`
- Split the `Name` column into:
  - **Last Name** (e.g., Braund)
  - **Title + Full Name** (e.g., Mr. Owen Harris)

---

## 📊 Exploratory Data Analysis (EDA)

### Charts Created:
- ✅ Gender distribution (Bar Chart & Pie Chart)
- ✅ Passenger class distribution
- ✅ Age distribution (Histogram)
- ✅ Survival rate by gender and class (Stacked Bar Chart)
- ✅ Average fare by class

### Tools Used:
- ✅ Google Sheets (Formulas, Pivot Tables, Charts)
- ✅ Functions used: `IF`, `COUNTIF`, `REGEXEXTRACT`, `IFERROR`, `SPLIT`

---

## 🔍 Key Insights

- **Females** had a much higher survival rate than **males**
- **1st Class** passengers were more likely to survive than those in 2nd or 3rd class
- Most **3rd Class male passengers** did not survive
- **Children** (especially in 1st or 2nd class) had relatively better chances of survival
- **Fare** was positively correlated with survival

---

## 🛠️ Future Improvements
- Use Python (Pandas/Matplotlib) or Tableau for advanced visualizations
- Perform correlation analysis between numeric features
- Predict survival using classification models (e.g., Decision Trees)

---

## 🙌 Acknowledgements

- [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- [Prodigy InfoTech](https://prodigyinfotech.dev/) – Internship Provider

---

## 📬 Contact

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/mohamed-hashim2005/) for feedback or collaboration!
