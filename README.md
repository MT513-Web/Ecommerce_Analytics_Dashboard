# 🛒 E-Commerce Production Analytics & Insights Hub

An interactive, production-grade Streamlit web application designed for automated data cleaning, statistical distribution diagnosis, outlier detection, and executive KPI reporting on e-commerce transaction data.

**Live Streamlit App:** [Click Here to View Live Dashboard](https://ecommerceanalyticsdashboard-2dqe3dbtdwxveq5h4bugdx.streamlit.app/)

---

## Key Features

* **Automated Data Cleaning Pipeline:** Handles missing order values using outlier-robust **Median Imputation**.
* **Executive KPI Panel:** Displays real-time metrics for **Total Revenue**, **Total Orders**, and **Average Order Value (AOV)** formatted in PKR.
* **Interactive Filtering:** Sidebar options to dynamically slice dataset by **Customer City** and **Product Category**.
* **Statistical Skewness & Distributions:** Visualizes age and order value distributions with Seaborn KDE curves and skewness scores.
* **Tukey's IQR Outlier Detection:** Calculates interquartile ranges and plots boxplots with customizable threshold cutoff lines.
* **Feature Correlation & Data Grid:** Interactive Pearson correlation heatmap alongside a dynamic, searchable raw data grid.

---

## Tech Stack & Libraries

* **Language:** Python 3.10+
* **Dashboard Framework:** Streamlit
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib

---

##  How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/MT513-Web/Ecommerce_Analytics_Dashboard.git
   cd Ecommerce_Analytics_Dashboard

2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Launch the Streamlit application:
```bash
streamlit run app.py 
 ```



