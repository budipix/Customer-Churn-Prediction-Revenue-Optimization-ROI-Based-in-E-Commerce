# Customer-Churn-Prediction-Revenue-Optimization-ROI-Based-in-E-Commerce
This project analyzes and predicts customer churn in an e-commerce platform using XGBoost. By identifying high-risk and high-value customers, it enables targeted retention strategies that reduce inefficiencies in promotional spending, with a potential revenue recovery of up to $48.4M and improved overall ROI.

Problems:
1. High churn rate across customers
2. Inefficient promotional spending
3. Difficulty identifying high-value customers at risk
   
Objectives:
1. Identify customers with high churn risk
2. Analyze key factors driving churn behavior
3. Build a predictive model for churn classification
4. Design targeted retention strategies

Exploratory Data Analysis (EDA):
1. Customers inactive for >15 days: 93.4% churn rate
2. Low interaction users (0–5 interactions): 91.2% churn
3. Engagement is a stronger driver than revenue

Models used:
1. Logistic Regression
2. Random Forest
3. XGBoost (Best Model)

Model optimization:
1. Grid Search CV
2. Randomized Search CV

Model Performance (XGBoost):
1. Precision (Churn Class): 93%
2. Recall: 74%
3. Successfully identified 9,700+ high-risk customers

Insight:
1. Churn is primarily driven by low engagement, not low spending
2. Customers who rarely log in are significantly more likely to churn
3. A small group (~0.85%) contributes ~80% of total revenue

Business Impact:
1. Potential revenue loss: $380M+
2. Optimized strategy targets Top 5% high-risk customers
3. Estimated revenue saved: $48.4M
4. Net profit improvement: $48.3M

Recommendations:
1. Focus on high-value & high-risk customers
2. Replace mass promotions with targeted campaigns
3. Improve user engagement (login frequency, interaction)
