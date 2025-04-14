# 🧬 Cancer Prediction Using Machine Learning

## 📊 Project Overview

This project applies machine learning techniques to predict whether a tumor is benign or malignant based on features extracted from breast cancer cell images. Using logistic regression as the core model, we preprocess the data, train the classifier, and evaluate model performance on both training and test datasets. The final model is serialized using `joblib` for reuse or deployment.

---

## 🎯 Objectives

- Load and preprocess breast cancer data
- Scale the features using `StandardScaler`
- Train a **Logistic Regression** model for binary classification
- Evaluate model accuracy on training and test sets
- Save the trained model using `joblib` for future use

---

## 🧩 Dataset Information

This dataset is a well-known **Breast Cancer Wisconsin (Diagnostic) Data Set**.

### 🧾 Columns

| Feature Group     | Description                                                             |
|-------------------|-------------------------------------------------------------------------|
| `id`              | Unique identifier                                                       |
| `diagnosis`       | Target variable: B = Benign, M = Malignant                              |
| `*_mean`          | Mean values of cell nuclei measurements                                 |
| `*_se`            | Standard error of measurements                                           |
| `*_worst`         | Worst or largest value of measurements across the cell nuclei           |
| `Unnamed: 32`     | Empty column — removed during preprocessing                             |

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Scikit-learn** (`sklearn`)
- **Pandas** and **NumPy** for data handling
- **Matplotlib / Seaborn** for visualization
- **Joblib** for saving ML model

---

## ⚙️ Workflow

### 1. Load and Clean the Data
### 2. Feature Scaling
### 3. Train Logistic Regression Model
### 4. Evaluate Model Performance
### 5. Save the Model with Joblib

📈 Results
The logistic regression model achieved high accuracy on both training and test datasets.

The model is ready to be deployed for real-time cancer prediction from new patient data.

✅ Future Improvements
Apply other models like Random Forest, SVM, or XGBoost

Perform cross-validation for better generalization

Create a simple web app using Flask or Streamlit

Add confusion matrix, precision, recall, and ROC-AUC evaluation

🙌 Acknowledgment
This project is inspired by real-world medical datasets and uses the publicly available Breast Cancer Wisconsin dataset for educational purposes.

📬 Contact
Feel free to connect or raise an issue if you have feedback or want to collaborate.

✉️ your.tarikukebede200@gmail.com 
