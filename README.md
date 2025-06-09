# 🎓 Student Score Predictor

A machine learning project that predicts students' final exam scores (`G3`) using demographic, academic, and behavioral data.

## 📊 Dataset

- **Source:** UCI Student Performance Dataset  
- **Total Records:** 395 students  
- **Features Used:** 30+ categorical and numerical attributes  
- **Target Variable:** Final grade (`G3`)

## ⚙️ Features

- 🔄 **Preprocessing:** Encoding categorical data, handling missing values, outlier removal
- 📈 **Models Used:** Linear Regression, Ridge, Lasso  
- 🧮 **Best Performance:**  
  - R² Score: **0.72**  
  - MSE: **5.66**  
- 🔍 Feature importance analysis to understand key predictors like `G1`, `G2`, study time, etc.

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/04abhinavsharma/Student-ScorePredictor.git
   cd Student-ScorePredictor
2. Install Dependencies:
   pip install -r requirements.txt
3. Open the notebook:
   jupyter notebook student_score_predictor.ipynb

📂 Files in the Repo
student_score_predictor.ipynb: Colab notebook with full ML pipeline

student_data.csv: Cleaned dataset

requirements.txt: List of dependencies

README.md: Project overview

📌 Key Learnings
Preprocessing and feature engineering significantly impact prediction

Regularization (Ridge/Lasso) helps in controlling overfitting

Including intermediate scores (G1, G2) boosts performance by over 60%
