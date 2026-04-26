# Phishing Attack Detection Using Machine Learning

## Overview
This project presents a machine learning based framework for detecting phishing attacks using feature-based classification. The goal is to classify websites as phishing or legitimate by analyzing URL-based, domain-based, and content-based features.

Traditional rule-based phishing detection methods often fail against evolving attacks. This project explores whether machine learning models, especially ensemble methods, can improve phishing detection performance.

This work compares seven classification algorithms:

- Logistic Regression  
- Naive Bayes  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- XGBoost  

The project shows that ensemble models provide the best detection performance, with Random Forest and XGBoost achieving approximately **97% accuracy**. :contentReference[oaicite:0]{index=0}

---

## Problem Statement
Phishing attacks use deceptive websites, fake login pages, and malicious links to steal sensitive information such as:

- User credentials  
- Banking details  
- Personal data  
- Financial information  

Traditional blacklists and signature-based methods struggle to detect newly emerging phishing attacks. This project applies machine learning to solve that problem.

---



## Project Workflow

1. Data Collection  
2. Data Preprocessing  
3. Feature Engineering  
4. Model Training  
5. Model Evaluation  
6. Phishing Classification

---

## Machine Learning Models Used

### Baseline Models
- Logistic Regression
- Naive Bayes

### Classical Models
- Support Vector Machine
- K-Nearest Neighbors
- Decision Tree

### Ensemble Models
- Random Forest
- XGBoost

---

## Evaluation Metrics
The models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- ROC Curve / AUC  
- Cross Validation

---

## Results Summary

| Model | Accuracy |
|------|----------|
| Logistic Regression | 90% |
| Naive Bayes | 88% |
| SVM | 93% |
| KNN | 94% |
| Decision Tree | 94% |
| Random Forest | 97% |
| XGBoost | 97% |

### Key Findings
- Random Forest and XGBoost were top performers.
- Ensemble methods reduced false negatives.
- Feature engineering strongly influenced results.
- Simpler models performed reasonably well but struggled with complex phishing patterns.

---

## Technologies Used

- Python  
- Google Colab  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- XGBoost  

---

## Repository Structure

```bash
Phishing-Attack-Detection/
│
├── data/
│   └── phishing.csv
│
├── notebooks/
│   └── phishing_detection.ipynb
│
├── src/
│   └── phishing_detection.py
│
├── results/
│   ├── confusion_matrices/
│   ├── roc_curves/
│   └── model_results.csv
│
│
└── README.md
```

---

## How to Run

### Clone Repository
```bash
git clone https://github.com/yourusername/phishing-detection-project.git
cd phishing-detection-project
```

### Install Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib xgboost
```

### Run Notebook
Open:

```bash
phishing_detection.ipynb
```

or run Python script:

```bash
python phishing_detection.py
```

---

## Sample Output
The system compares all models and outputs:

- Classification reports  
- Accuracy comparison  
- Confusion matrices  
- ROC curves  
- Feature importance plots  

---

## Novel Contributions
This project contributes:

- A comparative framework evaluating seven ML models
- Ensemble learning approach for phishing detection
- False negative focused evaluation for security relevance
- Feature-based phishing classification pipeline

---

## Future Work
Possible extensions:

- Deep learning for advanced phishing detection  
- Real-time browser extension deployment  
- Online adaptive learning for evolving phishing attacks  
- Integration with live phishing feeds

---

## Author
**Eruventi Anjan Kumar**  
University of North Florida  
School of Computing

---

