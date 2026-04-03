# Retail Profit Optimisation

**Tools:** Python | Tableau  
**Skills:** Predictive Modelling | Profit Analysis | 
Customer Retention Analysis

---

## Project Overview

This project analyses the impact of discount strategies on profit 
and customer retention for an Australian online activewear retailer. 
Using a dataset of 9,131 customers and 12,011 orders recorded between 
October 2023 and May 2025, the analysis examines coupon behaviour, 
repeat purchase patterns, and the long-term value of discounting.

---

## Interactive Dashboard

[View Tableau Dashboard](https://public.tableau.com/views/DiscountStrategyProfitAnalysis/Coupon_Story?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Key Findings

- Sales peaked in November and December 2024, with NSW and Victoria 
  as the strongest regions
- 34.83% of all orders used a coupon, with ROOSTER15 dominating 
  repeat customer usage
- Repeat customers have very high retention regardless of discount 
  level — discounts do not meaningfully improve loyalty
- First-order customers are more sensitive to discounts, making 
  coupons more effective as an acquisition tool
- Higher discounts consistently reduce profit — a 50% discount 
  cuts expected value by approximately 75%

---

## Predictive Models

| Model | Target | Performance |
|---|---|---|
| Random Forest | Predict repeat purchase | Accuracy = 81%, AUC = 0.81 |
| Linear Regression | Predict profit per order | Profit drops consistently as discount increases |

---

## Expected Value Analysis

Combined profit and repeat probability to evaluate long-term 
discount impact:

| Discount Level | Expected Value |
|---|---|
| 0% | ~21.5 (highest) |
| 10-20% | ~25-30% reduction |
| 50% | ~5.8 (lowest, -75%) |

---

## Recommendations

- Use discounts mainly to attract and convert new buyers, 
  not to retain existing ones
- Avoid deep discounts for returning customers as retention 
  is already high
- Discounts above 20% significantly erode profit without 
  improving loyalty
- Focus on margin-driven strategies such as product quality 
  and personalised follow-ups

---

## Repository Contents

| File | Description |
|---|---|
| `Discount_Strategy_Profit_Analysis.ipynb` | Data cleaning, EDA, Random Forest and profit modelling |
