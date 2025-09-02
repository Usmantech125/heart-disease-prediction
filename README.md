# ❤️ Heart Disease Prediction

This project predicts the presence of heart disease in a patient using machine learning models.  
It is based on the classic **UCI Heart Disease Dataset** with 13 input features.

---

## 📊 Dataset
The dataset contains the following features:

- `age`: Age of the patient  
- `sex`: Gender (1 = male, 0 = female)  
- `cp`: Chest pain type (categorical: 0–3)  
- `trestbps`: Resting blood pressure (mm Hg)  
- `chol`: Serum cholesterol (mg/dl)  
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)  
- `restecg`: Resting electrocardiographic results (0–2)  
- `thalach`: Maximum heart rate achieved  
- `exang`: Exercise-induced angina (1 = yes, 0 = no)  
- `oldpeak`: ST depression induced by exercise  
- `slope`: Slope of ST segment (0–2)  
- `ca`: Number of major vessels (0–3)  
- `thal`: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)  
- `target`: Presence of heart disease (1 = yes, 0 = no)

---

## ⚙️ Models Used
We compared the following models using **5-fold cross-validation**:

- Logistic Regression  
- Random Forest  
- XGBoost  

The best model is automatically selected based on accuracy.

---


