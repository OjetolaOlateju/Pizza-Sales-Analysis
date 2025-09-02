# Pizza-Sales-Analysis
A data-driven exploration of pizza sales, uncovering customer behavior, best-selling products, and time-based trends. The insights help guide marketing, inventory, and menu planning decisions. Cleaned and analyzed in Excel, this project highlights key metrics to boost business performance.
# 🍕 Pizza Sales Analysis  
<img width="1080" height="434" alt="image" src="https://github.com/user-attachments/assets/a790a947-2f59-4170-ba44-e9f79946c2dc" />

## 📌 Introduction  
This project presents a structured analysis of pizza sales data, highlighting **key performance indicators**, **product trends**, and **customer behavior patterns**.  
The goal is to uncover what sells most, when demand peaks, and which categories contribute most to revenue — providing a **data-driven foundation** for better product strategy, operations, and marketing decisions.  

---

## 🎯 Objectives  
- Analyze overall sales performance: total revenue, order volume, and quantity sold.  
- Identify top-performing products based on popularity and profitability.  
- Discover trends across days and times to understand customer behavior.  
- Evaluate contribution of categories and sizes to optimize the product mix.  
- Support data-driven decisions for inventory, promotions, and menu planning.  

---

## 📊 Scope  
The analysis covers all recorded pizza sales transactions in the dataset, including:  
- **Order-level details:** product type, quantity, price, and order timing  
- **Category and size breakdowns:** popularity by size and category  
- **Time-based trends:** daily and hourly sales patterns  

> **Note:** This analysis excludes external factors such as marketing campaigns or seasonal events and focuses solely on internal sales performance.  

---

## 🗂 Dataset Overview  
- **Rows:** 48,621  
- **Columns:** 14 (after cleaning)  

### 🔑 Key Columns  
- **Order ID:** Unique transaction identifier  
- **Pizza Name:** Identifies each product sold  
- **Pizza Category:** Classic, Supreme, Veggie, etc.  
- **Pizza Size:** S, M, L, XL  
- **Quantity:** Number of pizzas sold per order line  
- **Total Price:** Sales amount per line  
- **Order Date/Time:** For time-series analysis (day name, day time derived)  

---

## 🧹 Data Cleaning  
- Checked for **missing values** using `=COUNTBLANK()`  
- Removed **duplicates** (none found)  
- Verified **data types** for numeric and text columns  
- Generated **Day Name** and **Day Time** from order date/time  

---

## 🔍 Exploratory Data Analysis (EDA)  

### 1️⃣ Sales Performance Overview  
- **Total Sales:** $817,860.05  
- **Average Pizza Price:** $16  
- **Total Pizzas Sold:** 49,574  

### 2️⃣ Top Performing Products  
- **Most Popular Pizza:** Classic Deluxe Pizza (by quantity)  
- **Most Profitable Pizza:** Thai Chicken Pizza (by revenue)  

### 3️⃣ Category & Size Trends  
- **Top Category:** Classic  
- **Most Ordered Size:** Large (L)  

### 4️⃣ Time-Based Trends  
- **Busiest Day:** Friday  
- **Peak Order Time:** Afternoon  
- **Seasonal Peak:** January & November  
- **Lowest Months:** September & December  

---

## 💡 Key Insights  
- **Strong Sales Performance:** Over $817k revenue from ~50k pizzas sold  
- **Customer Favorites:** Classic Deluxe & Thai Chicken drive major revenue  
- **Size & Category Preferences:** Large pizzas and Classic category dominate  
- **Timing Matters:** Friday afternoons are peak business hours  

---

## 📌 Recommendations  
- **Focus Promotions on Peak Times:** Fridays and afternoons  
- **Highlight Bestsellers:** Market Classic Deluxe & Thai Chicken Pizza  
- **Optimize Inventory:** Stock up for Large and Classic pizzas  
- **Streamline Menu:** Reevaluate low-performing products  
- **Offer Time-Based Deals:** Boost slow periods with early-bird or midweek discounts  
- **Seasonal Campaigns:** Stabilize low-demand months with targeted promotions  

---

## 📅 Conclusion  
The analysis reveals **clear patterns** in demand — Fridays, afternoons, and Large pizzas lead the charts.  
These insights enable **data-driven menu planning, inventory management, and promotional strategies** to optimize business performance.  

---

## ⚠️ Limitations & Future Work  
- No customer demographic data included  
- Future work: integrate customer feedback & profiles for personalized marketing  
