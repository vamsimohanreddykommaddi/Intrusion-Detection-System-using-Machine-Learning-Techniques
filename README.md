# Intrusion Detection System (IDS) Using Machine Learning

## 📌 Project Overview
This project focuses on detecting **network intrusions and cyber threats** using **Machine Learning (ML) techniques**. It utilizes the **NSL-KDD dataset**, a widely used benchmark for intrusion detection, to classify network traffic into normal and attack categories.

## 🔍 Objectives
- Develop an **ML-based Intrusion Detection System (IDS)** to classify network traffic.
- Train a **Random Forest Classifier** to distinguish between normal and malicious activities.
- Handle **imbalanced data** using **SMOTE (Synthetic Minority Over-sampling Technique)**.
- Evaluate model performance using **accuracy, precision, recall, and F1-score**.

## 📂 Dataset Used
- **KDDTrain+.txt** – Training data containing various network traffic records.
- **KDDTest+.txt** – Test data used for evaluating model performance.
- Features include **protocol type, service, duration, bytes transferred, and attack labels**.

## 🛠️ Technologies & Tools Used
- **Python** (NumPy, Pandas, Matplotlib, Seaborn)
- **Scikit-learn** (Machine Learning models & preprocessing)
- **Imbalanced-learn (SMOTE)** (Handling imbalanced datasets)
- **Google Colab** (For cloud-based execution)

## 📊 Methodology
### 1️⃣ Data Preprocessing
- Loaded the dataset using **Pandas**.
- Displayed key attributes like `protocol_type`, `service`, and `attack types`.
- Converted categorical data into numerical form.
- Applied **feature scaling** to normalize numerical values.

### 2️⃣ Handling Imbalanced Data
- The dataset contained **imbalanced classes** (more normal records than attack records).
- Used **SMOTE (Synthetic Minority Over-sampling Technique)** to balance attack and normal samples.

### 3️⃣ Model Training
- Split the dataset into **training (80%) and testing (20%)** sets.
- Trained a **Random Forest Classifier**, known for its high accuracy and robustness.

### 4️⃣ Model Evaluation
- Evaluated performance using **confusion matrix, accuracy, precision, recall, and F1-score**.
- Visualized model performance using **Matplotlib & Seaborn**.

## 📈 Results & Insights
- The **Random Forest Classifier** achieved **high accuracy** in detecting network intrusions.
- **Feature importance analysis** identified key attributes contributing to intrusion detection.
- **SMOTE balancing improved model performance**, especially for minority attack classes.

## 🚀 Future Enhancements
- Implementing **Deep Learning models** like LSTMs or CNNs for better accuracy.
- Adding **real-time packet analysis** to detect live network threats.
- Expanding dataset with **newer cybersecurity threats and attack types**.

---
