# 📦 Delivery Performance Analysis — E-Commerce Dataset

## 🚀 Overview
Exploratory Data Analysis to understand delivery delays, shipment performance, and operational issues in an e-commerce system.

---

## 📁 Dataset Overview
Each row represents one order.

**Key Columns:**  
Warehouse_block, 
Mode_of_Shipment, 
Customer_care_calls, 
Customer_rating,  
Cost_of_the_Product, 
Prior_purchases, 
Product_importance, 
Gender,  
Discount_offered, 
Weight_in_gms, 
Reached.on.Time_Y.N (0 = On time, 1 = Late)

---

## 🎯 Objective
- Identify the sources of delivery delays  
- Analyze warehouse performance  
- Evaluate shipping modes  
- Understand the impact of product/customer features  

---

## 📊 EDA Insights

### **Univariate**
- Warehouse **F** handles the most orders  
- **Ship** is the most used mode  
- **Low-importance** products dominate  
- **Late deliveries** are more frequent than on-time ones  
- Gender distribution is balanced  
- Most products cost **150–300**  

### **Bivariate**
- Warehouse **F** shows the **highest delays**  
- **Ship mode** is the **least reliable**  
- High-importance items are delivered faster  
- **3–4 customer care calls** often signal delays  
- Ratings are **not** affected by delivery time  
- **High discounts** correlate with late deliveries  
- Cost & prior purchases don’t impact delivery time  

---

## 📌 Business Insights
- Improve processes in **Warehouse F**  
- Strengthen logistics for **Ship mode**  
- Prioritize low/medium importance products  
- Add capacity during **high-discount** periods  
- Delivery delays are independent of product cost or ratings  

---

## 🛠 Tools Used
Python · Pandas · Matplotlib · Seaborn · Plotly

---

## ▶️ How to Run
Open the `.ipynb` file and run all cells in Jupyter Notebook or JupyterLab.

## Notebook:
[Click here to view the notebook]
(https://github.com/gudabhavishya-ops/Delivery-Performance-Analysis-EDA-Python/blob/main/Delivery_Analysis_Project.ipynb)

