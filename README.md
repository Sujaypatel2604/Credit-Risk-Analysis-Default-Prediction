📊 Credit Risk Analysis & Default Prediction

📌 Project Overview

This project analyzes credit card customer data to identify key drivers of default risk and build a predictive model for credit default prediction.
The objective is to help financial institutions:
Identify high-risk customers early
Reduce credit default losses
Improve credit approval decisions
Optimize credit risk strategy

The project combines exploratory data analysis, feature engineering, and logistic regression modeling to generate business-driven insights.

🎯 Business Problem
Credit defaults lead to significant financial losses for banks.
This project helps improve decision-making by predicting default probability and identifying key risk factors influencing customer behavior.

📂 Dataset Source
UCI Machine Learning Repository
Credit Card Default Dataset
Includes customer demographics, credit limits, repayment history, and default status.

⚙️ Tools & Technologies
Python (Pandas, NumPy)
Matplotlib & Seaborn
Scikit-learn
Logistic Regression
Jupyter Notebook

🔍 Key Analysis Performed
Data cleaning and preprocessing
Feature engineering (age groups, credit utilization, risk segments)
Default rate analysis by:
Credit limit
Age group
Repayment behavior
Credit utilization
Payment delay history

Credit exposure and risk contribution analysis
Correlation analysis to identify key predictors
Predictive modeling using Logistic Regression
Model evaluation using ROC curve and confusion matrix
Cost-based threshold optimization

📊 Key Insights
Repayment behavior is the strongest predictor of default
High credit exposure increases financial risk
Higher credit utilization leads to higher default probability
Demographic factors improve risk segmentation
Behavioral features significantly improve prediction accuracy

🤖 Model Performance
Overall Default Rate: 22.12%
Model: Logistic Regression
ROC–AUC Score: 0.748
Optimal Threshold: 0.3

Estimated Loss Reduction: ~29% vs default threshold

💼 Business Recommendations
Prioritize repayment behavior in credit approval decisions
Implement risk-based credit limits
Deploy optimized threshold (0.3) to reduce losses
Monitor high-risk customers proactively
Apply customer risk segmentation strategy

🚀 Business Impact
Reduced default risk exposure
Improved credit approval strategy
Better customer risk profiling
Data-driven financial decision making
