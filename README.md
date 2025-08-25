<img width="1563" height="617" alt="image" src="https://github.com/user-attachments/assets/5da8b038-3e65-4c7f-9639-f2c96af25129" />
.

# 🚢 Titanic Survival Prediction

A Machine Learning project that predicts passenger survival on the Titanic dataset using **Logistic Regression**.  
This project was developed during my **Data Science Internship at Codenscious Technologies**.

---

## 📌 Project Overview
The Titanic dataset is a classic beginner-friendly dataset widely used for classification problems.  
The goal of this project is to build a predictive model that determines whether a passenger survived or not, based on features such as age, gender, class, and more.

---

## 📊 Dataset
- **Source:** [Kaggle – Titanic Dataset](https://www.kaggle.com/c/titanic)  
- **Rows:** 891  
- **Columns:** 12  

Key Features:
- `Pclass` – Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- `Sex` – Gender of passenger  
- `Age` – Age in years  
- `SibSp` – Number of siblings/spouses aboard  
- `Parch` – Number of parents/children aboard  
- `Fare` – Passenger fare  
- `Embarked` – Port of embarkation  

---

## ⚙️ Tech Stack & Tools
- **Python**  
- **Pandas, NumPy** – Data handling & preprocessing  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning model (Logistic Regression)  
- **Jupyter Notebook** – Development environment  

---

## 🔎 Exploratory Data Analysis (EDA)
- Checked for **missing values** (Age, Embarked columns).  
- Visualized survival rates by **gender, class, and age groups**.  
- Correlation analysis between features & survival outcome.  

Example:  
- Females had a much higher survival rate than males.  
- Passengers in **1st class** had better chances of survival compared to 2nd & 3rd class.  

---

## 🤖 Model Development
- **Model Used:** Logistic Regression  
- **Data Split:** 80% training, 20% testing  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score  

### ✅ Results:
- Logistic Regression Model achieved **83% accuracy** on test data.  

---

## 📈 Visualizations
- Survival distribution across genders  
- Age distribution of survivors vs non-survivors  
- Heatmap of feature correlations  


