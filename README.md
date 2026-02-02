# 🩺 Diabetes Readmission Prediction

## 📌 Project Overview
Hospital readmissions for diabetic patients are costly and often preventable.  
This project aims to **predict whether a diabetic patient will be readmitted to the hospital** using machine learning models trained on real-world clinical data.

The solution helps healthcare providers:
- Identify high-risk patients early
- Reduce avoidable readmissions
- Improve patient outcomes and resource allocation

---

## 📊 Dataset
- **Source:** UCI Machine Learning Repository  
- **Hospitals:** 130 US hospitals  
- **Years:** 1999–2008  
- **Size:** ~100,000 patient encounters  
- **Features:** 50+ (demographics, diagnoses, lab tests, medications, visits)

### Target Variable
- `<30` → Readmitted within 30 days  
- `No / >30` → Not readmitted (converted to binary classification)

---

## ⚙️ Project Workflow
1. Data Understanding & Cleaning  
2. Missing Value Treatment  
3. Feature Engineering  
4. Exploratory Data Analysis (EDA)  
5. Class Imbalance Handling (Oversampling)  
6. Model Training  
7. Model Evaluation & Cross-Validation  
8. Model Comparison & Selection  

---

## 🧠 Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- XGBoost  
- LightGBM  
- KNN  
- AdaBoost  
- CatBoost  
- Bagging Classifier  
- Voting Classifier  
- Stacking Classifier  

---

## 🏆 Best Performing Model
### ✅ Random Forest Classifier

**Key Metrics (Test Set):**
- Accuracy: **95%**
- Precision: **93%**
- Recall: **98%**
- ROC AUC: **0.99**
- False Negatives: **~1.3%**

**Cross-Validation (5-Fold):**
- Accuracy: **93.29% ± 0.0046**
- Precision: **91.09%**
- Recall: **95.97%**
- F1-score: **93.47%**

👉 High recall ensures **very few high-risk patients are missed**, which is critical in healthcare.

---

## 📈 Visualizations
- Feature correlation heatmap  
- Outlier detection plots  
- Feature importance (Random Forest)  
- Confusion matrix  

(Additional plots available in the notebook)

---

## 🧪 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC AUC  
- False Positive %  
- False Negative %  

---

## 🚀 Business Impact
- Helps hospitals proactively identify high-risk patients  
- Reduces emergency readmissions  
- Supports data-driven clinical decision-making  

---

## ⚠️ Limitations
- Dataset may not represent all populations  
- Some features had high missing values  
- Model performance depends on data quality  

---

## 🔮 Future Improvements
- SHAP-based explainability  
- External validation datasets  
- Nested cross-validation  
- Real-time EHR integration  

---

## 📜 License
This project is for academic and educational purposes.
