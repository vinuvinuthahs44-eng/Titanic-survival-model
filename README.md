
🚢 Titanic Survival Prediction Model

📌 Project Overview
This project predicts whether a passenger survived the Titanic disaster using Machine Learning. It uses classification algorithms and exploratory data analysis to understand survival patterns.

---

## 📊 Dataset
- Source: Kaggle Titanic Dataset
- Features used:
  - Pclass
  - Sex
  - Age
  - SibSp
  - Parch
  - Fare

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)
- Survival distribution visualization
- Survival based on:
  - Passenger class
  - Gender
  - Age
- Missing value handling

---

## 🤖 Model Building
Models used:
- Logistic Regression
- Random Forest Classifier

Steps:
1. Data cleaning
2. Feature selection
3. Train-test split
4. Model training

---

## 📈 Results
- Random Forest gave better performance than Logistic Regression
- Key insights:
  - Females had higher survival rates
  - Higher class passengers survived more
  - Younger passengers had slightly better chances

---

## 📊 Evaluation Metrics
```python
from sklearn.metrics import classification_report, confusion_matrix
