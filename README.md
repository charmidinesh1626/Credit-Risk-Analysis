# Credit-Risk-Analysis-using-Power-BI

## 📌 Summary – Credit Risk Analysis using Power BI

This project focuses on **credit risk analysis** using the **UCI Credit Card dataset (30,000+ records)**, visualized and analyzed through **Power BI dashboards**. The objective was to uncover **patterns of default risk**, study **demographic and financial behavior**, and apply **advanced analytical techniques** to support **data-driven credit policy decisions**.

### 🔹 Key Steps

* **Data Cleaning & Transformation**: Renamed columns, handled missing values, created derived fields (e.g., *Total Bill*, *Total Payment*, *Age Groups*), and calculated KPIs such as *average credit limit* and *default rate*.
* **Data Modeling**: Structured demographic, financial, and behavioral attributes to analyze repayment behavior and defaults.
* **Exploratory Analysis**: Used dashboards to explore customer demographics, payment histories, credit limits, and default behavior.

### 🔹 Dashboard Insights

1. **Demographics & Defaults**

   * Overall default rate: **22.14%**.
   * Women (39.65% of customers) showed **higher default rates (~24.18%)** compared to men (~20.81%).
   * Higher education levels correlated with **lower default risk**.

2. **Financial Behavior**

   * Average credit limit: **167.5K**, average age: **35.5 years**.
   * Older groups had **higher credit limits** but **more stable repayment patterns**.

3. **Influencing Factors**

   * Past defaults strongly influenced repayment improvement (**+0.64 increase**).
   * Younger clients (≤22 years) and those with lower education levels showed **riskier repayment trends**.

4. **Segmentation (Decomposition Tree)**

   * Factors like **gender, age, marital status, education,** and **repayment behavior** explained variations in credit limits.

5. **Advanced Analytics**

   * **K-Means Clustering**: Grouped clients into low-risk borrowers, high-risk young clients, and moderate-risk new entrants.
   * **PCA**: Reduced dimensions to highlight clusters of **low-risk (blue)** vs. **high-risk (yellow) outliers**.



### 🔹 Conclusion

The analysis revealed that **age, gender, and education** significantly influence default risks. By combining **interactive dashboards, clustering, and PCA**, the project provided **actionable insights** into customer behavior, enabling **effective segmentation, risk profiling, and targeted intervention strategies**. This approach enhances **strategic credit risk management** for financial institutions.
