# 🏥 NovaGen Risk Prediction using Ensemble Machine Learning

An end-to-end Machine Learning project that predicts patient risk using multiple supervised learning algorithms. The project compares individual models with an ensemble approach to improve predictive performance while emphasizing **Recall**, a crucial metric in healthcare applications.

---

## 📌 Project Overview

NovaGen is a healthcare risk prediction system designed to classify patients into high-risk and low-risk categories using clinical features.

The project includes data preprocessing, feature scaling, model training, model comparison, and ensemble learning using Soft Voting.

---

## 🚀 Features

- End-to-end Machine Learning pipeline
- Data preprocessing and train-test splitting
- Feature scaling using StandardScaler
- Multiple model comparison
- Ensemble Learning using Soft Voting Classifier
- Performance evaluation using Recall, Accuracy and Classification Report
- Healthcare-oriented evaluation strategy

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn

---

## 📂 Dataset

Dataset contains patient-related medical features used to predict health risk.

> Place the dataset inside the `data/` folder.

```
data/
└── novagen_dataset.csv
```

---

## ⚙️ Machine Learning Workflow

### Data Preprocessing

- Loaded dataset using Pandas
- Train-Test Split (80:20)
- Stratified Sampling
- Feature Scaling using StandardScaler

---

### Models Implemented

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest
- Gradient Boosting
- Soft Voting Ensemble

---

## 📊 Model Evaluation

Performance Metrics

- Accuracy
- Recall
- Classification Report

### Why Recall?

In healthcare applications, missing a high-risk patient can have serious consequences. Therefore, Recall was considered a key evaluation metric.

---

## 📁 Project Structure

```
novagen-risk-prediction-ensemble-ml/
│
├── data/
│   └── novagen_dataset.csv
│
├── notebooks/
│   └── novagen_prediction.ipynb
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/preetmohantyagi/novagen-risk-prediction-ensemble-ml.git
```

Navigate to the project

```bash
cd novagen-risk-prediction-ensemble-ml
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 📚 Libraries Used

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## 🔮 Future Improvements

- Hyperparameter tuning using RandomizedSearchCV
- XGBoost and LightGBM implementation
- SHAP explainability
- Model deployment using Streamlit
- REST API using FastAPI
- Cross-validation for robust evaluation

---

## 👨‍💻 Author

**Preet Mohan Tyagi**

- GitHub: https://github.com/preetmohantyagi
- LinkedIn: https://www.linkedin.com/in/preetmohantyagi

---

## ⭐ If you found this project useful, consider giving it a star!
