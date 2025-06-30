# 🧪 Titanic Dataset - Exploratory Data Analysis (Task 5)

This project presents an Exploratory Data Analysis (EDA) of the Titanic dataset using Python and Jupyter Notebook. The objective is to uncover hidden patterns and insights related to passenger survival, and to prepare the dataset for future machine learning modeling.

---

## 📊 Project Objectives

- Understand the structure and features of the Titanic dataset.
- Identify and handle missing values.
- Perform univariate and multivariate visual analysis.
- Derive key insights that influence survival outcomes.

---

## 🛠️ Tools & Technologies

- **Language:** Python 3.x
- **IDE:** Jupyter Notebook (Anaconda)
- **Libraries:**
  - `pandas` for data manipulation
  - `numpy` for numerical operations
  - `matplotlib` and `seaborn` for data visualization

---

## 📁 Files Included

| File Name                  | Description                           |
|---------------------------|---------------------------------------|
| `Titanic_EDA_Task5.ipynb` | Main Jupyter Notebook with code & graphs |
| `Titanic_EDA_Task5.pdf`   | Exported PDF version of the notebook  |
| `train.csv` (optional)    | Titanic dataset from Kaggle           |

---

## 🔍 Key Insights from EDA

- **Gender:** Female passengers had a significantly higher survival rate than males.
- **Pclass:** Passengers in 1st class were more likely to survive.
- **Fare:** Higher fare passengers had better chances of survival.
- **Age:** Younger passengers (especially children) had higher survival probability.
- **Cabin:** Dropped due to excessive missing data.

---

## 📌 Cleaning Performed

- Filled missing values in the `Age` column with median.
- Dropped `Cabin` column due to >75% missing values.
- Dropped rows with missing values in `Embarked`.

---

## 📈 Visualizations Used

- 🔥 Correlation heatmap
- 👨‍👩‍👧‍👦 Countplots (Survival vs Gender, Class)
- 📦 Boxplots (Age vs Survival)
- 📊 Histograms (Fare & Age distributions)

---

## 🚀 Future Scope

This cleaned dataset can now be used for:
- Predictive modeling using machine learning
- Classification tasks (e.g., logistic regression, decision trees)

---

## ✅ Author

**Name:** Avnish Bedi 
**Course:** B.Tech IT — Data Analytics Internship  
---

