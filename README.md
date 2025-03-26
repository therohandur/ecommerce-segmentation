# 📦 E-Commerce Customer Segmentation with RFM and K-Means  
**Author:** Rohan Duraipandian  
**Tools:** Python, Pandas, Scikit-learn, Seaborn, Matplotlib, Jupyter Notebook, Tableau

---

## 📋 Overview  
This project analyzes customer transaction data from an online retail dataset to identify key customer segments using **RFM (Recency, Frequency, Monetary)** analysis and **K-Means Clustering**. The goal is to uncover insights that help optimize marketing strategies and inventory management.

---

## 📊 Objectives  
- Clean and preprocess raw transaction data  
- Perform RFM scoring for each customer  
- Apply K-Means clustering to segment customers  
- Visualize cluster patterns and behaviors  
- Recommend marketing and inventory strategies for each segment  

---

## 🧪 Techniques Used  
- **Data Cleaning:** Removed missing values, filtered canceled orders  
- **Feature Engineering:** Calculated Total Price, transformed Invoice Dates  
- **RFM Analysis:** 
  - **Recency:** Days since last purchase  
  - **Frequency:** Total number of purchases  
  - **Monetary:** Total spend  
- **Clustering:**  
  - Scaled data using StandardScaler  
  - Used Elbow Method to determine optimal clusters  
  - Applied K-Means and assigned customer clusters  
- **Visualization:** Box plots for each RFM variable by cluster using Seaborn

---

## 🧠 Key Insights  
- **Cluster 0:** VIPs – Frequent, recent, high-spending customers  
- **Cluster 1:** At-risk – Haven’t purchased recently, low activity  
- **Cluster 2:** Loyal but moderate – Consistent but not top spenders  
- **Cluster 3:** One-time buyers – High recency, low frequency

---

## 📈 Business Recommendations  
- **VIPs:** Reward with loyalty perks or early access to products  
- **At-risk:** Retarget with email campaigns and special offers  
- **Moderate customers:** Encourage repeat purchases with personalized recommendations  
- **One-time buyers:** Use welcome campaigns or discounts to re-engage

---

## 📂 Files  
- `Ecommerce_Customer_Segmentation_Rohan.ipynb` – Main analysis notebook  
- `Online Retail Dataset` – [Kaggle link](https://www.kaggle.com/datasets/hydrabolt/online-retail-data-set)  
- `README.md` – This file  

---

## 🚀 Future Improvements  
- Deploy as a dashboard using Tableau Public  
- Apply time-series analysis to predict customer churn  
- Explore association rules for product bundling
