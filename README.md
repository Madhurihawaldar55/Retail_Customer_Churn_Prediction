# Retail_Customer_Churn_Prediction

### Background Information
​Welcome—we’re excited you’re here.

​BCG X is the tech build and design unit of BCG where our teams combine cutting-edge technology, data science, and human-centered design to build and scale the bold ideas that deliver real impact for our clients. Today, you’ll be stepping into the shoes of a BCG X Data Scientist to gain first-hand experience solving complex problems at the intersection of business, data, and technology.

​In this simulation, you’ll be working with a case team to help a client, PowerCo, investigate a problem with customer churn. PowerCo suspects price sensitivity is driving their customers to switch providers—the data tells a more complex story. Your job is to dig into the data, develop hypotheses, build predictive models, and translate your insights into strategic recommendations.

### Project Overview
- This project focuses on predicting customer churn in a retail/energy dataset using machine learning techniques.
- The goal is to identify customers who are likely to leave, helping businesses take proactive retention actions.
### Objectives
- Analyze customer data and identify churn patterns
- Handle data quality issues and missing values
- Perform feature engineering for better predictions
- Build and evaluate a churn prediction model
### Dataset Description
- client_df → Customer information
- price_df → Pricing details (off-peak, peak, mid-peak)
### Key Insights
- Data Quality
   * No duplicate records found
   * Missing values present in some categorical features
   * Data cleaned and converted appropriately
### Churn Distribution
- around 9.7% customers churned
- 90.3% customers retained
- Significant class imbalance observed
### Feature Insights
- Consumption features are highly skewed
- Log transformation used to normalize data
- Price features vary across different periods
### Categorical Insights
- Certain sales channels dominate
- Customers with gas contracts show lower churn
- Some categories have higher churn rates
### Feature Engineering
- Created time-based features (tenure, months active)
- Built consumption ratios and per-day metrics
- Generated price difference features
- Applied one-hot encoding for categorical variables
- Log transformation for skewed numerical features
### Correlation Analysis
- Low linear correlation with target variable
- Indicates non-linear relationships
- Removed highly correlated features to avoid multicollinearity
### Model Building
- Model Used: Random Forest Classifier
- Accuracy: 90%
- Recall for churn class: Very Low (5.7%)
