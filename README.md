# <u>**Telecom Customer Churn Analysis Dashboard**</u>



---

## <u>**Business Problem**</u>

Telecom companies lose revenue when customers switch to competitors. Key challenges include identifying high-risk segments, understanding churn patterns across regions and services, predicting future churn, and enabling data-driven retention strategies.

---

## <u>**Short Description / Purpose**</u>

An end-to-end churn analysis project implemented in three stages: analyzing historical churn patterns, predicting at-risk customers using machine learning, and visualizing results in a Power BI dashboard. The project helps telecom businesses identify churn drivers and take proactive retention actions.

---

## <u>**Tech Stack**</u>

* 📊 **Power BI Desktop** – For building interactive dashboards and reports.
* 📂 **Power Query Editor** – For data cleaning, transformation, and calculated columns.
* 🧠 **DAX (Data Analysis Expressions)** – For KPI calculations like churn rate, total churn, and customer count.
* 🐍 **Python (Jupyter Notebook / Anaconda)** – For building machine learning models.
* 🤖 **Scikit-learn & XGBoost** – For churn prediction models.
* 🐼 **Pandas & NumPy** – For data manipulation and preprocessing.
* 📁 **File Format** – .pbix for Power BI dashboards, .csv/.xlsx for intermediate data, .png for dashboard previews.

---

## <u>**Data Source**</u>

Telecom Customer Churn Dataset:
* Includes demographics, account info, service details, and churn status.
* **Key fields:** Gender, Age, Tenure, Contract, Payment Method, Monthly Charges, Services, Churn Category.
---

## <u>**Project Implementation**</u>

* **Stage 1 – Churn Analysis Summary**
    * Explored churn by demographics, contract type, tenure, payment method, and services
    * Derived columns: Age Group, Tenure Group, Monthly Charge Range
    * Key insights: Month-to-month contracts and unsubscribed services show higher churn; certain demographics (females over 50) and regions have higher churn

* **Stage 2 – Machine Learning Prediction**
    * Built Random Forest and XGBoost models to predict churn among new joiners
    * Achieved ~84% accuracy in identifying high-risk customers
    * Key drivers: Contract Type, Tenure, Monthly Charges, and Service Subscriptions

* **Stage 3 – Power BI Dashboard**
    * Visualized historical and predicted churn with interactive KPIs, charts, and slicers:
        * Churn by Demographics (Gender, Age)
        * Contract Type & Payment Method vs. Churn
        * Service Impact & Tenure vs. Churn Rate
        * Regional churn map
        * Predicted at-risk customers table
    * Dashboard supports targeted retention campaigns and actionable insights

---

## <u>**Conclusion**</u>

This project demonstrates a complete churn analysis pipeline, combining data exploration, machine learning prediction, and Power BI visualization. It enables telecom companies to understand churn drivers, predict at-risk customers, and implement effective retention strategies.
