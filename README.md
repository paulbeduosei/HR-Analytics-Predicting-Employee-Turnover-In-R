# HR-Analytics-Predicting-Employee-Turnover-In-R

📌 Project Overview
This project was completed for an HR client looking to understand employee turnover drivers and reduce the cost of attrition. Using employee records, performance ratings, and manager surveys, I built a predictive model to identify employees at risk of leaving.

📂 Data Sources
org.csv – employee demographics, compensation, location, level, and status

rating.csv – employee and manager performance ratings

survey.csv – manager effectiveness and satisfaction scores

🛠️ Tools Used

R (dplyr, ggplot2, caret, Information, tidypredict)

Logistic regression

Exploratory Data Analysis (EDA)

# Feature engineering

🔍 Step-by-Step Process (What & Why)

1️⃣ Data Integration
Datasets were joined using employee and manager IDs to create a single source of truth.
📌 Why: Turnover depends on multiple factors, not one dataset alone.

2️⃣ Turnover Exploration

Turnover rates were calculated by:

Status (Active vs Inactive)

Level

Location
📌 Why: Identifies departments and roles with higher attrition risk.

3️⃣ Feature Engineering
New variables were created:

Tenure → measures employee stability

Age difference → explores manager-employee dynamics

Job hop index → captures career movement patterns

Compa-ratio → evaluates pay fairness
📌 Why: These variables reveal hidden behavioral and financial drivers.

4️⃣ Compensation & Satisfaction Analysis

Compared salary, promotions, satisfaction, and manager effectiveness across active and inactive employees.
📌 Why: Low satisfaction and unfair pay are strong predictors of turnover.

5️⃣ Predictive Modeling

A logistic regression model was built to predict employee turnover.

Multicollinearity was addressed using VIF, and the model was refined for stability.
📌 Why: Predictive models help HR act before employees leave.

6️⃣ Model Validation

Train/Test split (70/30)

Confusion matrix evaluation

Final accuracy: 93.35%
📌 Why: Ensures predictions are reliable and not overfitted.

7️⃣ Risk Segmentation

Active employees were classified into:

No risk

Low risk

Medium risk

High risk
📌 Why: Allows HR to target retention strategies effectively.

8️⃣ Business Impact & ROI

I calculated the return on investment of increasing salaries vs. replacing employees.
📌 Insight: Small pay increases can significantly reduce turnover costs.

📊 Key Insights

Analysts and specialists showed higher turnover risk

Employees with low compa-ratio and low satisfaction were more likely to leave

Manager effectiveness strongly influenced retention

Proactive retention strategies showed positive ROI

🎯 Why This Project Matters

This project demonstrates my ability to:

Work with real HR data

Build predictive models

Explain insights in business terms

Support data-driven decision-making
