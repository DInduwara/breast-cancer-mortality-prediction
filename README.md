# 🩺 Breast Cancer Mortality Prediction

This project focuses on predicting breast cancer **mortality status** (Alive = 0, Dead = 1) using structured clinical data and various machine learning classification techniques.

It is structured into three notebooks covering preprocessing, baseline models, and advanced ensemble classifiers.

---

## 📁 Notebooks Overview

### 📘 Final Python Notebook 1: Data Understanding & Preprocessing
- Loaded raw dataset and cleaned missing values
- Encoded categorical variables and handled numeric scaling
- Separated data for classification and regression tasks

### 📘 Final Python Notebook 2: Classification Models
- Implemented:
  - Naive Bayes (GaussianNB)
  - Logistic Regression
  - k-Nearest Neighbors (with tuning)
- Evaluated with confusion matrix, ROC curve, and classification metrics

### 📘 Final Python Notebook 3: Advanced Classification & Ensembles
- Implemented:
  - Decision Tree (fully grown and pruned)
  - Soft Voting Classifier (NB + LR)
  - Random Forest (bagging)
  - AdaBoost (boosting)
  - (Optional) Multilayer Perceptron (MLP)
- Regression metrics added for tree-based models
- Feature scaling and hyperparameter tuning included

---

## 📊 Evaluation Metrics
Each model is evaluated using:
- Confusion Matrix
- Classification Report (Accuracy, Precision, Recall, F1)
- ROC AUC
- MSE, MAE, and R² where applicable

---

## 📂 File Structure
/notebooks/
├── Notebook1_Preprocessing.ipynb
├── Notebook2_Classification_Basics.ipynb
├── Notebook3_Advanced_Models.ipynb

/data/
└── Prepared_Breast_Cancer_Classification.csv

/outputs/
├── *.csv (predictions)
├── *.png (plots and trees)


---

## 🔧 Technologies Used
- Python 3.x
- pandas, NumPy, matplotlib, seaborn, plotly
- scikit-learn (models, metrics, GridSearchCV)
- Google Colab + Google Drive for notebook storage

---

## ✅ Author
**Dinuka Induwara**  
2nd-Year Software Engineering Undergraduate  
Passionate about full-stack development and applied machine learning

---

## 📌 License
This project is academic coursework. Usage outside educational contexts should request permission from the author.
