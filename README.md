# 📊 Marketing Campaign Analysis with Pandas

## Key Focus Areas:
- **Conversion Rates**
- **Retention Rates**
- **Segmentation**
- **Data Visualization**
- **Attribution**
- **A/B Testing**

## 📘 Project Overview

Dive into the world of marketing campaign data from a hypothetical online subscription business. Using Python and Pandas, we translate common business questions into measurable outcomes, uncovering insights about campaign performance, referral channels, and underperformance causes.

### What We Did:
- **Data Assessment:** Evaluate the content and quality of the dataset.
- **Feature Engineering:** Create new columns to enrich the data.
- **Automation:** Develop functions for retention, conversion, and segmentation analysis.
- **User Segmentation:** Visualize results to highlight differences between user groups.
- **Campaign Diagnosis:** Identify and address issues within the campaign.
- **A/B Testing Analysis:** Determine statistical significance using lifts and t-tests.

## 📚 Python Libraries Utilized:
- **pandas**
- **numpy**
- **matplotlib**
- **scipy**

## 🚧 Challenges and Solutions

One significant challenge was an anomalously high retention rate (~680%). After double-checking the code and equations, the root cause was identified as a data type conversion issue. The 'is_retained' column, initially of type object, was incorrectly converted to bool, with missing values turning into True/False. This was resolved by using `fillna(False)` to handle missing values correctly.

## 🚀 Results

This analysis provides a robust framework for assessing and improving marketing campaigns, ensuring data-driven decision-making and insightful business strategies.

Feel free to explore, fork, and contribute to this project! Your feedback and suggestions are always welcome. Happy analyzing!

---

> **Note:** This README is a guide to understanding the project's scope, methodology, and outcomes. For detailed code and further information, please refer to the respective sections in the repository.
