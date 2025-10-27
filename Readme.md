# 🕵️‍♂️ Fraud Detection System

A robust machine learning-based system designed to detect fraudulent transactions with high accuracy and efficiency. Built using Python and Streamlit, this project combines data preprocessing, model training, and an interactive interface for real-time predictions.

---

## 🚀 Features

- ✅ Streamlit-powered web interface for user-friendly interaction  
- 📦 Pre-trained model (`fraud_detection_pipeline.pkl`) for instant predictions  
- 📊 Exploratory Data Analysis and model insights via Jupyter Notebook  
- 🔍 Handles missing values, encodes categorical features, and scales inputs  
- 🧠 Supports batch and single transaction evaluation  

---

## 🔗 Live Demo

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://fraud-detection-system-8wny5mlvpnqrsnbhqmn8pa.streamlit.app/)

> Click the badge to launch the app instantly — no setup required!

---

## 🧰 Tech Stack

| Component        | Details                          |
|------------------|----------------------------------|
| Language         | Python                           |
| Interface        | Streamlit                        |
| Model            | Scikit-learn                     |
| Notebook         | Jupyter Notebook (`.ipynb`)      |

## 📊 Dataset

The dataset used in this project is sourced from **Kaggle**.  
You can access it here:  
👉 [Click here to view the dataset on Kaggle](https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset?resource=download)

---

## 🚀 Model Enhancements (10/27/2025)

Recent updates have significantly improved the performance and interpretability of the fraud detection system:

- **Upgraded Model:** Replaced Logistic Regression with **LightGBM (LGBMClassifier)** to better handle class imbalance and achieve higher accuracy.
- **Enhanced Evaluation:** Integrated **Precision**, **Recall**, and **F1-Score** metrics for a more comprehensive understanding of model performance on minority (fraud) cases.
- **AUC-ROC Curve:** Added an **AUC-ROC Curve** visualization to graphically evaluate the trade-off between true positive and false positive rates.
- **Improved Reliability:** Leveraged LightGBM’s gradient boosting framework for improved precision, recall stability, and faster model convergence compared to linear models.
- I previously lost my improvements due to git command mishandling and removed my whole repository and now I have fixed everything, work needs to be finished you know ;)  

---

## ⚙️ Installation

```bash
git clone https://github.com/ProfessionalPallav20014/Fraud-Detection-System.git
cd Fraud-Detection-System
pip install -r requirements.txt

python -m streamlit run FD_interface.py


