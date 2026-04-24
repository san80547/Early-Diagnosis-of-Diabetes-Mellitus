# 🩺 Early Diagnosis of Diabetes Mellitus: A Comparative study of Machine Learning Models for Clinical Decision Support.
 

## 📌 Project Overview

This project focuses on the **early detection of Diabetes Mellitus** using machine learning techniques applied to multiple healthcare datasets. By combining clinical and symptomatic data, the system aims to improve prediction accuracy and support early-stage diagnosis.

The project demonstrates a complete **end-to-end data science pipeline**, including:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training and comparison
* Performance evaluation and visualization

---

## 🎯 Objectives

* Detect diabetes at an early stage using clinical indicators
* Compare multiple machine learning models
* Analyze feature importance for medical insights
* Build a reproducible and interpretable pipeline

---

## 📊 Datasets Used

This project integrates three datasets:

1. **Pima Indians Diabetes Database**
2. **Frankfurt Hospital Diabetes Dataset**
3. **Diabetes Risk Prediction Dataset (Mendeley)**

### Key Features:

* Glucose
* BMI (Body Mass Index)
* Age
* Insulin
* Blood Pressure
* Skin Thickness
* Symptoms (Polyuria, Polydipsia, Weakness, etc.)

---

## 🧹 Data Preprocessing

* Removed duplicate records
* Handled missing values (replaced zeros with median values)
* Encoded categorical variables using Label Encoding
* Standardized features using `StandardScaler`

---

## 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Distribution plots for clinical features
* Correlation heatmap
* Symptom frequency analysis
* Class balance visualization
* Bivariate analysis (Glucose vs Outcome, BMI vs Glucose)
* Outlier detection using boxplots

---

## 🤖 Machine Learning Models

Three models were trained and compared:

* 🌲 Random Forest Classifier
* ⚙️ Support Vector Machine (SVM)
* 📉 Logistic Regression

---

## 📊 Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Curve
* Confusion Matrix

---

## 🏆 Results

* Random Forest showed strong performance with high accuracy and interpretability
* Feature importance analysis highlighted **Glucose, BMI, and Age** as key predictors
* ROC curves demonstrated model effectiveness in classification tasks

---

## 📉 Visual Outputs

The project generates:

* Clinical distribution plots
* Correlation heatmap
* Symptom analysis charts
* ROC-AUC curve
* Feature importance graph
* Confusion matrix visualization

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/diabetes-early-detection.git
cd diabetes-early-detection
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the script or notebook:

```bash
python main.py
```

---

## 📁 Project Structure

```
├── data/
│   ├── raw datasets
│   ├── cleaned datasets
├── outputs/
│   ├── plots (EDA, ROC, feature importance)
├── notebooks/
│   └── Early Diagnosis of Diabetes Mellitus.ipynb
├── src/
│   └── main.py
├── README.md
└── requirements.txt
```

---

## 🔍 Key Insights

* Glucose level is the most influential factor in diabetes prediction
* Combining datasets improves generalization
* Early-stage symptoms significantly contribute to prediction accuracy

---

## ⚠️ Limitations

* Dataset size may limit generalization
* Some medical values are imputed (not real measurements)
* Model performance depends on data quality

---

## 🔮 Future Improvements

* Use deep learning models (ANN, CNN)
* Deploy as a web application (Flask/Streamlit)
* Integrate real-time health monitoring data
* Apply hyperparameter tuning for optimization

---

## 👨‍💻 Author

Sandeep

---

