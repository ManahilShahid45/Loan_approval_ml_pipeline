# 📌 Loan Approval Prediction using Supervised ML

## 🧠 Objective

To predict whether a loan application will be approved based on applicant attributes like income, credit history, marital status, and loan amount.  
The goal is to assist financial institutions in automating the loan approval process using supervised machine learning.

---

## 🛠️ Methodology

- **Data Cleaning:** Handled missing values and dropped unnecessary columns.  
- **Label Encoding:** Converted categorical features to numerical form.  
- **Imputation:** Used mode/mean to fill missing data.  
- **Model Building:**
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
- **Evaluation Metrics:**
  - Accuracy  
  - AUC Score  
  - Confusion Matrix  
  - Precision, Recall, F1-Score  

---

## 📊 Key Results

| Model               | Accuracy | AUC Score |
|--------------------|----------|-----------|
| Logistic Regression| ~0.81    | ~0.76     |
| Decision Tree      | ~0.78    | ~0.71     |
| Random Forest      | ~0.83    | ~0.78     |

> ✅ **Random Forest gave the best overall performance.**

---

## 🧰 Tools & Libraries Used

- **Python 3.10+**
- `pandas`, `numpy` – Data handling  
- `matplotlib`, `seaborn` – Visualization  
- `scikit-learn` – Machine Learning Models  

---

## 🧠 Skills Demonstrated

- Handling real-world datasets  
- Dealing with categorical variables and missing data  
- Model evaluation and selection  
- Data visualization and performance comparison  

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/loan-approval-ml-pipeline.git
cd loan-approval-ml-pipeline
