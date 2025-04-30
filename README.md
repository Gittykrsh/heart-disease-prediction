# 🫀 Heart Disease Prediction using Logistic Regression

## 📌 Project Overview
This project aims to predict the likelihood of a person having heart disease using machine learning. It uses the Logistic Regression algorithm to analyze various health parameters and classify patients as either having or not having heart disease. This can be used as a decision support tool in the medical field.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python** | Core programming language |
| **Pandas** | Data manipulation & cleaning |
| **NumPy** | Numerical computations |
| **Seaborn / Matplotlib** | Data visualization |
| **scikit-learn** | ML modeling, preprocessing, and evaluation |
| **StandardScaler** | Feature normalization |
| **Logistic Regression** | ML algorithm for binary classification |

---

## 🧠 Modeling Approach

1. **Dataset Loading**: Reads `heart.csv` which includes features like age, cholesterol level, resting blood pressure, etc.
2. **Data Visualization**: Uses heatmaps, distribution plots, and boxplots for understanding data trends and outliers.
3. **Outlier Handling**: Caps extreme values using the 3 standard deviation rule to reduce model skewness.
4. **Preprocessing**:
   - Feature-label separation (`X`, `y`)
   - Feature scaling with `StandardScaler`
5. **Train-Test Split**: 75% data for training and 25% for testing using `train_test_split`.
6. **Model Training**: Trains a Logistic Regression model on preprocessed data.
7. **Model Evaluation**:
   - Accuracy Score
   - Precision, Recall, F1-Score (via Classification Report)
   - Confusion Matrix (visualized via heatmap)

---

## 🌍 Real-World Application

Cardiovascular diseases are a leading cause of mortality worldwide. Early detection is crucial. This project can serve as:
- A **low-cost screening tool** in under-equipped or remote areas
- A **support tool for doctors** to validate diagnoses
- Part of **wearable health monitoring** or mobile health apps
- A **preventive tool** for individuals to monitor health patterns over time

---

## 📊 Future Enhancements
- Implement more powerful models like Random Forest, XGBoost, or Neural Networks
- Perform cross-validation for better generalization
- Create a user-friendly **web app** using Streamlit or Flask
- Deploy the model using cloud platforms like Heroku or AWS

---

## 📁 Dataset
The dataset used is `heart.csv`, which contains labeled medical data. (Ensure to include it in your repository or provide a link to download.)

---

## ❤️ Made with love by [Shakyasimha Das]
