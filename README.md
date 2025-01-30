# Breast Cancer Classification Using Machine Learning
This project is developed as part of my portfolio for Digital Skill Fair (DSF) 35.0 - Data Science by Dibimbing. I am using the Wisconsin Breast Cancer Diagnostic Dataset from scikit-learn, which is a classic and widely used binary classification dataset. It contains 569 instances with 30 numeric predictive attributes and a target variable indicating whether a tumor is benign (0) or malignant (1). The objective of this project is to build and evaluate machine learning models to accurately classify breast tumors using **Logistic Regression**, **Random Forest**, and **Support Vector Machine (SVM)** algorithms. You can access the dataset through this link: https://scikit-learn.org/1.5/modules/generated/sklearn.datasets.load_breast_cancer.html

## Goals
The primary goal of this project is to develop a machine learning model that can:
- To build and evaluate machine learning models for classifying breast tumors as **benign** or **malignant**.
- To identify the most important features that contribute to the classification.
- To determine the best-performing model based on accuracy and other evaluation metrics.
- To provide insights into the dataset and model performance for potential clinical use.

By achieving these goals, this project demonstrates how machine learning can improve cancer diagnosis and potentially assist radiologists and healthcare professionals in clinical decision-making.

## Dataset Description
The dataset contains the following:
- 569 instances (samples) with 30 features:
  Mean values of tumor characteristics (e.g., radius, texture, perimeter, area, etc.).
- Standard errors of these features.
  Worst values (largest or most severe) of these features.
- Target variable:
   0: Malignant (dangerous/cancerous tumors).
   1: Benign (non-dangerous/non-cancerous tumors).

## Tools and Libraries
The following tools and libraries were used in this project:
1. Python as the programming language.
2. Pandas and NumPy for data manipulation.
3. Matplotlib and Seaborn for data visualization.
4. Scikit-learn for machine learning algorithms and evaluation.
5. GridSearchCV for hyperparameter tuning
6.  StandardScaler for feature scaling

## Project Workflow
### Step 1: Data Preprocessing
- Handle missing values (if any).
- Feature Scaling (Normalization) using StandardScaler.
- Train-Test Split (80% Training, 20% Testing).

### Step 2: Exploratory Data Analysis (EDA)
- Understand the dataset through statistics and visualizations.
- Identify correlations between tumor features.
- Visualize the target variable distribution (Benign vs. Malignant).

### Step 3: Train Machine Learning Models
- Logistic Regression
- Random Forest (With Hyperparameter Tuning)
- Support Vector Machine (SVM - Linear Kernel)

### Step 4: Model Evaluation
- Evaluate models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC Curve.
- Identify the best-performing model for real-world application.

### Step 5: Visualization for Feature Importance Analysis
- Analyze which tumor characteristics contribute most to classification.
- Use Random Forest & Logistic Regression coefficients to determine important features.

### Step 6: Conclusion & Final Model Selection
- Compare model performances and determine the best model.
- Optimize using GridSearchCV for better accuracy.

## Conclusion
This project demonstrates the potential of machine learning for breast cancer classification. By using features extracted from tumor characteristics, the **Logistic Regression** model effectively distinguishes between benign and malignant cases with an accuracy of **98.25%**. While the current model shows promising results, further development and validation are necessary to ensure its reliability and potential for clinical use.

#### If you have any questions, suggestions, or feedback, please feel free to reach out to me via Email: deviadns1@gmail.com or LinkedIn: https://www.linkedin.com/in/deviandinisastro/.
