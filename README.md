#  Employee Sentiment Analysis Summary

## Overview

This project analyzes the internal communication sentiment of 10 employees, based on 2,191 messages. The goal was to assess emotional tone, rank engagement, and identify potential flight risks using sentiment classification, visualization, and predictive modeling.

# Instruction：
Original data :test.csv

Run the notebooks sequentially

Task 1: Sentiment Labelling.Uses cardiffnlp/twitter-roberta-base-sentiment from Hugging Face to label each email.
  Output: sentiment_practice_output.csv with sentiment scores.

Task 2: Explore sentiment trends.
  
Task 3: Calculate sentiment scores per employee.  
  Output：monthly_employee_scores.csv
  
Task 4: Rank employees based on sentiment.

  Output:top_negative_employees.csv;top_positive_employees.csv
  
Task 5: Detect flight risks using rolling analysis.

Task 6: linear regression to predict future sentiment trends.

### Sentiment Distribution:
- **Neutral**: 1,485 messages (67.8%)
- **Positive**: 558 messages (25.5%)
- **Negative**: 148 messages (6.7%)

Based on monthly cumulative sentiment scores:

### Top Positive Employees:
1. **Sally Beck**
2. **Eric Bass**
3. **Bobette riner**

These employees consistently exhibited high levels of positive sentiment in their communications.


##  Flight Risk Employees

The following employees were flagged for sending **4 or more negative messages within any 30-day rolling period**:

- **Bobette Riner**
- **Don Baughman**
- **John Arnold**
- **Sally Beck**

These individuals may be experiencing dissatisfaction or stress and warrant further HR or managerial attention.


##  Key Insights

- Most messages were **neutral**, suggesting a predominantly informational communication style.
- A few employees showed **disproportionately high negative tone**, which correlates with flight risk.
- **Lydia Delgado**, **John Arnold**, and **Patti Thompson** were the top communicators, based on message volume.
- Predictive modeling using linear regression achieved strong results:
  - **R² = 0.950**
  - **RMSE = 0.0096**



---
