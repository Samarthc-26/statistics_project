# Atliqo Bank Project: Credit Card Launch Target Market Analysis

## Project Overview

The Atliqo Bank project focuses on identifying and analyzing the target market for the launch of a new credit card. The goal is to target an untapped market segment, primarily customers aged 18-25, and validate the assumptions using statistical analysis.

## Project Phases

### Phase 1: Data Collection, Cleaning, and Analysis

#### Datasets Used:

1. `customer.csv`
2. `credit_profiles.csv`
3. `transaction.csv`

#### Key Tasks:

1. **Data Cleaning:**

   - Handled null values, duplicates, and outliers across 50,000 entries.
   - Ensured data consistency and integrity for further analysis.

2. **Exploratory Data Analysis (EDA):**

   - Conducted descriptive statistics and visualizations to understand customer behavior.
   - Identified key patterns and trends in the data.

3. **Data Visualization:**

   - Visualized customer demographics, credit profiles, and transaction patterns using tools like Matplotlib and Seaborn.

4. **Feature Engineering:**

   - Engineered new features to better define the target market segment.

#### Insights:

- Customers aged **18-25** account for approximately **26%** of the customer base.
- This group has an average annual income of less than **\$50,000**.
- Limited credit history is reflected in lower credit scores and credit limits.
- Credit card usage is relatively low in this group.
- Top shopping categories for this group:
  1. Electronics
  2. Fashion & Apparel
  3. Beauty & Personal Care

### Phase 2: Statistical Analysis and Hypothesis Testing

#### Key Tasks:

1. **Statistical Measures:**

   - Performed Z-tests to validate hypotheses about the target group.

2. **Hypothesis Testing:**

   - Used the `statsmodels` library's `ztest` function for statistical testing.

#### A/B Testing:

- Conducted an A/B test comparing the performance of the old credit card (control group) versus the new credit card (test group).
- Results:
  - Z-score: **2.74**
  - P-value: **0.0030**
  - Significance Level: **5%**
  - Z-critical: **1.644**
- Conclusion: Since the Z-score of 2.74 exceeds the Z-critical value of 1.644, and the p-value is less than 0.05, the test results are statistically significant, indicating that the new credit card outperforms the old credit card.

#### Results:

- Validated the hypothesis that the 18-25 age group represents an untapped market segment for credit card usage.
- Confirmed statistically significant differences in transaction patterns and income levels compared to other groups.

## Outcomes

- Identified an untapped market segment (age 18-25) with potential for targeted credit card marketing.
- Validated assumptions through robust statistical analysis.
- Provided actionable insights for product design and marketing strategies.



