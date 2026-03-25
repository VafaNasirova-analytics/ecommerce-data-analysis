# E-commerce User Behavior Analysis

## Objective
The purpose of this project is to analyze user behavior in an e-commerce dataset and identify patterns in conversion, category performance, and purchase behavior.

## Business Question
How can we improve conversion rates and better understand user behavior across the funnel (view → cart → purchase)?

---

## Dataset
The dataset contains event-level data where each row represents a user interaction:
- View
- Cart
- Purchase

It includes product details, category information, prices, and user activity.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Key Analyses

### 1. Funnel Analysis
- Significant drop-off from **view → cart → purchase**
- Indicates friction early in the user journey

### 2. Category Analysis
- Some high-traffic categories have low conversion
- Suggests potential issues in pricing, UX, or product positioning

### 3. Price vs Conversion
- No strong relationship between price and conversion
- Indicates that other factors (brand, intent, category) are more important

### 4. User Behavior
- Returning activity shows slightly higher conversion than first observed activity
- Suggests trust and familiarity impact purchasing decisions

### 5. Cohort Analysis
- Retention from October → November is ~3.5%
- Indicates strong drop-off in user activity over time

---

## Key Insights
- Conversion loss occurs primarily at early funnel stages
- Retention is low but critical for long-term growth
- Price alone does not explain purchasing behavior
- Returning users are more likely to convert

---

## Limitations
- The dataset is event-based, meaning multiple events per user are possible. Funnel metrics are therefore event-level, not strict user-level conversion rates.
- Cohorts are based on first observed activity within the dataset, not necessarily truly new users.
- Balanced sampling was used to ensure equal representation across months, which may affect absolute counts but improves comparability.

---

## Future Work
- Perform **user-level funnel analysis** (unique users instead of events)
- Apply **A/B testing framework** for conversion improvements
- Build **predictive models** for purchase probability
- Segment users (e.g., high-value vs low-value customers)
- Analyze **time-to-purchase behavior**
- Incorporate **brand-level analysis**
- Use larger datasets for more robust conclusions

---

## 👤 Author
**Vafa Nasirova**  
Data Analyst / Statistician   
📍 Gothenburg, Sweden  

---

## 🔗 Project Link
👉 https://github.com/VafaNasirova-analytics/ecommerce-data-analysis

