# Credit Line Increase Eligibility Analysis  
A Python based exploration of responsible growth strategies for credit products

## Overview  
This project simulates how financial institutions evaluate customers for credit line increases. Using a synthetic dataset of two hundred customers, I analyzed credit scores, utilization rates, on time payment behavior, spend patterns, and tenure to determine which customers qualify for a safe and responsible credit line increase.  

The goal is to understand how credit teams balance growth with credit risk and how product teams can design features that improve customer experience and drive healthy engagement.

---

## Business Problem  
Credit line increases support multiple goals for card products:
- higher monthly spend  
- stronger engagement  
- lower churn  
- better long term customer value  

However, offering a credit line increase to the wrong customer increases risk exposure, charge offs, and delinquency.  
This project evaluates which customers show financially healthy behavior and which customers present risk indicators that should delay or prevent a credit line change.

---

## Dataset  
The dataset includes two hundred synthetic customers with fields commonly used in credit line increase decisions:

- customer id  
- credit score  
- utilization rate  
- on time payment rate  
- monthly spend  
- account tenure  

These attributes reflect the real variables financial institutions consider when determining credit eligibility.

---

## Python Analysis  
Python was used to:
- generate the dataset  
- define simple eligibility rules  
- calculate eligibility rates  
- compare behavior of eligible and non eligible customers  
- group customers by tenure, score, and utilization  
- visualize distribution patterns and risk signals  

The core eligibility logic evaluates:
- credit score above 680  
- utilization below 0.60  
- on time payments above 0.90  
- tenure greater than twelve months  

These rules simulate responsible credit policy design.

---

## Visualizations  
This project includes several charts to explore eligibility patterns:
- credit score distribution  
- utilization distribution  
- on time payment distribution  
- tenure buckets vs eligibility  
- comparison of average metrics by eligibility  
- eligibility count plot  

These charts highlight consistent financial behavior differences between eligible and non eligible groups.

---

## Key Insights  
- Customers with higher credit scores, lower utilization, and strong on time payment behavior are much more likely to qualify for a credit line increase.  
- Tenure influences eligibility because early stage users show higher volatility and less predictable credit behavior.  
- Spend patterns and payment consistency are strong indicators of responsible credit use.  
- A balanced eligibility rule can increase engagement while maintaining healthy risk controls.  

---

## Product Manager Perspective  
A PM can use these insights to:
- simplify eligibility messaging in the mobile app  
- guide proactive nudges that help customers build credit readiness  
- design targeted CLI offers for responsible customers  
- work with risk teams to adjust thresholds that support growth without increasing losses  
- create transparency around credit decisions to improve trust and satisfaction  

This analysis reflects how product, risk, and analytics teams collaborate inside real financial institutions.

---

## Tools Used  
- Python  
- pandas  
- NumPy  
- Matplotlib  

---

## Future Enhancements  
- add behavioral trends such as spend change over time  
- integrate credit score simulation  
- build a logistic regression classifier  
- test alternative eligibility rules for scenario modeling  
- create a small UI mock to show how CLI surfaces in the product experience  

---

## About  
This project is part of my Applied Business Strategy Challenge where I solve real fintech product problems using analytics and product thinking.

If my work aligns with the needs of your team I would welcome a conversation.
