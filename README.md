# ❤️ Heart Disease Prediction with KaggleHub

This project demonstrates how to use the publicly available Kaggle dataset [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) via `kagglehub` to build a machine learning model and simulate secure healthcare data practices such as encryption.

## 📦 Dataset

- **Source**: [mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Records**: 284,807 transactions
- **Fraud Cases**: Only 492 (~0.17%)
- **Fields**: PCA-transformed features + `Amount`, `Time`, and `Class` (target)

## 🧠 What This Project Covers

- Automated data download using **KaggleHub**
- Exploratory Data Analysis (EDA)
- Preprocessing using **StandardScaler**
- Binary classification using **Logistic Regression**
- Evaluation via **accuracy**, **precision**, **recall**, and **F1-score**
- Simulated **HIPAA-style encryption** for patient ID using Python's `cryptography` package

## 🚀 How to Run

1. **Install dependencies**:
```bash
pip install kagglehub pandas scikit-learn matplotlib seaborn cryptography
```

2. **Ensure KaggleHub is authenticated** using your Kaggle API credentials:
   - Save your `kaggle.json` file under `~/.kaggle/kaggle.json`

3. **Run the notebook**:
Open `fixed_heart_disease_kagglehub_notebook.ipynb` and execute all cells to download the dataset, train the model, and see evaluation + encryption demo.

## 🔐 Sample Encryption Output

Simulates encrypting a patient ID:
```
Encrypted: gAAAAABl...
Decrypted: Patient123
```

## 📘 License

This notebook is for educational use only.
