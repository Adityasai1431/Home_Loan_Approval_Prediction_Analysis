# # 🏦 Home Loan Approval Prediction Analysis- Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on a Home Loan Approval dataset to identify key factors influencing loan approval decisions.

The dataset contains **614 records and 13 features**, including applicant demographics, income details, loan information, and credit history.

---

## 📂 Dataset Features
- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status (Target Variable)

---

## 🛠️ Tools & Technologies Used
- Python 🐍
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 🔍 Key Steps Performed

### 1. Data Understanding
- Analyzed dataset structure, data types, and summary statistics
- Identified categorical and numerical features

### 2. Data Cleaning & Preprocessing
- Handled missing values:
  - Mode for categorical columns
  - Median for LoanAmount
- Converted data types (object → category)
- Checked and removed inconsistencies
- Verified no duplicate records

### 3. Univariate Analysis
- Studied distribution of numerical features using histograms and boxplots
- Analyzed categorical variables using count plots and pie charts

### 4. Bivariate Analysis
- Explored relationships between:
  - Categorical vs Target (Loan_Status)
  - Numerical vs Target
- Used count plots, bar plots, and box plots

### 5. Multivariate Analysis
- Used correlation heatmap
- Identified relationships between income, loan amount, and approval

---

## 📊 Key Insights

- ⭐ **Credit History is the most important factor** in loan approval
- 👨‍🎓 Graduates have higher approval rates
- 💼 Salaried applicants are preferred over self-employed
- 💍 Married applicants show better approval trends
- 👨‍👩‍👧 Applicants with fewer dependents are more likely to get loans
- 🌆 Semiurban and Urban areas have higher approval rates
- 💰 Income alone does not guarantee loan approval

---

## 📈 Visualizations
- Histograms & Boxplots
- Count Plots & Pie Charts
- Bar Plots
- Heatmap (Correlation Matrix)

---

## 📎 Project Files
- `EDA.ipynb` → Main analysis notebook  
- `loan_sanction_train.csv` → Dataset  
- `Project_Presentation.pdf` → Project presentation  

---

## 📁 Project Structure
```
Home_Loan_Approval_Prediction_Analysis/
│
├── data/
│   └── loan_sanction_train.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── presentation/
│   └── Project_Presentation.pdf
│
├── README.md
```
---

## 🚀 Future Scope
- Build a **Machine Learning model** for loan prediction
- Perform **feature engineering**
- Deploy as a **web application**

---

## 🔗 Connect With Me
- GitHub: https://github.com/Adityasai1431
- LinkedIn: https://www.linkedin.com/in/aditya-kumar-lotti-136122249/  

---

⭐ If you like this project, give it a star!
