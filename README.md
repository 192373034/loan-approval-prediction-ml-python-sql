# Financial Loan Approval Prediction using Machine Learning with Python and SQL

## 📌 Project Overview
This project aims to predict whether a loan will be approved or not based on applicant details. It uses Machine Learning techniques along with SQL-based analysis to automate and improve the loan approval process.

---

## 🎯 Objective
To build a predictive model that can analyze applicant data and determine loan approval status accurately, reducing manual effort and decision-making time.

---

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- SQLite (SQL)

---

## 📊 Dataset Description
The dataset contains information about loan applicants such as:
- Gender
- Marital Status
- Dependents
- Education
- Self Employment
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Term
- Credit History
- Property Area
- Loan Status (Target Variable)

---

## ⚙️ Project Workflow

### 1. Data Collection
Loaded dataset using Pandas.

### 2. Data Preprocessing
- Handled missing values using mean and mode
- Converted categorical data into numerical format using Label Encoding

### 3. Exploratory Data Analysis (EDA)
- Visualized loan approval distribution
- Analyzed relationship between credit history and loan status

### 4. Model Building
- Split data into training and testing sets
- Trained model using **Random Forest Classifier**

### 5. Model Evaluation
- Accuracy achieved: **~79%**
- Used confusion matrix for detailed evaluation

### 6. SQL Integration
- Stored dataset into SQLite database
- Performed SQL queries to analyze:
  - Loan approval counts
  - Credit history vs loan status
  - Average income analysis

---

## 📈 Key Insights
- Applicants with good credit history are more likely to get loan approval
- Loan approval is not solely dependent on income
- Majority of loan applications are approved

---

## 📂 Files in Repository
- `LoanApprovalPrediction.csv` → Dataset
- `loan_approval.ipynb` → Implementation notebook
- `README.md` → Project documentation

---

## 🚀 How to Run the Project
1. Clone the repository
2. Open Jupyter Notebook
3. Run `loan_approval.ipynb`
4. Install required libraries if needed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn sqlalchemy

   
  **Author Name**
   Bandaru Nikitha
