# 🔐 Fraud Detection System

A machine learning-based **Fraud Detection System** designed to identify potentially fraudulent financial transactions and provide an interactive interface for transaction risk analysis, customer risk assessment, fraud investigation, and ML model monitoring.

## 🚀 Project Overview

Financial fraud can cause significant losses for organizations and customers. This project uses **Machine Learning** to analyze transaction patterns and predict whether a transaction is potentially fraudulent.

The system combines a **Machine Learning backend**, **FastAPI API**, and **interactive web dashboard** to provide an end-to-end fraud detection workflow.

## 🎯 Objectives

* Detect potentially fraudulent transactions
* Calculate transaction risk
* Analyze customer risk profiles
* Support fraud investigation
* Monitor machine learning model performance
* Present insights through an interactive dashboard

## 🧠 Machine Learning

The project experiments with multiple machine learning algorithms, including:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

The models are evaluated using metrics suitable for an imbalanced fraud detection problem, including:

* **ROC-AUC**
* **PR-AUC**
* **F1 Score**

## 🏗️ System Architecture

```text
Transaction Data
       ↓
Data Processing & Feature Engineering
       ↓
Machine Learning Models
       ↓
Fraud Prediction
       ↓
FastAPI Backend
       ↓
Interactive Web Dashboard
       ↓
Risk Analysis & Investigation
```

## 📊 Dashboard Features

### 1. Overview

Provides a high-level view of:

* Total transactions
* Fraud transactions
* Fraud rate
* Transaction trends
* Risk distribution

### 2. Transaction Investigation

Allows users to analyze individual transactions and identify potentially suspicious activity.

### 3. Customer Risk

Provides customer-level risk analysis to help identify customers associated with potentially fraudulent behavior.

### 4. Model Monitoring

Displays machine learning model performance and monitoring information.

## 🛠️ Technologies Used

| Technology   | Purpose                    |
| ------------ | -------------------------- |
| Python       | Machine Learning & Backend |
| Pandas       | Data Processing            |
| NumPy        | Numerical Computing        |
| Scikit-learn | Machine Learning           |
| XGBoost      | Fraud Classification       |
| FastAPI      | REST API                   |
| React        | Frontend                   |
| Vite         | Frontend Development       |
| JavaScript   | Web Interface              |
| HTML/CSS     | UI                         |

## 📁 Project Structure

```text
fraud-detection-system/
│
├── api/
│   └── main.py
│
├── frontend/
│   ├── public/
│   │   └── data/
│   └── ...
│
├── models/
│   └── trained models
│
├── data/
│   └── processed/
│
├── requirements.txt
├── README.md
└── ...
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/fraud-detection-system.git
cd fraud-detection-system
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the environment

Windows:

```bash
.venv\Scripts\activate
```

### 4. Install Python dependencies

```bash
pip instal
```
