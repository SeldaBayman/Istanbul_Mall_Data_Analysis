# Istanbul_Mall_Data_Analysis

# 🛍️ 2021–2022 Istanbul Shopping Mall Customer Analysis with Power BI

This Power BI project analyzes shopping mall customer and sales behavior in Istanbul across the years 2021 and 2022. It provides deep insights into seasonal patterns, customer segments, and category-based sales trends.

![mall_sales](https://github.com/user-attachments/assets/0b5adb32-8b6f-40fb-b011-04a20b72eeae)

---

## 🔧 Data Cleaning & Price Normalization

The original dataset contained inconsistent "price" values:
- Some rows had amounts inflated by a factor of 10, 100, or even 1000.
- These inconsistencies were resolved using custom logic in Power Query:
  - If [price] > 10000 → divide by 1000
  - Else if [price] > 1000 → divide by 100
  - Else if [price] > 100 → divide by 10

> As a result, all financial metrics were standardized, allowing for accurate KPIs and comparisons.

![mall_customer1](https://github.com/user-attachments/assets/ee482819-dd35-4c6c-bca7-59243feb6a4a)

---

## 📊 Key Business Insights

### 1. 📈 Sales Volume Growth
- 2022 saw a **notable increase** in total sales volume.
- However, **revenue did not increase proportionally**, likely due to seasonal campaigns and promotional discounts.

### 2. 🕰️ Monthly Trends
- **Top Sales Months:** May, March, June
- **Low Sales Months:** February, September, November
- **December** marked a **turning point**, with a significant uptick heading into 2022.

### 3. 👥 Customer Demographics
- The **25–34 age group** was the most active in spending behavior.
- These insights could help tailor future marketing efforts by demographic.

### 4. 🛍️ Top Categories (by invoice count)
1. Clothing  
2. Cosmetics  
3. Food & Beverage  
4. Toys  
5. Shoes  

These categories dominated transaction counts and suggest areas for targeted campaigns.

### 5. 🏬 Mall Performance

**Most Invoices Issued:**
- Mall of Istanbul  
- Kanyon  
- Metrocity  

**Highest Revenue Generators:**
- Forum Istanbul  
- Mall of Istanbul  
- Istinye Park

---

## 💡 Strategic Recommendations

- Focus marketing efforts on **Q2 and Q4**, especially targeting high-performing age groups and categories.
- Investigate revenue gaps during peak sales months (e.g., June & December).
- Use this dashboard for **seasonal planning**, **category-based promotions**, and **customer segmentation**.

---

## 📎 Project Tools
- Power BI (Data Modeling, DAX, Visualization)
- Power Query (Data Transformation & Normalization)
- Microsoft Excel (initial exploration)
- Custom Measures (YTD Sales, Growth Rate %, Revenue Comparison)

---

## 🔗 Live Demo & Report

Explore the full interactive dashboard and visuals here:  
👉 [GitHub Repository Link or Power BI Service Link]



