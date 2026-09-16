# MLCS Lab Programs

This repository contains my **Machine Learning and Cyber Security (MLCS) Lab** programs for Experiments 1–6.

The programs mainly focus on network traffic analysis, DDoS detection, cyber attack classification, and malicious/phishing URL detection using different machine learning and data analysis techniques.

---

## 📚 Experiments

| No. | Experiment | Technique Used |
|-----|------------|----------------|
| 1 | Time Series Decomposition | Additive Time Series Decomposition |
| 2 | Network Traffic Forecasting & DDoS Detection | ARIMA |
| 3 | Cyber Attack Classification | Random Forest |
| 4 | Phishing URL Detection | TF-IDF + Logistic Regression |
| 5 | Malicious URL Classification | TF-IDF + SVM |
| 6 | URL Abnormal Pattern Detection | Feature Engineering + Random Forest |

---

## 🔍 What This Repository Covers

### Experiment 1 – Time Series Decomposition
Network traffic data is separated into different components such as:

- Trend
- Seasonal component
- Residual

This helps in understanding unusual changes and traffic spikes.

### Experiment 2 – DDoS Detection
An ARIMA model is used to analyze and forecast network traffic. Unexpected differences between predicted and actual traffic can be used to identify possible anomalies.

### Experiment 3 – Cyber Attack Classification
Network traffic data is classified into normal and attack categories using a Random Forest classifier.

### Experiment 4 – Phishing URL Detection
URLs are converted into numerical features using TF-IDF character n-grams and classified using Logistic Regression.

### Experiment 5 – Malicious URL Detection
A larger balanced URL dataset is used with TF-IDF features and an SVM classifier to identify potentially malicious URLs.

### Experiment 6 – URL Pattern Analysis
Additional URL features are extracted, including:

- URL length
- Hostname length
- Shannon entropy
- IP address patterns
- Suspicious keyword frequency

These features are then used with a Random Forest model for classification.

---

## 📁 Files in the Repository

```text
MLCS-LAB-PROGRAM/
│
├── exp1.py
├── exp2.py
├── exp3.py
├── exp4.py
├── exp5.py
├── exp6.py
│
├── activity1.py
├── ddos_timeseries_analysis.py
├── activity1_report.md
│
├── DDoS_dataset.csv
├── cyber_attacks.csv
├── urls_dataset.csv
├── Time-Series_Network_logs.csv
├── balanced_urls.csv
│
├── *.png
├── *.pkl
│
├── requirements.txt
└── README.md
