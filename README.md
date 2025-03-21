# 💳 Credit Risk Classification

**Author:** Logan Dameron  
*Machine learning analysis created for educational purposes as part of the edX Data Science Bootcamp.*

---

## 🚀 Overview

This project builds a binary classification model to help a peer-to-peer lending platform evaluate the risk level of loan applicants.  

Using historical lending data, I trained a **logistic regression model** to predict whether a loan is high-risk (`1`) or healthy (`0`).

---

## 📊 Dataset

- **Source:** Lending data provided in `lending_data.csv`
- **Features (X):** Borrower financial information (e.g., income, debt-to-income ratio)
- **Target (y):** `loan_status` (0 = healthy loan, 1 = high-risk loan)

---

## 🧪 Model & Metrics

I applied a **Logistic Regression** model using Scikit-learn:

- Data split into 75% training / 25% testing
- Evaluated with accuracy, precision, and recall

### 🔎 Results

| Metric     | Class 0 (Healthy) | Class 1 (High-Risk) |
|------------|------------------|---------------------|
| Precision  | 1.00             | 0.84                |
| Recall     | 0.99             | 0.94                |
| Accuracy   | **0.99**         |                     |

The model performs especially well for both classes. While healthy loans are predicted nearly perfectly, the model also catches 94% of actual high-risk loans with strong precision.

---

## 📁 Folder Structure

```bash
📦 credit-risk-classification
 ┣ 📂 Resources
 ┃ ┗ 📜 lending_data.csv
 ┣ 📜 credit_risk_classification.ipynb
 ┣ 📜 report-template.md
 ┗ 📜 README.md
