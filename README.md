# customer-churn-prediction

LAB of Information Systems and Analytics Dayana Amanzhol · Aiday Karazhan 
Business Context

Customer churn — a customer canceling a subscription or leaving a service — is one of the most costly problems in telecommunications. Acquiring a new customer costs five to ten times more than retaining an existing one, making proactive retention far more valuable than reactive recovery. A reliable churn model lets a company identify at-risk customers before they leave and intervene with targeted offers: a contract upgrade incentive, a pricing adjustment, or a proactive support call.

Project Objective

This project builds an end-to-end binary classification pipeline on the IBM Telco Customer Churn dataset (7,043 customers, 20 features), covering the full CRISP-DM cycle from data exploration through modeling, evaluation, and error analysis. Three models are trained and compared — Logistic Regression, Random Forest, and XGBoost — using ROC-AUC and recall as the primary metrics, reflecting the asymmetric cost of missing a churner versus sending an unnecessary retention offer.

