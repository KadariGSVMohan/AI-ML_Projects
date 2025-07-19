
---

# 🫀 Heart Disease Prediction App

A **Streamlit-based web application** that predicts the likelihood of heart disease using patient data and a trained **Logistic Regression model**. This application also generates a personalized **PDF health report**.

---

## 🚀 Features

* 🧠 **Heart Disease Risk Prediction** using 13 clinical features
* 📊 Based on the **UCI Heart Disease Dataset**
* 📋 Interactive and user-friendly input form
* 📄 **Auto-generated downloadable PDF report**
* 🧑‍⚕️ Health advisory based on prediction outcome
* 🧪 Model trained using **scikit-learn**

---

## 📂 Dataset Information

* **Source**: UCI Heart Disease Dataset
* **Total Records**: 303
* **Target Variable**: `target` (1 = Heart Disease, 0 = Healthy)

### 🔍 Features Used:

1. Age
2. Sex (1 = Male, 0 = Female)
3. Chest Pain Type (0–3)
4. Resting Blood Pressure (mm Hg)
5. Serum Cholesterol (mg/dl)
6. Fasting Blood Sugar > 120 mg/dl (1 = Yes, 0 = No)
7. Resting ECG Results (0, 1, 2)
8. Max Heart Rate Achieved
9. Exercise-induced Angina (1 = Yes, 0 = No)
10. ST Depression (Oldpeak)
11. Slope of ST Segment
12. Number of Major Vessels (0–3)
13. Thalassemia Type (0–3)

---

## 🧑‍💻 Technologies Used

* **Python**
* **Streamlit** – UI framework
* **scikit-learn** – Model training and prediction
* **pandas**, **NumPy** – Data handling
* **FPDF** – PDF report generation

---

## 📦 Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/heart-disease-predictor.git
   cd heart-disease-predictor
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Place the dataset:**
   Ensure the `heart_disease_data.csv` file is in the project root directory.

4. **Run the Streamlit app:**

   ```bash
   streamlit run app.py
   ```

---

## 📄 PDF Report

After prediction, the app generates a **personalized health report** that includes:

* Patient input details
* Prediction result (Likely or unlikely to have heart disease)
* Health advisory section
* Downloadable `.pdf` file via Streamlit

---

## ⚠️ Disclaimer

> This tool is intended for **educational and awareness purposes only**. It is **not a substitute for professional medical diagnosis or treatment**. Always consult a certified healthcare provider for medical concerns.

