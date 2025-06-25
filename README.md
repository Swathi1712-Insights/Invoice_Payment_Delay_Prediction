# Invoice_Payment_Delay_Prediction📊
This project predicts whether an invoice will be paid on time or delayed using supervised machine learning. It is built using a mock dataset  and simulates invoice payment behavior for a fictional company "Oracle India Pvt Ltd'
# 📌 Project Summary

This notebook explores invoice-level data and uses classification models to predict delays in payments. The main goal is to help businesses proactively manage late payments and identify high-risk invoices.

# 🔧 Tools & Technologies
- Python (Pandas, NumPy)
- Scikit-learn (Logistic Regression, Random Forest)
- Matplotlib / Seaborn
- Google Colab
- 
# 📊 Dataset
  - Mock data simulating:
  - Invoice date
  - Due date
  - Customer type/rating
  - Payment delay (in days)
  - Paid/Not Paid (label)
- File: "invoice_payment_data.csv" 

# 🧠 Workflow
1. Data Cleaning & Preprocessing
2. Feature Engineering (e.g., delay duration, customer behavior)
3. EDA (heatmaps, distributions, class balance)
4. Model Training (Logistic Regression, Random Forest)
5. Model Evaluation (Accuracy, ROC AUC, Confusion Matrix)
6. Prediction & Interpretability

# ✅ Key Results
- **Random Forest** gave the best performance with ~87% accuracy
- Key factors: invoice amount, customer type, delay history
- Insight: High-risk customers cause >60% of delays


# 💡 Future Enhancements
- Try XGBoost or LightGBM for better performance
- Add feature selection & SHAP explainability
- Deploy as a web app using Flask or Streamlit

# 📬 Contact
If you’d like to discuss this project or collaborate, feel free to reach out via GitHub ,LinkedIn :www.linkedin.com/in/swathi-vnk-325142184
or Mail Id : vnkswathi1712@gmail.com



