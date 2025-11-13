# Customer Retention Analysis & Dashboard

**Author:** Sara Fatma  
**Tools:** Python (Pandas, NumPy, Matplotlib, Seaborn), Power BI  
**Date:** November 2025

## Summary
Built an end-to-end churn analysis pipeline: generated sample customer data, cleaned & engineered features with Python, analyzed churn patterns (age groups, monthly charges), and created an interactive Power BI dashboard highlighting key segments at risk.

## Files
- `notebooks/01_data_explore.ipynb` — Jupyter notebook with EDA and feature engineering.
- `data/sample_customer_data.csv` — sample raw data.
- `data/cleaned_customer_data.csv` — cleaned dataset used in Power BI.
- `powerbi/Customer_Retention_Dashboard_Final.pbix` — Power BI dashboard file.
- `reports/Customer_Retention_Dashboard_Report.pdf` — exported dashboard (PDF).
- `assets/dashboard_preview.png` — preview image of dashboard.

## Key Insights
- Middle-aged customers show ~50% churn rate.  
- High-paying customers are more likely to churn (50% vs 33%).  
- Overall churn rate: **40%**

## How to View the Project
1. Open `notebooks/01_data_explore.ipynb` to see data cleaning and churn logic.  
2. Open Power BI file (`.pbix`) in the `powerbi/` folder.  
3. Check `reports/Customer_Retention_Dashboard_Report.pdf` for the final presentation.

## Notes
This is a demo dataset project showcasing churn analysis skills in Python + Power BI.  
For real data, connect to a secure database and implement model versioning.

---

![Dashboard Preview](assets/dashboard_preview.png)
