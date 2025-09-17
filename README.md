# 🛒 Integrated Retail Analytics for Store Optimization  

## 📌 Project Overview  
This project applies **data analytics and machine learning** to Walmart’s historical sales dataset in order to provide actionable insights for **store optimization, customer targeting, and demand forecasting**. The analysis integrates sales, store, and feature datasets to uncover patterns and support data-driven retail decisions.  

---

## 🎯 Objectives  
- Perform **Exploratory Data Analysis (EDA)** to identify sales trends, holiday effects, and store type performance.  
- Apply **Customer Segmentation** using clustering to group departments based on demand behavior.  
- Conduct **Market Basket Analysis (MBA)** to discover cross-selling opportunities between departments.  
- Build **Demand Forecasting Models** (Linear Regression, Random Forest, XGBoost) to predict weekly sales.  

---

## 📂 Dataset Description  
- **Sales Data** → Weekly sales per store & department.  
- **Stores Data** → Store type (A/B/C) and size.  
- **Features Data** → External factors (temperature, fuel price, CPI, unemployment, markdowns, holidays).  

---

## 🔍 Methodology  
1. **Data Cleaning & Integration**  
   - Merged all datasets, handled missing values, engineered time features.  
2. **Exploratory Data Analysis (EDA)**  
   - Sales trends, holiday vs non-holiday performance, store type comparisons, markdown impact.  
3. **Customer Segmentation (K-Means Clustering)**  
   - Grouped departments into clusters: high-revenue, seasonal, steady-demand, and low-demand.  
4. **Market Basket Analysis (Association Rules)**  
   - Identified departments often purchased together to enable bundling & cross-selling strategies.  
5. **Demand Forecasting**  
   - Built baseline (Linear Regression) and advanced models (Random Forest, XGBoost).  
   - Achieved high accuracy with Random Forest/XGBoost (**R² ≈ 0.97**).  

---

## 📊 Key Insights  
- **Holiday weeks** drive significantly higher sales compared to normal weeks.  
- **Store Type A (largest stores)** consistently outperforms B & C in weekly sales.  
- **Promotions (markdowns)** have a modest but positive impact on sales.  
- **Top-performing departments** contribute ~80% of total revenue (Pareto effect).  
- **Market basket analysis** shows strong co-purchase patterns between grocery, household, and apparel categories.  
- **Random Forest & XGBoost** models provide reliable sales forecasts, helping in inventory and promotion planning.  

---

## 🚀 Technologies Used  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost)  
- **Clustering (KMeans)** for segmentation  
- **Association Rule Mining** (FP-Growth / pyfpgrowth) for market basket analysis  
- **Machine Learning** (Random Forest, XGBoost) for forecasting  

---

## 📌 Conclusion  
This project demonstrates how **integrated retail analytics** can help optimize store operations by:  
- Identifying **seasonality & demand drivers**  
- Segmenting departments for **better marketing & inventory strategies**  
- Discovering **cross-selling opportunities**  
- Providing **accurate demand forecasts**  

Overall, the solution enables **data-driven retail decision-making** to improve efficiency, increase revenue, and enhance customer satisfaction.  

---

## Acknowledgments

*   The developers of the powerful open-source libraries used in this project.
*   The community providing the dataset for this important research area.

---

## 🗂️ Data sets
* This project was created during and Internship.
* If you want to use the data that I have used, you can contact me.

---

## 🙋‍♂️ Author

**Shubham Pandey**
📧 [Email Me](mailto:shubhamppandey1084@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/shubham-pandey-6a65a524a/) • [GitHub](https://github.com/Shubhampandey1git)