# Credit Scoring Model

## 📌 Project Overview

This project was developed as part of my **Alpha Internship** to build a machine learning model that predicts an individual's **creditworthiness** based on financial information.

The project uses classification algorithms to determine whether an applicant is likely to be **Creditworthy** or **Not Creditworthy**.

Two machine learning algorithms were implemented:

* Logistic Regression
* Random Forest Classifier

The models were evaluated using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

---

## 🎯 Objective

The main objective of this project is to develop a machine learning-based credit scoring system that can predict an individual's creditworthiness using financial features such as:

* Income
* Debt
* Payment History
* Credit Utilization
* Debt-to-Income Ratio

---

## 📊 Dataset

For this educational project, a **sample financial dataset** was created to demonstrate the complete machine learning workflow.

The dataset contains financial information and a target variable:

| Feature            | Description                                              |
| ------------------ | -------------------------------------------------------- |
| Income             | Monthly income of the individual                         |
| Debt               | Existing debt                                            |
| Payment_History    | Payment history (1 = Good, 0 = Poor)                     |
| Credit_Utilization | Percentage of available credit being used                |
| Debt_to_Income     | Ratio of debt to income                                  |
| Creditworthy       | Target variable (1 = Creditworthy, 0 = Not Creditworthy) |

**Dataset size:** 20 records

> Note: The dataset is intended for educational demonstration and should not be used for real-world financial or lending decisions.

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## 🤖 Machine Learning Algorithms

### 1. Logistic Regression

Logistic Regression was used as the first classification algorithm to predict the probability of an individual being creditworthy.

### 2. Random Forest

Random Forest Classifier was implemented as a second model to compare its performance with Logistic Regression and to analyze feature importance.

---

## ⚙️ Methodology

The project follows these steps:

```text
Data Collection
      ↓
Data Understanding
      ↓
Data Preprocessing
      ↓
Feature Engineering
      ↓
Data Visualization
      ↓
Train-Test Split
      ↓
Logistic Regression
      ↓
Random Forest
      ↓
Model Prediction
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
New Applicant Prediction
```

---

## 🔧 Feature Engineering

A new feature called **Debt-to-Income Ratio** was created.

### Formula

```text
Debt-to-Income Ratio = Debt / Income
```

This feature provides an additional indication of an individual's financial burden relative to their income.

---

## 📈 Model Evaluation

The models were evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC

A **Confusion Matrix** and **ROC Curve** were also created to visualize model performance.

Since the project uses a small educational dataset, the evaluation results should not be interpreted as real-world model performance.

---

## 🔍 Feature Importance

The Random Forest model was used to analyze the importance of different financial features.

This helps identify which financial factors contribute more strongly to the model's predictions.

---

## 👤 New Applicant Prediction

The trained model was also tested using a new applicant's financial information.

The system takes values such as:

```text
Income
Debt
Payment History
Credit Utilization
Debt-to-Income Ratio
```

and predicts:

```text
Creditworthy
```

or

```text
Not Creditworthy
```

along with the probability of being classified as creditworthy.

---

## 💾 Saved Model

The trained Random Forest model was saved using Joblib:

```text
credit_scoring_model.pkl
```

---

## 📁 Project Structure

```text
Alpha_Credit_Scoring_Model/
│
├── Credit_Scoring_Model_Alpha_Internship.ipynb
├── credit_scoring_model.pkl
└── README.md
```

---

## ▶️ How to Run

### Option 1: Google Colab

1. Open the notebook in Google Colab.
2. Run the cells sequentially from top to bottom.
3. The dataset will be created automatically.
4. Train the models.
5. Evaluate the models.
6. Test the model with a new applicant.

### Option 2: Local Python Environment

Clone the repository:

```bash
git clone https://github.com/your-username/Alpha_Credit_Scoring_Model.git
```

Navigate to the project directory:

```bash
cd Alpha_Credit_Scoring_Model
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

Open the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🚀 Future Improvements

The project can be improved further by:

* Using a larger real-world credit dataset
* Handling missing and inconsistent financial data
* Applying feature scaling and advanced preprocessing
* Performing hyperparameter tuning
* Using cross-validation
* Testing additional classification algorithms
* Improving class imbalance handling
* Deploying the model as a web application
* Adding an interactive credit scoring interface

---

## ⚠️ Disclaimer

This project is developed for **educational and internship purposes only**.

The sample dataset is small and does not represent real-world banking or financial data. The model should **not** be used to make actual lending, credit, or financial decisions.

---

## 👨‍💻 Author

**Pradoksh Sowdi**

B.E. Information Science & Engineering
Alpha Internship – Machine Learning Project

---

## 📜 License

This project is intended for educational purposes.
