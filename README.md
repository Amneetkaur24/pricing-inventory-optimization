# Pricing & Inventory Optimization

Demand Elasticity Modeling • Revenue Simulation • Inventory-Aware Pricing

---

## Project Overview

Retail and e-commerce companies often optimize prices using **theoretical demand models**, without considering inventory constraints.

This leads to:

• Stockouts during promotions
• Lost revenue opportunities
• Inefficient discount strategies
• Misalignment between pricing and operations

This project builds an **end-to-end pricing analytics framework** that evaluates whether pricing strategies are **operationally feasible**, not just theoretically profitable.

The analysis integrates **price elasticity modeling, scenario simulation, and inventory constraints** to identify pricing strategies that maximize **realized revenue**.

---

## Business Question

**Can a pricing strategy that maximizes demand actually be fulfilled with available inventory?**

The project evaluates how pricing decisions interact with:

• demand elasticity
• revenue potential
• inventory availability
• stockout risk

---

## Tools & Technologies

**Programming**

• Python
• Pandas
• NumPy

**Modeling**

• Linear Regression (Demand Modeling)
• Price Elasticity Analysis

**Visualization**

• Matplotlib

**Dashboard**

• Streamlit

**Version Control**

• Git & GitHub

---

## Dashboard Preview

<img width="628" height="503" alt="image" src="https://github.com/user-attachments/assets/74644f63-a77f-4852-b960-4923fe7e047b" />

Interactive dashboard highlights:

• Pricing scenario KPIs
• Theoretical vs feasible revenue
• Category-level pricing recommendations
• Elasticity vs inventory risk analysis

Live App
https://pricing-inventory-optimization-2appeg9cg3dxgr9u6utkhjx.streamlit.app/

---

## Project Workflow

### 1️⃣ Data Preparation

• Cleaned raw pricing and demand data
• Handled missing values and inconsistencies
• Created analysis-ready datasets

---

### 2️⃣ Price Elasticity Analysis

Analyzed how demand responds to price changes.

Identified:

• Elastic product categories
• Inelastic product categories
• promotion-sensitive segments

---

### 3️⃣ Demand Modeling

A regression model was trained to estimate demand at different price points.

This allowed simulation of **revenue curves across pricing ranges**.

---

### 4️⃣ Pricing Scenario Simulation

Simulated multiple pricing strategies:

• Baseline price
• −10% discount
• +5% price increase
• +10% price increase

Each scenario evaluates:

• predicted demand
• projected revenue
• demand sensitivity

---

### 5️⃣ Inventory-Aware Pricing Evaluation

Inventory constraints were applied to determine **feasible sales volume**.

Key metrics evaluated:

• fulfilled demand
• stockout risk
• realized revenue

This step highlights the difference between **theoretical revenue and achievable revenue**.

---

### 6️⃣ Elasticity & Risk Segmentation

Categories were segmented based on:

• price elasticity
• stockout probability

This enables identification of:

• safe discount ranges
• high-risk promotional strategies

---

## Key Insights

• Deep discounts increase demand but significantly raise stockout risk
• Inventory constraints reduce achievable revenue versus theoretical forecasts
• Moderate pricing strategies deliver the most reliable revenue outcomes
• Pricing decisions must align with supply planning

---

## Business Recommendations

### Pricing Strategy

Avoid aggressive discounts without inventory readiness.

Moderate pricing adjustments produce **more stable revenue outcomes**.

---

### Inventory Planning

Promotional campaigns should be aligned with:

• inventory availability
• replenishment cycles
• demand forecasts

---

### Executive Takeaway

The most profitable pricing strategy is not always the one that maximizes demand — it is the one that **maximizes fulfilled revenue**.

---

## Project Structure

pricing-inventory-optimization

├── data
│ ├── ecommerce_pricing_raw.csv
│ ├── ecommerce_pricing_cleaned.csv
│ ├── ecommerce_pricing_featured.csv
│ ├── scenario_summary.csv
│ ├── category_decision_table.csv
│ └── elasticity_risk_table.csv

├── notebooks
│ ├── Day1_Data_Cleaning.ipynb
│ ├── Day2_Price_Elasticity_Analysis.ipynb
│ ├── Day3_Demand_Modeling.ipynb
│ ├── Day5_Pricing_Scenario_Simulation.ipynb
│ ├── Pricing_Feasibility_Inventory_Optimization.ipynb
│ └── Elasticity_Risk_Segmentation.ipynb

├── app
│ └── app_pricing_and_inventory_optimization.py

├── requirements.txt
├── insights.md
└── README.md

---

## Assumptions

• Inventory levels are simulated
• Demand model uses linear regression for interpretability
• Results illustrate pricing strategy trade-offs

Production deployment would require:

• real inventory feeds
• advanced elasticity models
• continuous monitoring

---

## Future Enhancements

• Non-linear demand modeling
• Dynamic pricing optimization
• Supply-chain lead time integration
• Explainable AI for price decisions
• Automated price recommendation engine

---

## Author

Amneet Kaur
Data Analyst | Pricing Analytics | Inventory Optimization
Canada

