# ❤️ Heart Disease Prediction App 
A Streamlit-based Machine Learning web application that predicts the risk of heart disease based on key medical input features. The app uses a trained Logistic Regression model and provides confidence scores, risk levels, and visual probability charts.

## 🚀 Features
- Predict heart disease using ML  
- Clean UI with sliders & dropdowns  
- Probability visualization using Plotly  
- Confidence score and risk levels  
- Input summary table  
- Loads model and scaler from `.pkl` files  
- Includes medical disclaimer  

---

## 📦 Project Structure

 - heart_app.py
 - heart_disease_model.pkl
 - heart_scaler.pkl
 - requirements.txt


---

## 🛠️ Installation & Setup

### 1. Install dependencies
```bash
pip install -r requirements.txt
2. Run the app
streamlit run heart_app.py
```
🧪 Model Details

Model: Logistic Regression
Dataset: 303 patient records
Accuracy: ~85%
Features Used: 13 medical attributes

📊 Output Provided

Prediction: Healthy or Disease Risk
Confidence percentage
Risk level: Low / Medium / High
Probability bar chart
Input summary table

⚠️ Disclaimer
This app is for educational purposes only and not a substitute for professional medical diagnosis.
