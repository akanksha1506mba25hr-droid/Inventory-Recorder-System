# Inventory-Reorder-System-AI


![Python](https://img.shields.io/badge/Python-3.9-blue)
![Machine Learning](https://img.shields.io/badge/ML-DecisionTree-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## Project Overview

This project presents an AI-powered Inventory Optimization System that predicts whether a product should be reordered based on sales trends, stock availability, supplier lead time, and demand patterns.

The system simulates real-world retail decision-making and helps automate inventory management efficiently.

---

## Business Problem

Retail companies often face two major challenges:

* Stockouts leading to loss of sales
* Overstocking leading to increased storage costs

### Solution

This project uses Machine Learning to determine whether a product should be reordered based on multiple operational factors.

---

## AI Solution Approach

A classification model is developed using a Decision Tree Classifier that learns decision rules from data and predicts reorder decisions automatically.

### Output

* 1 → Reorder Required
* 0 → Stock is Sufficient

---

## Features Used

| Feature Name    | Description                                  |
| --------------- | -------------------------------------------- |
| daily_sales     | Average daily product sales                  |
| stock_available | Current inventory level                      |
| lead_time       | Time required to restock                     |
| demand_trend    | Demand level (1 = Low, 2 = Medium, 3 = High) |

---

## Technology Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib

---

## Screenshots

<img width="421" height="636" alt="image" src="https://github.com/user-attachments/assets/71d4c509-d4cb-49ae-92e8-e1350d2043f3" /> 


---

## Sample Prediction

Example Input:

* Daily Sales = 60
* Stock Available = 50
* Lead Time = 5
* Demand Trend = High

Result:
Reorder Required

---

## Business Impact

* Reduces inventory costs
* Prevents stock shortages
* Improves supply chain efficiency
* Enables automated decision-making

---

## Real-World Applications

This type of system is used by companies such as Amazon, Flipkart, and Reliance Retail for inventory optimization and supply chain automation.

---

## Future Scope

* Power BI Dashboard Integration
* Web Application Deployment using Streamlit
* Real-time Inventory Tracking
* Use of advanced machine learning models

---

## Colab Link
https://colab.research.google.com/drive/1t8D_pvRV1D1dZhDaeVQIGBmguq-ez0XZ#scrollTo=1b8gEiU09ePs
---

## Learning Outcomes

* Understanding real-world business problems
* Applying Machine Learning to operations
* Converting business logic into AI models
* Building industry-level GitHub projects

---

## Author

Preeti
[www.linkedin.com/in/Preeti-HR](http://www.linkedin.com/in/Preeti-HR)

---

## Final Note

This project demonstrates how Artificial Intelligence can transform traditional inventory management into a smart, automated, and data-driven system used in modern retail industries.

---
