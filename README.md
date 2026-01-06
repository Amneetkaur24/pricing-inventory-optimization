📊 Pricing & Inventory Optimization
Demand Elasticity, Revenue Simulation & Inventory-Aware Pricing Decisions
📌 Project Overview

Retail and e-commerce businesses often optimize prices based on theoretical demand, ignoring inventory feasibility. This leads to revenue leakage through stockouts, over-discounting, and operational inefficiencies.

This project builds an end-to-end pricing and inventory optimization framework that:

Models price-demand relationships

Simulates pricing scenarios

Evaluates inventory-constrained feasibility

Identifies safe vs risky pricing strategies

Delivers executive-ready insights via dashboard

The goal is to optimize realized revenue, not just predicted demand.

🎯 Business Problem

Even if a price maximizes demand and revenue on paper, can the business actually fulfill that demand with available inventory?

This project answers that question using data-driven simulations and operational constraints.

🧠 Key Concepts Applied

Price elasticity & demand behavior

Revenue maximization vs fulfillment feasibility

Inventory-aware optimization

Scenario simulation & stress testing

Executive decision analytics

🗂 Project Structure
pricing-inventory-optimization/
│
├── data/
│   ├── ecommerce_pricing_raw.csv
│   ├── ecommerce_pricing_cleaned.csv
│   ├── ecommerce_pricing_featured.csv
│   ├── scenario_summary.csv
│   ├── category_decision_table.csv
│   ├── elasticity_risk_table.csv
│
├── notebooks/
│   ├── Day1_Data_Cleaning.ipynb
│   ├── Day2_Price_Elasticity_Analysis.ipynb
│   ├── Day3_Demand_Modeling.ipynb
│   ├── Day5_Pricing_Scenario_Simulation.ipynb
│   ├── Pricing_Feasibility_Inventory_Optimization.ipynb
│   ├── Elasticity_Risk_Segmentation.ipynb
│
├── app/
│   └── app_pricing_and_inventory_optimization.py
│
├── requirements.txt
├── README.md

🔍 Project Workflow
🟢 Data Cleaning & Preparation

Cleaned raw pricing and demand data

Handled missing values and inconsistencies

Created analysis-ready datasets

🟡 Price Elasticity & Demand Behavior

Analyzed price vs demand relationships

Identified elastic vs inelastic categories

Evaluated promotion and competitor price impact

🟠 Demand Modeling & Revenue Curves

Trained regression model for demand prediction

Simulated demand across price ranges

Identified revenue-optimal prices

🔵 Pricing Scenario Simulation

Simulated pricing strategies:

Baseline

−10% discount

+5% increase

+10% increase

Quantified revenue sensitivity

🔴 Inventory-Aware Pricing Feasibility

Introduced inventory constraints

Calculated fulfilled demand (real sales)

Compared theoretical vs feasible revenue

Identified stockout risks

🟣 Elasticity & Risk Segmentation

Segmented categories by:

Price elasticity

Stockout risk

Identified:

Safe discount zones

Risky price strategies

📈 Executive Dashboard (Streamlit)

An interactive dashboard provides:

Scenario-level KPIs

Feasible vs theoretical revenue comparison

Category-level pricing recommendations

Elasticity vs inventory risk visualization

🔗 Live App: https://pricing-inventory-optimization-2appeg9cg3dxgr9u6utkhjx.streamlit.app/

📊 Key Insights

Aggressive discounts maximize demand but create high stockout risk

Inventory constraints significantly reduce achievable revenue

Moderate pricing strategies balance profitability and execution

Pricing decisions must align with supply planning

💼 Business Recommendations
Pricing Strategy

Avoid deep discounts without inventory buildup

Favor moderate price changes with stable fulfillment

Inventory Coordination

Increase stock before promotional campaigns

Align pricing actions with replenishment cycles

Executive Takeaway:
Optimize for realized revenue, not theoretical demand.

🛠 Tools & Technologies

Python: Pandas, NumPy, Scikit-learn

Modeling: Linear Regression

Visualization: Matplotlib

Dashboard: Streamlit

BI (Optional): Power BI

Version Control: Git & GitHub

⚠️ Assumptions & Disclaimer

Inventory levels are simulated

Demand model is linear for interpretability

Results are directional and illustrative

Real-world deployment would require:

Live inventory feeds

Advanced elasticity models

Continuous monitoring

🚀 Future Enhancements

Non-linear demand models

Dynamic pricing optimization

Supply-chain lead-time integration

SHAP-based explainability

Automated price recommendations

👤 Author

Amneet Kaur
Data Analyst | Pricing Analytics | Inventory Optimization
📍 Canada
