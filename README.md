# Invoice_Payment_Delay_Prediction
This project predicts whether an invoice will be paid on time or delayed using supervised machine learning. It is built using a mock dataset  and simulates invoice payment behavior for a fictional company "Oracle India Pvt Ltd'
# Invoice Payment Delay Prediction 🧾📊

This project predicts whether an invoice will be paid on time or delayed using supervised machine learning. It is built using a **mock dataset** and simulates invoice payment behavior for a fictional company, **FinEdge Solutions**.

---

## 📌 Project Summary

This notebook explores invoice-level data and uses classification models to predict delays in payments. The main goal is to help businesses proactively manage late payments and identify high-risk invoices.

---

## 🔧 Tools & Technologies
- Python (Pandas, NumPy)
- Scikit-learn (Logistic Regression, Random Forest)
- Matplotlib / Seaborn
- Jupyter Notebook / Google Colab

---

## 📊 Dataset
- Synthetic/mock data simulating:
  - Invoice date
  - Due date
  - Customer type/rating
  - Payment delay (in days)
  - Paid/Not Paid (label)
- File: `invoice_data.csv` *(replace with actual name if included)*

---

## 🧠 Workflow
1. Data Cleaning & Preprocessing
2. Feature Engineering (e.g., delay duration, customer behavior)
3. EDA (heatmaps, distributions, class balance)
4. Model Training (Logistic Regression, Random Forest)
5. Model Evaluation (Accuracy, ROC AUC, Confusion Matrix)
6. Prediction & Interpretability

---

## ✅ Key Results
- **Random Forest** gave the best performance with ~87% accuracy
- Key factors: invoice amount, customer type, delay history
- Insight: High-risk customers cause >60% of delays

---

## 📸 Sample Output
_Add a screenshot of your output or model result here if available_

---

## 📂 File Guide
| File Name                          | Description                        |
|-----------------------------------|------------------------------------|
| `Invoice_Payment_Delay_Prediction.ipynb` | Main ML Notebook                    |
| `invoice_data.csv`                | Dataset (mock, optional to upload) |
| `output_sample.png`               | Screenshot of notebook result      |
| `README.md`                       | This documentation file            |

---

## 💡 Future Enhancements
- Try XGBoost or LightGBM for better performance
- Add feature selection & SHAP explainability
- Deploy as a web app using Flask or Streamlit

---

## 📬 Contact
If you’d like to discuss this project or collaborate, feel free to reach out via GitHub or LinkedIn!

