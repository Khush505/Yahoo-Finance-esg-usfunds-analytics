# **Yahoo Finance ESG US Funds Analytics**

This project analyzes **Environmental, Social, and Governance (ESG)** scores of US mutual funds using Yahoo Finance data. The objective is to identify **top-performing funds based on ESG metrics** and provide category-wise insights through Python-based analytics and a Power BI dashboard.


## **Problem Statement**

Investors are increasingly looking for funds that align with **sustainable and responsible investing (SRI)** principles.  
This project aims to address:

- Which funds have the **highest ESG performance**?  
- How do **different fund categories** compare on ESG dimensions?  
- What patterns emerge in **environment, social, and governance** scores?  


## **Dataset**

The dataset comes from **Yahoo Finance US Mutual Funds** and includes:

- Fund details such as symbol, name, and category  
- ESG scores: _environment_, _social_, _governance_  
- Peer averages and category information  

**Rows:** 19,000+  
**Columns:** 298 (subset used for analysis)  


## **Key Insights**

- Top 10 US funds by overall ESG score were identified, with **RSNRX** and **RSNYX** leading the list.  
- **Category-level analysis** revealed variations in ESG performance, with some allocations excelling in environmental scores and others in social metrics.  
- Score distributions showed skewness, highlighting clusters of funds with low governance ratings.


## **Tools Used**

- **Python** (Pandas, NumPy, Matplotlib, Seaborn) for data cleaning and analysis  
- **Jupyter Notebook** for exploratory analytics  
- **Power BI** for interactive dashboard visualizations  


## **Files Included**

| **File**                                      | **Description**                           |
|-----------------------------------------------|-------------------------------------------|
| `mutualfunds_clean.csv`                       | Cleaned dataset for ESG analysis          |
| `01_eda_esg.ipynb`                             | Python notebook with exploratory analysis |
| `KhushbooMasih_USFunds_ESG_Analytics_Aug2025.pbix` | Power BI dashboard file                  |
| `KhushbooMasih_USFunds_ESG_Analytics_Aug2025.pdf`  | Exported PDF version of the dashboard    |


## **Dashboard Highlights**

The Power BI dashboard provides:  
- **KPI cards**: average ESG scores  
- **Clustered bar charts**: ESG breakdown by fund category  
- **Pie charts**: fund distribution based on ESG ranges  
- **Top 10 fund rankings** based on ESG performance  


## **Author**

**Khushboo Masih**  
MSc Data Science  

 [khushboomasih193@gmail.com](mailto:khushboomasih193@gmail.com)  
 [GitHub](https://github.com/Khush505)  
 [LinkedIn](https://www.linkedin.com/in/khushboo-masih/)  


## **License**

This project is licensed under the **MIT License** – you are free to use, modify, and distribute it with proper attribution.
