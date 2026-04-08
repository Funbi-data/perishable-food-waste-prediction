# Perishable Food Waste Prediction and Supply Chain Optimization

## Overview
Food waste in perishable supply chains leads to significant economic losses and inefficiencies. This project applies data analysis and machine learning techniques to identify key drivers of spoilage and predict waste risk.

The goal is to support data-driven decision-making in food systems by analyzing storage conditions, logistics, and demand patterns.

---

## Research Question
How can supply chain, storage, and demand factors be used to predict food spoilage and reduce waste-related losses?

---

## Dataset
The dataset contains over 100,000 records with 40+ features, including:

- Storage conditions (temperature, temperature deviation, abuse events)
- Supply chain variables (distribution time, handling score)
- Demand patterns (daily demand, variability)
- Financial metrics (revenue, waste cost, profit, profit margin)
- Target variable: `was_spoiled` (0 = Not Spoiled, 1 = Spoiled)

---

## Methodology
The project follows a structured data science workflow:

1. Data Cleaning and Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Selection  
4. Model Development (Logistic Regression, Random Forest)  
5. Model Evaluation and Optimization  

---

## Key Insights

- Spoiled products are associated with higher temperature instability and extreme abuse events  
- Longer distribution times increase spoilage risk  
- Handling quality has a moderate but secondary impact  
- Demand variability is not a primary driver of spoilage  
- Increased waste significantly reduces profit and profit margins  

---

## Model Performance

| Model | Accuracy | Key Observation |
|------|--------|----------------|
| Logistic Regression | ~56% | Improved detection of spoiled items |
| Random Forest (tuned) | ~61% | Balanced performance with better spoilage detection |

> Note: Initial models achieved higher accuracy but failed to detect spoiled items due to class imbalance. Balancing techniques improved real-world usefulness.

---

## Visual Insights

### Temperature Deviation vs Spoilage
(Add image)

### Distribution Time vs Spoilage
(Add image)

### Waste Percentage vs Profit
(Add image)

---

## Business Impact

This project demonstrates how data-driven models can:

- Identify high-risk products early  
- Reduce food waste in supply chains  
- Improve storage and logistics decisions  
- Minimize financial losses  

---

## Recommendations

- Implement strict temperature monitoring to prevent deviations  
- Reduce distribution time through optimized logistics  
- Prevent extreme temperature abuse events  
- Improve handling practices  
- Use predictive models for early waste detection  
- Reduce waste levels to improve profitability  

---

## Tools and Technologies

- Python (Pandas, NumPy)  
- Data Visualization (Matplotlib, Seaborn)  
- Machine Learning (Scikit-learn)  

---

## Author
Funbi Opemipo Olowojesiku
