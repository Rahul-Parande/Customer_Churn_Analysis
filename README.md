# 📊 Customer Churn Analysis – Telecom Dataset

## 📌 Project Overview
Customer churn is one of the biggest challenges for telecom companies. Retaining customers is far more cost-effective than acquiring new ones.  
In this project, I analyzed the behavior of **7,043 telecom customers** to identify churn patterns, engineered new features, and built machine learning models to predict churn.  

The goal: **Understand why customers leave and suggest strategies to reduce churn.**

---

## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Scikit-learn, SHAP  
- **Environment**: Jupyter Notebook  

---

## 📂 Dataset
The dataset includes **7,043 customers** with features such as:
- Demographics: gender, senior citizen, partner, dependents  
- Account info: tenure, contract type, payment method  
- Services: phone, internet, streaming, etc.  
- Financials: monthly charges, total charges  
- Target: `Churn` (Yes/No)

---

## 🔑 Key Steps
1. **Data Cleaning & Preprocessing**  
   - Handled missing values & categorical encoding  
   - Scaled numerical variables  
   - Created **tenure bands** & **contract type buckets**  

2. **Exploratory Data Analysis (EDA)**  
   - Generated **11+ visualizations** (histograms, box plots, heatmaps)  
   - Insights: Customers on **monthly contracts with <3 months tenure** had the highest churn rate  

3. **Modeling**  
   - Trained Logistic Regression, Decision Tree, and Random Forest  
   - Compared performance using Accuracy, Precision, Recall, ROC-AUC  
   - **Random Forest** performed the best  

4. **Model Interpretation (SHAP)**  
   - Explained feature importance & contributions  
   - Found that **tenure, contract type, and monthly charges** are the top drivers of churn  

---

## 📊 Results & Insights
- **38% of churned users** were on monthly contracts with **less than 3-month tenure**  
- Customers with **high monthly charges** were more likely to churn  
- **Recommendations**:  
  - Offer loyalty benefits to new customers within the first 3 months  
  - Provide discounts or flexible plans to customers with high monthly charges  
  - Encourage long-term contracts to reduce churn risk  

---

## 📈 Visualizations
Some key plots included:
- Distribution of churn across tenure bands  
- Box plots of monthly charges vs churn  
- SHAP summary plots for feature importance  

*(Add screenshots of plots here if possible)*

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-churn-analysis.git
   cd customer-churn-analysis
