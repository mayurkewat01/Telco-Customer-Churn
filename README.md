Telco Customers Churn

Project Introduction
This report provides insights into customer churn for a telecom company. The goal is to identify patterns and segments where churn is more likely to occur, and to uncover the underlying reasons behind customer dissatisfaction. This project involved cleaning and preparing the dataset, performing exploratory data analysis (EDA), visualizing key variables, and deriving recommendations based on observed churn behavior. These findings aim to support the business in improving customer retention strategies.

Data Overview
• The dataset includes customer demographics, contract details, payment methods, and services used, with around 7,000 records.
• The target variable is 'Churn', indicating whether a customer left the service (Yes/No).
• The dataset has a mix of numerical (e.g., tenure, MonthlyCharges) and categorical columns (e.g., Contract, PaymentMethod).
• No missing values were found, and the dataset was clean and ready for analysis.

Data Preparation
• Imported libraries: pandas, numpy, matplotlib, seaborn for analysis and visualization.
• Loaded the dataset using pandas.read_csv().
• Converted 'TotalCharges' to numeric and handled any parsing issues.
• Dropped unnecessary columns like 'customerID'.
• Identified and encoded categorical columns for analysis.

Exploratory Data Analysis (EDA)
• Checked data types and ensured numeric and categorical features were correctly identified.
• Used value_counts() to study distribution of churn across different features.
• Investigated patterns in features such as Contract, InternetService, OnlineSecurity, and PaymentMethod to understand churn trends.

Data Visualization
• Stacked bar charts for churn across contract types, internet services, and features like tech support, streaming, and backups.
• Pie chart to represent churn distribution by payment method.
• Count plots to visualize the number of customers who churned or stayed based on different service attributes.
• Correlation matrices and bar charts for numeric fields to identify patterns in tenure, charges, and churn.

Key Findings from EDA and Visualizations
• Month-to-month contract customers churn the most.
• Fiber optic internet users have higher churn rates than DSL users.
• Customers without online security, backup, or tech support services are more likely to churn.
• Electronic check users represent the largest share of churned customers.
• Longer contracts and automatic payment methods are associated with reduced churn.
• Bundled services like streamingTV and device protection improve retention.

Recommendations for Improvement
• Encourage customers to shift to long-term contracts with discounts or loyalty points.
• Offer bundled packages that include online security, backup, and tech support to increase retention.
• Discourage use of electronic checks by offering cashback or incentives for automatic payments.
• Focus marketing and retention efforts on month-to-month and fiber optic users.
• Use predictive modeling in future to proactively identify high-risk churn customers.

Conclusion
This telecom churn analysis project revealed several key drivers of customer attrition through comprehensive EDA and visualization. By identifying patterns tied to contract type, internet service, support services, and payment method, the business can take focused actions to reduce churn. These insights provide a strong foundation for building targeted retention strategies that enhance customer loyalty and overall satisfaction.
