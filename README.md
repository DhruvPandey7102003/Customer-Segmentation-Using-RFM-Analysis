# 🧠 RFM Customer Segmentation Using Python

This project performs **RFM (Recency, Frequency, Monetary)** analysis on customer transaction data using Python and Jupyter Notebook. RFM is a marketing analysis tool used to identify high-value customers and group them based on their purchasing behavior.

---

## 📁 Project Overview

- 📅 **Recency**: How recently a customer made a purchase
- 🔁 **Frequency**: How often they make a purchase
- 💰 **Monetary**: How much they spend in total

This analysis helps businesses:
- Identify loyal and high-spending customers
- Recognize inactive or at-risk customers
- Create targeted marketing strategies

---

## 📊 Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📌 Steps Followed

1. **Data Cleaning & Preparation**
   - Converted `InvoiceDate` to datetime format
   - Created `TotalPrice = Quantity × UnitPrice`

2. **Feature Engineering**
   - Calculated Recency, Frequency, Monetary values per `Customer ID`

3. **RFM Table**
   - Grouped and aggregated data to create the RFM table

4. **Data Preprocessing**
   - Standardized the RFM features using `StandardScaler`

5. **Clustering (Optional Extension)**
   - Applied **KMeans clustering** on the RFM values to segment customers

6. **Visualization**
   - Used Matplotlib and Seaborn for visual insights into customer groups

---
