# 💳 Credit Risk Analysis using Machine Learning
Credit risk assessment is one of the most important tasks performed by financial institutions before approving a loan. This project develops a Machine Learning-based Credit Risk Analysis system capable of predicting the likelihood of loan default using customer financial and credit information.

The application predicts:
- 📈 Default Probability
- 💳 Credit Score
- ⭐ Credit Rating

## 🎯 Objectives
- Analyze customer credit behaviour.
- Build an accurate loan default prediction model.
- Compare multiple machine learning algorithms.
- Handle imbalanced datasets.
- Optimize model performance using hyperparameter tuning.
- Deploy the trained model using Streamlit.

## 📂 Dataset
The dataset contains customer financial, behavioural, and demographic information.

### Features
- Age
- Annual Income
- Loan Amount
- Loan Tenure
- Loan-to-Income Ratio
- Average Days Past Due (DPD)
- Delinquency Ratio
- Credit Utilization Ratio
- Number of Open Loan Accounts
- Residence Type
- Loan Purpose
- Loan Type

## 🔄 Project Workflow

```text
Data Collection
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Data Preprocessing
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Model Comparison
      │
      ▼
Hyperparameter Tuning
      │
      ▼
Model Evaluation
      │
      ▼
Streamlit Deployment
```

## 🧹 Data Preprocessing
- Missing value handling
- Feature encoding
- Feature scaling
- Train-Test Split
- Loan-to-Income Ratio calculation
- Data normalization

## ⚖ Handling Class Imbalance
- Random Under Sampling
- SMOTETomek

## 🤖 Machine Learning Models

### Logistic Regression
- Baseline model
- RandomizedSearchCV tuning
- Optuna optimization

### Random Forest Classifier
- Model comparison
- Performance benchmarking

### XGBoost Classifier
- Gradient Boosting algorithm
- RandomizedSearchCV tuning
- Optuna Hyperparameter Optimization
- Final deployed model

## 🔍 Hyperparameter Optimization
### RandomizedSearchCV
- Logistic Regression
- XGBoost

### Optuna
- Logistic Regression
- XGBoost

## 📊 Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- ROC Curve

## 💻 Streamlit Web Application
The application predicts:
- 📈 Default Probability
- 💳 Credit Score
- ⭐ Credit Rating

## 📁 Project Structure

```text
Credit-Risk-Analysis/
│
├── app/
│   ├── main.py
│   ├── prediction_helper.py
│   └── model_data.joblib
│
├── artifacts/
│   └── model_data.joblib
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

## 🛠 Technologies Used

**Language**
- Python

**Libraries**
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Imbalanced-Learn
- Optuna
- Joblib
- Streamlit
- Matplotlib
- Seaborn

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/NandiniBorse04/Credit-Risk-Analysis.git
```

```bash
cd Credit-Risk-Analysis
```

```bash
python -m venv venv
```

```bash
.\venv\Scripts\Activate.ps1
```

```bash
pip install -r requirements.txt
```

```bash
streamlit run app/main.py
```

## 📜 License
This project is licensed under the MIT License.
