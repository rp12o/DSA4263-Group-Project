# DSA4263-Group-Project
# 🛡️ Online Payment Fraud Detection

This project focuses on building a machine learning pipeline to detect fraudulent online payment transactions. Using supervised learning techniques such as Logistic Regression, XGBoost, SMOTE for class imbalance handling, and ensemble learning, the model aims to identify patterns of fraud in financial transaction data.

---

## 📁 Project Structure
DSA4263-Group-Project/
├── README.md
├── requirements.txt
├── data
│   ├── raw
│   │   └──  # Folder for dataset (empty by default)
│   └── processed
│       ├── test_data.csv.gz
│       └── test_data.csv.gz
├── EDA
│   ├── OnlineFraudEDA
│   └── OnlineFraudEDA(Cash_In)
│   ├── OnlineFraudEDA(Cash_Out)
│   └── OnlineFraudEDA(Transfer)
│   ├── OnlineFraudEDA(Payment)
│   └── OnlineFraudEDA(Debit)
├── models
    ├── Ensemble
    └── LogReg
    ├── NaiveBayes
    └── XGBoost

## 📊 Dataset

This project uses a public dataset originally from [Kaggle's Online Payment Fraud Detection](https://www.kaggle.com/datasets/ealaxi/paysim1).

However, due to GitHub's file size limitations, the raw dataset is **not included in this repository**.

### 🔗 Download Instructions

Please download the dataset manually using the link below:

👉 [Download from Google Drive]([https://drive.google.com/your-shareable-link-here](https://drive.google.com/file/d/1gZ15NYGJuNbc6Q5GTkmLKTmNKj0Gso5y/view?usp=sharing))

After downloading:

1. Place the dataset (e.g., `onlinefraud.csv`) in the `data/` folder.
2. If provided as a `.gz` file, ensure it is extracted or handled appropriately in your preprocessing script.

---

## ⚙️ Requirements

To install all dependencies:

```bash
pip install -r requirements.txt
