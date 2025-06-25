# Diabetes-XAI-PIMA: Explainable Diabetes Risk Prediction with SHAP on PIMA Dataset

## 🧑‍⚕️ Overview
This project implements a machine learning model to predict Type 2 Diabetes using the **PIMA Indian Diabetes Dataset**, with a focus on **explainability (XAI)** using SHAP.

We go beyond basic classification by introducing:

- ✔️ Feature engineering (e.g., `Age_BMI`, `Glucose_BMI_Ratio`)
- ✔️ Hyperparameter tuning (optional step)
- ✔️ Explainable AI with SHAP for feature importance visualization
- ✔️ Error-free and scalable SHAP interpretation
- ✔️ Reproducible results for research and academic projects

---

## 📊 Dataset Used
- **Source:** [UCI Machine Learning Repository - PIMA Indians Diabetes Dataset](https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv)

---

📌 Installation & Running
Clone the repository:
git clone https://github.com/yourusername/Diabetes-XAI-PIMA.git
cd Diabetes-XAI-PIMA
(Optional but Recommended) Create a virtual environment:


python -m venv venv
source venv/bin/activate        # On Linux/Mac
venv\Scripts\activate           # On Windows
Install required libraries:


pip install -r requirements.txt
✅ Project Features
📈 Exploratory Data Analysis (EDA)

🧪 Data Cleaning and Missing Value Handling
⚖️ Class Balancing using SMOTE
🌲 Random Forest Classifier with hyperparameter tuning
📊 Performance Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC

🔎 Multiple SHAP Explainability Plots:

Beeswarm Plot
Feature Importance Bar Plot
Force / Waterfall Plot
Dependence Plot

🖥️ Running the Notebook
You can run the notebook either:
Locally using Jupyter Notebook
OR
Directly in Google Colab with this badge:


📂 Files in This Repo
pima_diabetes_rf_shap.ipynb → Full Python notebook with code, plots, and SHAP visualizations
requirements.txt → Python dependencies
README.md → Project documentation
.gitignore → Ignore unnecessary system and IDE files
LICENSE → MIT License

