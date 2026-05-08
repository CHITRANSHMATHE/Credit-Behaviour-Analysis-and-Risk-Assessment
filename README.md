# Credit-Behaviour-Analysis-and-Risk-Assessment
Credit Behaviour Analysis and Risk Assessment project using Python, Pandas, and Seaborn to analyze customer credit activity, loan approvals, spending behavior, risk profiling, and customer segmentation through EDA and feature engineering.

This project focuses on analyzing customer credit behavior, loan application trends, spending patterns, and risk profiling using real-world styled banking datasets. The objective is to improve loan approval strategies, identify high-risk clients, and generate business-driven insights through Exploratory Data Analysis (EDA), Feature Engineering, and Advanced Risk Analysis.

The project follows a complete data analytics workflow:
- Data Understanding
- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Risk Profiling
- Customer Segmentation
- Advanced Business Insights

---

# Objectives
- Validate client consistency across multiple datasets
- Detect duplicate and missing financial records
- Identify outliers and inconsistent credit behavior
- Analyze loan approval trends
- Understand credit utilization and enquiry behavior
- Segment customers based on risk and engagement
- Generate actionable recommendations for lending strategies

---

# Dataset Information

The analysis uses three datasets:

| Dataset | Description |
|---|---|
| `tradeline_data` | Customer credit tradeline information |
| `enquiry_data` | Customer credit enquiry records |
| `base_file` | Loan application and approval information |

Key Features:
- `Client_ID`
- `Total_Tradelines_6m_In`
- `Total_Tradelines_1y_In`
- `Total_Enquiry_6m_In`
- `Total_Enquiry_1y_In`
- `Max_Trade_3m_Out`
- `Applied`
- `Approved`

---

# Project Workflow

## 1. Data Understanding
- Client coverage validation
- Duplicate record analysis
- Missing value analysis
- Logical consistency checks
- Outlier detection using IQR

## 2. Data Cleaning
- Missing value imputation
- Datatype standardization
- Negative value handling
- Winsorization using 99th percentile
- Final integrity validation

## 3. Exploratory Data Analysis
- Distribution analysis
- Histograms and KDE plots
- Correlation analysis
- Scatter plots
- Loan approval trends
- Spending behavior analysis

## 4. Feature Engineering
Created new business-focused features:
- Loan Approval Rate
- Credit Utilization Rate
- Weighted Enquiry Score
- Application Frequency
- Credit Activity Segments
- Risk Profiles

## 5. Advanced Analysis
- Customer segmentation
- Risk classification
- Approval trend analysis
- Engagement analysis
- Spending vs approval analysis

---

# Key Insights

## Credit Behaviour Insights
- Most customers belong to the medium credit activity segment.
- Higher tradeline activity is associated with higher loan application frequency.
- Credit enquiries and tradeline activity show a positive relationship.
- A small group of clients demonstrates extremely high credit engagement and spending behavior.

## Loan Approval Insights
- Loan approval behavior varies significantly across customer segments.
- High-frequency applicants often show different approval patterns compared to low-frequency applicants.
- Spending behavior impacts approval trends but is not the only determining factor.

## Risk Analysis Insights
- Clients with high tradelines and high spending exhibit elevated financial risk.
- High credit utilization may indicate financial stress or aggressive borrowing behavior.
- Frequent credit enquiries can act as strong indicators of increased credit dependency.

## Customer Segmentation Insights
- Customer segmentation successfully identified low, medium, and high-risk profiles.
- Medium engagement customers form the largest client group.
- Highly engaged clients may represent opportunities for premium financial products.

---

# Recommendations

## Data Quality Improvements
- Implement stricter validation checks during data collection.
- Automate anomaly detection for inconsistent financial records.
- Standardize data formats before storage.

## Credit Risk Strategy
- Use enquiry frequency, tradeline activity, and utilization rate in credit scoring systems.
- Closely monitor high-risk customers with excessive credit activity.
- Develop early-warning systems for abnormal credit behavior.

## Loan Approval Optimization
- Apply segment-based approval strategies.
- Introduce stricter checks for high-frequency applicants.
- Improve underwriting decisions using behavioral analytics.

## Customer Engagement
- Target medium and high-engagement customers with personalized financial products.
- Use segmentation for marketing and retention strategies.
- Improve financial education initiatives for low-engagement customers.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# Concepts Applied

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Risk Profiling
- Customer Segmentation
- Correlation Analysis
- Outlier Detection
- Winsorization
- Business Analytics

---

# Visualizations Included
- Histograms
- KDE Plots
- Scatter Plots
- Count Plots
- Bar Charts

---

# Future Improvements
- Build predictive loan approval models
- Implement credit risk scoring models
- Create interactive dashboards using Power BI or Tableau
- Deploy the project using Streamlit
- Apply machine learning algorithms for risk classification

---

# Conclusion
This project demonstrates a complete end-to-end banking analytics workflow using Python and Pandas. Through data cleaning, exploratory analysis, feature engineering, and customer segmentation, the project uncovers critical insights into credit behavior, spending patterns, loan approvals, and financial risk. The findings can support better lending decisions, improve customer profiling, and enhance risk management strategies in the banking sector.
