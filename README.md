# 📊 Student Performance Prediction System

A machine learning project that predicts student performance (Pass/Fail) using study hours, attendance, past exam scores, parental education level, internet access, and extracurricular activities.  
This project leverages **Logistic Regression** for classification and demonstrates preprocessing, model training, and evaluation with detailed metrics.

---

## 📂 Project Files
- `stu.ipynb` → Jupyter Notebook containing the full workflow 

---

## 📑 Dataset Overview
The dataset includes the following features:
- **Study_Hours_per_Week**
- **Attendance_Rate**
- **Past_Exam_Scores**
- **Parental_Education_Level**
- **Internet_Access_at_Home**
- **Extracurricular_Activities**
- **Final_Exam_Score**
- **Pass_Fail (Target Variable)**

---

## ⚙️ Workflow
1. **Data Preprocessing**
   - Dropped irrelevant columns (`Student_ID`)
   - Encoded categorical variables using `pd.get_dummies`
   - Mapped target labels (`Pass` → 1, `Fail` → 0)
   - Train-test split with stratification
   - Feature scaling using `StandardScaler`

2. **Model Training**
   - Logistic Regression (`max_iter=1000`)
   - Fit on scaled training data

3. **Evaluation**
   - Confusion Matrix
   - Classification Report
   - Accuracy Score
   - Precision
   - Recall
   - F1-Score

---

## 📈 Results

### ✅ Accuracy : 0.9788732394366197


### 🔹 Confusion Matrix

<img width="1410" height="1266" alt="Screenshot 2026-07-22 221005" src="https://github.com/user-attachments/assets/afc743e9-c3ae-4b53-bdc5-5a326f519be6" />

