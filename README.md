# ELEVATELABS--TASK-5-customer-shopping-behavior-EDA
Exploratory Data Analysis on customer shopping behavior — uncovering purchasing patterns, demographics, and category/payment trends to drive business recommendations for a retail company.
Customer Shopping Behavior — Exploratory Data Analysis (EDA)

Exploratory Data Analysis on a retail customer shopping dataset to uncover purchasing patterns, customer preferences, and the factors that drive buying decisions — with actionable business recommendations.

Project Type

EDA · Individual Contribution

Tools & Libraries


Python
Pandas
Matplotlib
Seaborn
Google Colab


Problem Statement

A leading retail company wants to understand customer shopping behavior to improve business performance, customer satisfaction, and long-term loyalty. This project explores how factors like age, gender, product category, season, discounts, payment method, and review ratings influence purchase amount and repeat buying behavior.

Business Objective

Analyze customer shopping behavior to uncover patterns in demographics, product categories, purchase amounts, shopping frequency, payment methods, discounts, and seasonal trends — helping the company optimize marketing, improve inventory planning, personalize customer experience, and design targeted promotions.

Dataset


Records: 3,900 customers
Columns: 18
Missing values: 37 in Review Rating (0.95%), imputed with median
Duplicates: 0




Approach


Know Your Data — .shape, .info(), duplicate & missing-value checks
Understand Your Variables — .describe(), .nunique(), variable descriptions
Data Wrangling — cleaned copy of dataset, median imputation for missing review ratings
Data Visualization — 15 charts covering univariate, bivariate, and multivariate analysis (histograms, count plots, boxplots, bar plots, correlation heatmap, pair plot)
Business Insights — observations and impact written for every chart


Key Findings


Customer base skews male (~68%) and middle-aged; purchase amount doesn't differ much by gender.
A clear subset of product categories drives most purchase volume and revenue.
Seasonality is mild — no single season dominates.
Payment method and shipping type usage are concentrated in a few preferred options.
Subscription adoption is low — a clear untapped retention opportunity.
Discounts and promo codes are used in a large share of transactions, showing strong price sensitivity.
Review ratings skew positive-to-moderate overall satisfaction.
Numerical variables (Age, Purchase Amount, Review Rating, Previous Purchases) show negligible correlation with each other — segmentation should rely on categorical behavior rather than numeric relationships.


Business Recommendations


Prioritize inventory and promotion around top-performing categories.
Grow the subscription base with stronger incentives (free shipping, early access, subscriber-only discounts).
Use discounts/promo codes strategically rather than as a default, to protect margins.
Streamline checkout around the most-used payment and shipping options.
Align inventory and campaigns with seasonal demand patterns.
Monitor low review ratings proactively to reduce churn risk.
Build customer segments from purchase amount, review rating, and purchase history for personalized marketing.


Conclusion

The analysis shows fairly consistent purchasing behavior across demographics, with clear differentiation at the category, payment, shipping, and promotion level. The biggest opportunities are boosting subscription adoption and using discounts/promo codes more strategically, while continuing to prioritize top-performing categories and preferred payment/shipping channels.

How to Run


Clone this repository.
Open CUSTOMER_SHOPPING_BEHAVIOUR_.ipynb in Jupyter Notebook or Google Colab.
Place the dataset CSV in the working directory (update the file path in the notebook if needed).
Run all cells to reproduce the analysis and visualizations.


Author

Individual contribution — Customer Shopping Behavior EDA Capstone Project.
