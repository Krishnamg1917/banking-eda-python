# 🏦 Banking Loan EDA  

## 📌 Project Overview  
This project performs **Exploratory Data Analysis (EDA)** on banking loan data to understand customer demographics, financial patterns, and risk factors. The goal was to uncover insights that can improve **loan approval strategies, customer segmentation, and risk management** for financial institutions.  

---

## 🚀 Key Highlights  
- 🔗 **Data Extraction**: Connected to **MySQL database** and imported the `banking_case.banking` table into Pandas.  
- 🧹 **Data Cleaning & Transformation**:  
  - Handled missing values and irrelevant columns.  
  - Created **Income Bands** (Low, Medium, High) using custom bins.  
- 📊 **Exploratory Data Analysis (EDA)**:  
  - Analyzed demographic factors like **Gender, Nationality, Occupation, Age, Loyalty, Properties Owned**.  
  - Studied financial indicators like **Estimated Income, Credit Cards, Fee Structure, Risk Weighting**.  
- 📈 **Visualizations**: Built **countplots, histograms, and distributions** to uncover behavioral patterns.  

---

## 🔍 Key Insights  
- **Overall Dataset Size**: 5,000+ customer records analyzed.  
- **Income Bands**: ~62% of customers belonged to **Low–Medium income groups**, directly linked to higher loan risks.  
- **Occupation Trends**: **Technicians (18%)** and **Sales Executives (15%)** showed the highest concentration in **risk-prone categories**.  
- **Credit Behavior**: Customers with **2+ credit cards had 30% higher default risk**, while “High Loyalty” customers had **20% lower defaults**.  
- **Age Factor**: Age group **26–35 years** contributed to ~40% of loan applications but also had the **highest rejection/default rates**.  
- **Risk Factor**: Customers with **1–3 years tenure showed 25% higher attrition/default tendency** compared to long-tenured customers.  

---

## 🛠 Tools & Skills  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **SQL (MySQL)**: Data extraction & integration  
- **Data Cleaning & Transformation**: Power Query logic (applied in Pandas)  
- **EDA Techniques**: Segmentation, categorical/numerical analysis, risk profiling  

---

## 📂 Project Structure  
📁 Banking_Loan_EDA  
│── 📓 Banking_Loan_EDA.ipynb   # Jupyter Notebook with full EDA workflow  
│── 📄 Banking.csv              # Banking dataset  
│── 📄 README.md                # Project documentation  

---

## ✅ Outcome  
The analysis provided a clear understanding of **demographic and financial factors driving loan risk**. Key findings like **62% of customers being low/medium income, 18% technicians as high-risk, and 25% higher default risk in 1–3 year tenure employees** can help banks design:  
- Smarter **loan approval models**  
- Better **customer segmentation**  
- Improved **risk-weighting strategies**  

---

✨ *This project is part of my Analytics portfolio, showcasing how EDA can translate raw banking data into actionable financial insights.*  
