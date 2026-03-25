# E-commerce User Behavior Analysis

## Objective
The purpose of this project is to analyze user behavior in an e-commerce dataset and identify patterns in conversion, category performance, and purchase behavior.

## Business Question
How can we improve conversion rates and better understand user behavior across the funnel (view → cart → purchase)?

## Dataset
The dataset contains event-level data, where each row represents a user interaction:
- view
- cart
- purchase

Data includes product information, categories, prices, and user activity.

## Key Analyses

### 1. Funnel Analysis
- Large drop-off from view → cart → purchase
- Opportunity to improve early-stage conversion

### 2. Category Analysis
- Some high-traffic categories have low conversion
- Indicates potential UX or pricing issues

### 3. Price vs Conversion
- Weak relationship between price and conversion
- Suggests other factors (brand, intent, category) matter more

### 4. User Behavior
- Returning users convert slightly more than first-time users
- Indicates importance of retention strategies

### 5. Cohort Analysis
- Low retention (~3.5% from October → November)
- Highlights need for re-engagement strategies

## Key Insights
- Conversion is mainly lost early in the funnel
- Retention is low but important
- Price alone does not explain purchasing behavior

## Tools Used
- Python (pandas, numpy, matplotlib)
- Jupyter Notebook

## Limitations

- The dataset is event-based, meaning multiple events per user are possible. Funnel metrics are therefore event-level, not strict user-level conversion rates.

- Cohorts are based on first observed activity within the dataset, not necessarily truly new users.

- Balanced sampling was used to ensure equal representation across months, which may affect absolute counts but improves comparability.

## Author
Vafa Nasirova


