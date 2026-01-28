# Telco Customer Churn Prediction 📊

## 📌 Project Overview
A data analytics and machine learning project that analyzes customer behavior to predict churn (customers leaving). This project identifies key churn indicators and builds a predictive model to help the business retain high-risk customers.

## Tools & Technologies Used
* **Python:** Pandas, NumPy (Data Processing)
* **Machine Learning:** Scikit-Learn (Logistic Regression)
* **Visualization:** Matplotlib, Seaborn
* **Dashboarding:** Power BI
* **IDE:** VS Code / Jupyter Notebook

## Key Insights Discovered
1.  **Contract Type:** Customers on "Month-to-Month" contracts are **6x more likely to churn** than those on 2-year contracts.
2.  **Internet Service:** Fiber Optic users have a significantly higher churn rate, indicating potential service quality issues.
3.  **Tenure:** New customers (0-12 months) are at the highest risk. Loyalty stabilizes after 20 months.

## How to Run
1.  Clone the repository.
2.  Install dependencies: `pip install pandas scikit-learn seaborn matplotlib`
3.  Run the Jupyter Notebook in the `Notebooks/` folder.
4.  View the `churn_predictions.csv` output for risk scores.

## Power BI Dashboard
* Calculated "Churn Rate" using DAX measures.
* Visualized Churn by Contract, Payment Method, and Tenure.
* Created an actionable "High Risk" list for the sales team to target customers with >50% probability of leaving.