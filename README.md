# Network Anomaly Detection Using Machine Learning

## 📖 Project Overview
This project identifies zero-day threats by flagging unusual network traffic. Moving beyond standard signature-based systems, it applies machine learning models exclusively to the KDD Cup 99 dataset to detect malicious activity and potential intrusions.

## 🎯 Objective
To detect unusual patterns in network traffic using anomaly detection techniques.

## ⚠️ Problem Statement
Unknown or zero-day attacks are difficult to detect using signature-based systems. This project focuses on identifying anomalies that indicate potential threats rather than relying on known attack signatures.

## 📂 Repository Structure
* **`network_anomaly_detection.py`**: The main Python script containing the data preprocessing, model implementation, and evaluation logic.
* **`kddcup.data.gz.zip`**: The compressed training dataset (KDD Cup 99).
* **`corrected.gz.zip`**: The compressed test dataset containing corrected labels for evaluating the models.

## 🧠 Implemented Models
This project explores the following machine learning models to identify network anomalies:
* **Isolation Forest**
* **One-Class SVM**
* **Autoencoder**
* **Random Forest**

## 🚀 Getting Started

### Prerequisites
Ensure you have Python installed. You will likely need standard data science and machine learning libraries. If you don't have them installed, you can do so via pip:
```bash
pip install pandas numpy scikit-learn
