# Mobile Sales Exploratory Data Analysis (EDA)

## Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on mobile phone sales transactions using Python. The goal is to clean data, handle statistical outliers, and uncover commercial insights using data visualization.

## Technical Stack
* **Language:** Python
* **Libraries:** Pandas, Seaborn, Matplotlib
* **Environment:** Jupyter Notebook

## Key Steps Performed
1. **Data Cleaning & Pre-processing:** Resolved missing values, handled customer age groups, and corrected data types.
2. **Outlier Detection:** Used Interquartile Range (IQR) boundary checks to identify and manage statistical pricing anomalies (such as a 250,000 unit price outlier requiring data auditing).
3. **Exploratory Visualizations:** 
   * *Histogram:* Analysed customer age demographics.
   * *Boxplot:* Evaluated price distributions and brand price parity across Apple, OnePlus, Samsung, Vivo, and Xiaomi.
   * *Bar Chart:* Compared total sales volume by brand.
4. **Business Insight Generation:** Applied an *Observation → Insight → Action* reporting methodology to turn visual data into actionable business recommendations.
5. ## Business Recommendations & Actions
* **Audit Pricing Outliers:** Direct data teams to investigate the 250,000 unit price anomaly to determine if it is an error or bulk corporate purchase.
* **Shift to Feature Differentiation:** Since Apple, Samsung, OnePlus, Vivo, and Xiaomi share tight price parity, compete on bundled value and customer retention rather than price cuts.
* **Inventory Allocation:** Maintain strong stock for top volume drivers (Apple, Samsung, Vivo) while evaluating targeted campaigns for Xiaomi.
