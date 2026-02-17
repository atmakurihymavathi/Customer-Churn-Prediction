# 📊 Telecom Customer Churn Prediction

## 🚀 Project Overview

This project focuses on predicting customer churn in the telecom industry using Machine Learning techniques.

Customer churn occurs when customers stop using a company's services. Predicting churn helps businesses improve retention strategies and reduce revenue loss.

---

## 📂 Project Structure

```
├── Scripts/        # Python scripts for data processing and model training
├── icons/          # Icons and assets used in the project
├── output/         # Generated visualizations and model results
├── data.csv        # Dataset used for analysis
└── README.md       # Project documentation
```

---

## 📌 Problem Statement

Telecom companies face high customer churn rates due to competitive markets.

The goal of this project is to:
- Analyze customer behavior
- Identify factors influencing churn
- Build classification models
- Predict whether a customer will churn or not

---

## 📊 Dataset Description

The dataset includes:

- Customer demographics
- Service subscription details
- Contract type
- Payment methods
- Monthly and total charges
- Tenure
- Churn label (Yes/No)

---

## 🔍 Exploratory Data Analysis (EDA)

Key observations:

- Customers with Month-to-Month contracts have higher churn.
- Higher monthly charges increase churn probability.
- Customers without tech support or online security are more likely to churn.
- New customers (low tenure) show higher churn rates.

Visualizations are available in the `output/` folder.

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- K-Nearest Neighbors
- Naive Bayes
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- Voting Classifier (Final Model)

---

## 🏆 Final Model

The Voting Classifier combining:
- Gradient Boosting
- Logistic Regression
- AdaBoost

achieved the best performance after cross-validation.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Model Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision & Recall
- Cross Validation

---

## 🔮 Future Improvements

- Hyperparameter tuning
- Feature engineering
- Handling class imbalance
- Model deployment using Flask or Streamlit
- Real-time dashboard integration

---

## 👩‍💻 Author

Hymavathi Atmakuri  
Data Science & Machine Learning Enthusiast  

---

⭐ If you found this project useful, feel free to star the repository!
