# 📊 Churn Prediction Dashboard

A **machine learning-powered dashboard** to **predict customer churn** in telecom companies. Upload customer data, generate predictions, and explore interactive visualizations to identify **high-risk customers**.

---

## 🌟 Why This Project?

Customer churn directly impacts company revenue. By predicting which customers are likely to leave, telecom businesses can:

- Proactively retain customers
- Improve customer satisfaction
- Reduce marketing & retention costs

This dashboard was built as part of a **hackathon challenge** focusing on churn prediction using real-world telecom data.

---

## 🚀 Features

✅ **CSV File Upload** for customer data  
✅ **Churn Prediction** using trained **Random Forest Classifier**  
✅ **Downloadable Prediction Results**  
✅ **Interactive Visualizations**:
- Churn vs Retained distribution
- Monthly & Total Charges vs Churn
- Contract type, Device Protection, Tech Support impact
✅ **Top 10 High-Risk Customers List**  
✅ **Feature Importance Graph** (What features affect churn the most)

---

## 🗂️ Project Structure

📁 churn-prediction-dashboard

 churn_prediction_model.py # Train model locally
 churn_gui.py # Streamlit dashboard app
 d-2 train dataset.csv # Training dataset (private/local)
 d-2 test dataset.csv # Example test dataset (private/local)
 Churn Prediction Dashboard final.pdf # Presentation/report of the project

📤 Example CSV Format

| MonthlyCharges | TotalCharges | Contract       | TechSupport | tenure | DeviceProtection | ... |
| -------------- | ------------ | -------------- | ----------- | ------ | ---------------- | --- |
| 65.5           | 4500         | Month-to-month | No          | 22     | Yes              | ... |

## 🤖 Machine Learning Model Details

| **Property**     | **Details**                                                                     |
|------------------|-------------------------------------------------------------------------------- |
| **Algorithm**    | Random Forest Classifier                                                        |
| **Preprocessing**| Label Encoding for categorical features, Standard Scaler for numerical features |
| **Metrics**      | AUC-ROC ≈ 0.84 (Good Performance)                                               |


📊 Visualizations Included

| 🔸 Visualization         | 📌 Insight                                           |
| ------------------------ | ----------------------------------------------------- |
| Churn Distribution       | % of Churned vs Retained                              |
| Monthly Charges vs Churn | Higher charges → Higher churn probability             |
| Tenure vs Churn          | Shorter tenure → More likely to churn                 |
| Contract Type Analysis   | Month-to-month contracts → Higher churn risk          |
| Tech Support Impact      | Customers without tech support → More likely to churn |
| Top 10 Risk Customers    | List of most vulnerable customers with churn %        |
| Feature Importance       | What drives churn?                                    |

🎯 Future Scope
✅ Add animations to the file uploader and graphs (Planned)

✅ Enhance visual realism of graphs (Planned)

🔐 Add login/authentication for secure dashboard access

🧠 Improve model with advanced hyperparameter tuning

📬 Contact:

Developers: 

GitHub: 

Email: 








