# 💳 Credit Card Fraud Detection & Analytics Dashboard

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning models and visualizing insights through an interactive Power BI dashboard.

The dataset is **highly imbalanced**, making fraud detection a challenging and realistic problem. Multiple models are trained and compared, and results are presented in a business-friendly analytics dashboard.

---

## 🚀 Objectives
- Detect fraudulent credit card transactions
- Handle highly imbalanced data
- Compare multiple ML models
- Analyze fraud patterns by **time** and **transaction amount**
- Build an industry-style analytics dashboard in Power BI

---

## 🧠 Machine Learning Models Used
- Logistic Regression  
- Random Forest  
- XGBoost  
- Hybrid Model (Ensemble of Logistic + RF + XGBoost)

---

## 📊 Dashboard Features (Power BI)
- Total Transactions  
- Fraud Transactions Count  
- Fraud Percentage  
- Fraud Distribution by Hour  
- Fraud Heatmap (Hour × Amount Range)  
- Fraud vs Non-Fraud Average Amount  
- Model-wise Fraud Count  
- Model Precision Comparison  
- Interactive slicers:
  - Hour
  - Amount Range
  - Model Selection

---

## 🛠️ Tools & Technologies
- **Python** (NumPy, Pandas, Scikit-learn, XGBoost)
- **Jupyter Notebook**
- **Power BI**
- **Matplotlib & Seaborn**

---

## 📁 Project Structure
FraudDetectionProject/
├── Data/
│ └── fraud_dashboard_data.csv
├── Images/
│ └── Fraud_Dashboard.png
├── Notebooks/
│ └── fraud_analysis.ipynb
├── PowerBI/
│ └── Fraud_Dashboard.pbix
├── creditcard.csv
├── README.md
└── requirements.txt

---

## ⚠️ Large Files & GitHub File Size Limitation

Some datasets and dashboard files used in this project exceed GitHub’s **100 MB file size limit**, so they cannot be uploaded directly to this repository.

### Affected Files
- `Data/creditcard.csv` 
- `Data/fraud_dashboard_data.csv` 
- `PowerBI/Fraud_Dashboard.pbix` 

### 📥 Download Large Files
You can download the required large files from the link below:

  👉 https://drive.google.com/drive/folders/1prQRs4zJSdhnl1Fhd8T1EEMYaBKaH1VQ?usp=sharing


### Note
All machine learning code, preprocessing scripts, and dashboard logic are included in this repository.  
Only large files are hosted externally.
---

## 📷 Dashboard Preview
![Dashboard Preview](Images/Fraud_Dashboard.png)

---

## 📌 Key Insights
- Fraud transactions account for **less than 0.2%** of total transactions
- Fraudulent transactions often involve **higher amounts**
- Fraud peaks at **specific hours and amount ranges**
- **Hybrid and XGBoost models** show better precision
- Ensemble modeling improves stability in fraud detection

---

## 👤 Author
**Gayapu Laxman Reddy**  
B.Tech CSE  
Machine Learning | Data Analytics | Power BI  

📫 Feel free to connect on LinkedIn and GitHub
