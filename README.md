# 🚗 Audi Car Price Prediction

## 📌 Project Overview

This project focuses on predicting the selling price of Audi cars using supervised regression techniques.

The objective is to build and compare multiple regression models to accurately estimate vehicle prices based on various features.

This project demonstrates a complete end-to-end regression pipeline including data cleaning, feature engineering, model training, and evaluation.

---

## 🎯 Business Problem

Accurate car price prediction helps:

- Buyers evaluate fair market value
- Sellers set competitive prices
- Dealerships optimize inventory pricing
- Improve decision-making using data

The goal is to predict the **car price** based on vehicle attributes.

---

## 📊 Dataset

**Dataset Name:** Audi Cars Dataset  

The dataset includes features such as:

- Model
- Year
- Engine size
- Fuel type
- Transmission
- Mileage
- Tax
- MPG
- Price (Target Variable)

**Target Variable:**  
`price` → Continuous numerical value

---

## ⚙️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧠 Machine Learning Pipeline

### 1️⃣ Data Preprocessing
- Handling missing values
- Removing outliers using IQR method
- Encoding categorical variables
- Feature scaling
- Train/Test split

### 2️⃣ Models Implemented

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### 3️⃣ Evaluation Metrics

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📈 Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Outlier Removal
5. Feature Engineering
6. Model Training
7. Model Evaluation
8. Model Comparison

---

## 📊 Key Results

- Random Forest showed superior performance compared to Linear Regression
- Outlier removal improved overall model accuracy
- Tree-based models captured nonlinear relationships effectively
- R² score demonstrated strong explanatory power

---

## 🚀 How to Run the Project

1️⃣ Clone the repository:

```

git clone [https://github.com/your-username/Machine-Learning-Projects.git](https://github.com/your-username/Machine-Learning-Projects.git)

```

2️⃣ Navigate to the regression folder:

```

cd regression-audi-prices

```

3️⃣ Install required dependencies:

```

pip install -r requirements.txt

```

4️⃣ Run the notebook:

```

jupyter notebook audi_car_price_prediction.ipynb


```

## 📁 Project Structure

```
regression-audi-prices/
│
├── audi_car_price_prediction.ipynb
├── dataset/
└── README.md

```


## 🔎 Future Improvements

- Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
- Feature importance analysis
- Cross-validation for robust evaluation
- Try Gradient Boosting / XGBoost
- Deploy the model using Streamlit or Flask

---

## 🤝 Contributors
- Zeinab Ahmed
- Ibrahim Hamdy
