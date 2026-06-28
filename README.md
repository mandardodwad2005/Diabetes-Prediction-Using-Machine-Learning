# 🩺 Diabetes Prediction Using Machine Learning

## 📌 Overview

Diabetes is one of the most common chronic diseases worldwide, and early prediction can help people receive timely medical attention. This project focuses on building a machine learning model that predicts whether a person is likely to have diabetes based on demographic, lifestyle, and clinical health information.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, performance evaluation, and feature importance analysis.


## 🎯 Project Objective

The primary objective of this project is to develop a reliable machine learning model that can accurately predict diabetes using patient health-related data. Multiple classification algorithms were implemented and compared to identify the best-performing model.


## 📂 Dataset

The dataset contains **100,000 patient records** with **31 features**, including:

* Age
* Gender
* Ethnicity
* BMI
* Blood Pressure
* Cholesterol Levels
* HbA1c
* Glucose Levels
* Physical Activity
* Lifestyle Factors
* Family History of Diabetes

**Target Variable:**

* `diagnosed_diabetes`

  * **0** → No Diabetes
  * **1** → Diabetes


## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab


## 📊 Exploratory Data Analysis

During the analysis, the following tasks were performed:

* Checked dataset dimensions and data types
* Verified missing values and duplicate records
* Analyzed target class distribution
* Explored numerical and categorical features
* Visualized important variables using histograms
* Generated a correlation heatmap
* Performed feature encoding


## 🤖 Machine Learning Models

The following classification models were trained and evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier
* Random Forest Classifier


## 📈 Model Performance

| Model               | Accuracy     |
| ------------------- | ------------ |
| Logistic Regression | **83.98%**   |
| K-Nearest Neighbors | **80.85%**   |
| Decision Tree       | **86.23%**   |
| Random Forest       | **92.02%** ✅ |

Among all the models, the **Random Forest Classifier** achieved the highest accuracy and delivered the best overall performance.


## 🔍 Important Features

Feature importance analysis showed that the following variables had the greatest impact on diabetes prediction:

* HbA1c
* Postprandial Glucose
* Fasting Glucose
* Diabetes Risk Score
* Physical Activity
* BMI
* Triglycerides
* Insulin Level
* Age


## 🚀 How to Run the Project

1. Clone this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
Diabetes_Prediction.ipynb
```

4. Run all cells to reproduce the complete analysis and model training.


## 📌 Project Highlights

* Complete end-to-end Machine Learning workflow
* Data preprocessing and feature engineering
* Exploratory Data Analysis (EDA)
* Comparison of multiple ML algorithms
* Performance evaluation using Accuracy, Confusion Matrix, and Classification Report
* Feature Importance visualization


## 🔮 Future Improvements

Some possible enhancements for this project include:

* Hyperparameter tuning
* Cross-validation
* Model deployment using Flask or Streamlit
* Integration with a web-based user interface
* Testing advanced models such as XGBoost and LightGBM


## 👨‍💻 Author

**Mandar Dodwad**

Electronics and Computer Engineering Student

Passionate about Java, Backend Development, Machine Learning, and solving real-world problems through technology.


## ⭐ Support

If you found this project helpful, consider giving this repository a ⭐. Feedback and suggestions are always welcome!

