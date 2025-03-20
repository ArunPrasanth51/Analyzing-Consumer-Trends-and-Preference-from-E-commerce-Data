# Analyzing-Consumer-Trends-and-Preference-from-E-commerce-Data
Overview

E-commerce has transformed the retail landscape, generating vast amounts of consumer data. This project aims to analyze consumer trends and preferences using machine learning techniques. By leveraging data preprocessing, exploratory data analysis (EDA), and classification models, valuable insights are extracted to help businesses optimize their inventory, pricing, and marketing strategies.

Objectives

Identify key trends in consumer preferences, including best-selling products and seasonal shopping patterns.

Examine the impact of pricing, product categories, and geographical location on customer decisions.

Implement machine learning models (Random Forest and Decision Tree) to predict consumer behavior and classify purchasing patterns.

Provide data-driven recommendations for businesses to enhance marketing strategies and improve customer experience.

Dataset

Source: Kaggle (E-commerce transaction records)

Size: 228,975 records with 17 features

Key Features:

Order details (Order ID, Purchase Date, Sales Channel)

Customer information (Shipping City, State, Country)

Product information (Category, Fulfillment Type, Courier Status)

Transaction details (Sales Figures, Order Volume, Return Status)

Technologies Used

Programming Language: Python 3.x

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, imblearn, graphviz

Development Tools: Jupyter Notebook, VS Code, Google Colab

Methodology

Data Preprocessing

Handling Missing Values: Missing values were identified and addressed using mean imputation and mode replacement.

Removing Outliers: The Interquartile Range (IQR) method was applied to detect and remove extreme values.

Encoding Categorical Variables: Label encoding was used to convert categorical data into numerical format.

Feature Scaling: Standardization (StandardScaler) was applied to improve model performance.

Handling Class Imbalance: Oversampling (Random Over Sampling) was used to balance the dataset.

Data Splitting: The dataset was divided into 80% training and 20% testing sets.

Exploratory Data Analysis (EDA)

Customer Purchase Behavior: Analysis of product demand, preferred categories, and seasonal variations.

Sales Trends Over Time: Identification of peak sales periods and promotional effects.

Geographical Analysis: Study of order distribution by region to optimize logistics and marketing efforts.

Machine Learning Models

1. Random Forest Classifier

Used for predicting customer preferences and analyzing influential sales factors.

Trained with 100 estimators and achieved an accuracy of 80%.

2. Decision Tree Classifier

Applied for classifying product categories with hyperparameter tuning.

Achieved an improved accuracy of 94%, outperforming Random Forest.

Feature importance analysis provided insights into sales-driving factors.

Key Findings

High-Demand Products: Certain categories consistently perform better, requiring focused inventory management.

Seasonal Demand: Sales spike during promotional events and holiday seasons.

Pricing Sensitivity: Customers are influenced by discounts and price variations.

Geographical Preferences: Urban areas generate higher sales volume, emphasizing location-based marketing strategies.

Customer Loyalty: Repeat purchases indicate brand trust, highlighting the need for loyalty programs.

Results & Business Impact

Improved Decision-Making: Data-driven insights assist businesses in optimizing sales and marketing strategies.

Better Inventory Management: Understanding seasonal demand helps in maintaining optimal stock levels.

Enhanced Customer Engagement: Personalized recommendations and promotional campaigns improve customer satisfaction.

Installation & Usage

Clone the repository:

Install required dependencies:

Run the Jupyter Notebook to execute the analysis:

Future Enhancements

Implement deep learning models for better classification accuracy.

Use time-series forecasting for sales predictions.

Expand the dataset to include real-time consumer behavior trends.
