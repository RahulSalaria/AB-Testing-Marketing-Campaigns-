# AB-Testing-Marketing-Campaigns-

This project evaluates the effectiveness of Facebook and  AdWords campaigns using A/B testing to determine which platform yields better conversions, clicks, and cost-effectiveness.

🧠 Business Problem
As a marketing agency, the goal is to maximize ROI across ad platforms. This project uses campaign data to compare Facebook Ads and Google AdWords in terms of:

📈 Click-throughs

💰 Conversions

🧮 Cost efficiency

❓ Research Question
Which ad platform—Facebook or Google AdWords—is more effective in conversions, clicks, and ROI?

📁 Dataset
Source: marketing_campaign.csv

Contains features such as:

Date

Facebook Ad Clicks

Facebook Ad Conversions

Google Ad Clicks

Google Ad Conversions

Cost

📊 Methodology
Data Cleaning & Formatting (e.g., parsing dates)

Exploratory Data Analysis (EDA)

Lift and Uplift Calculations

Time-Series Decomposition

Statistical Testing (e.g., A/B testing, Cointegration test)

Regression Analysis for Trend Prediction

📦 Technologies Used
Python

pandas, numpy

matplotlib, seaborn

scipy, statsmodels

sklearn

📌 Key Insights
Facebook Ads showed higher immediate conversions, while AdWords had consistent engagement over time.

Uplift metrics were used to measure incremental improvement.

Seasonal decomposition and cointegration tests offered insights into long-term performance alignment
