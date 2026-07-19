# 🏠 House Price Prediction using Machine Learning

## 📌 Alfido Tech Machine Learning Internship Project

This project focuses on building a Machine Learning regression model to accurately predict house prices based on various property features. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model comparison, evaluation, and prediction.

---

# 📖 Project Overview

House price prediction is an important regression problem in machine learning. In this project, different regression algorithms are compared to determine the most accurate model for predicting residential property prices.

The complete workflow includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Handling Missing Values
- Feature Engineering
- Encoding Categorical Features
- Feature Scaling
- Log Transformation
- Model Training
- Model Evaluation
- Residual Analysis
- Model Saving
- Price Prediction

---

# 📂 Dataset Information

- **Dataset Size:** 4600 Records
- **Total Features:** 18
- **Target Variable:** Price

### Features

- Bedrooms
- Bathrooms
- Sqft Living
- Sqft Lot
- Floors
- Waterfront
- View
- Condition
- Sqft Above
- Sqft Basement
- Year Built
- Year Renovated
- Street
- City
- StateZip
- Country

---

# 📊 Exploratory Data Analysis

EDA performed in this project includes:

- Dataset Information
- Missing Value Analysis
- Price Distribution
- Correlation Analysis
- Feature Relationships
- Data Cleaning
- Feature Transformation

---

# ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

- Handling Missing Values
- Label Encoding
- Standard Scaling
- Log Transformation of Target Variable
- Train-Test Split

---

# 🤖 Machine Learning Models

The following regression models were trained and evaluated:

1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor

---

# 📈 Model Performance

| Model | RMSE | MAE |
|-------|------|------|
| Linear Regression | 1.407601 | 0.430468 |
| Random Forest ⭐ | **1.395156** | **0.331387** |
| Gradient Boosting | 1.396506 | 0.475364 |

### ✅ Best Model

**Random Forest Regressor**

---

# 📉 Residual Analysis

Residual analysis was performed using:

- Residual Scatter Plot
- Residual Distribution Plot

The residuals were centered around zero, indicating a good overall model fit with a few outliers.

---

# 🔮 Sample Prediction

```python
prediction = model.predict(new_house)

print(prediction)
```

### Predicted House Price

```
310998.43
```

---

# 💻 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

---

# 📁 Project Structure

```
House-Price-Prediction/
│
├── HousePrediction.ipynb
├── data.csv
├── house_price_model.pkl
├── requirements.txt
├── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/ankitbungla20-student/House-Price-Prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook HousePrediction.ipynb
```

---

# 🧪 How to Make Predictions

```python
import joblib

model = joblib.load("house_price_model.pkl")

prediction = model.predict(X_test.iloc[[0]])

print(prediction)
```

---

# 📌 Project Highlights

- End-to-End Machine Learning Pipeline
- Feature Engineering
- Model Comparison
- Performance Evaluation
- Residual Analysis
- Model Serialization
- Prediction Pipeline

---

# 📚 Internship Task Deliverables

✔ Exploratory Data Analysis

✔ Feature Engineering

✔ Missing Value Handling

✔ Feature Scaling

✔ Log Transformation

✔ Multiple Regression Models

✔ Model Comparison

✔ RMSE & MAE Evaluation

✔ Residual Analysis

✔ Model Saving

✔ Prediction Example

---

# 👨‍💻 Author

**Ankit Bungla**

Machine Learning Intern

**Alfido Tech**

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
