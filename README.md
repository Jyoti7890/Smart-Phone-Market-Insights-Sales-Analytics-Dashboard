# **Smartphone Market Insights & Sales Analytics Dashboard**

##  Dashboard Preview

![Dashboard Overview](https://github.com/Jyoti7890/Smart-Phone-Market-Insights-Sales-Analytics-Dashboard/blob/59da2e68f2ca9650f63714fa26ef01adc14c158a/Smartphones_dashboard_1.png)
*Sales Performance Overview*

![Deep Dive Analysis](https://github.com/Jyoti7890/Smart-Phone-Market-Insights-Sales-Analytics-Dashboard/blob/59da2e68f2ca9650f63714fa26ef01adc14c158a/SmartPhones_dashboard_2.png)
*Customer, Model, and Brand Insights*

##  Project Overview
...

This **Power BI dashboard** provides a detailed analysis of smartphone sales across different cities, brands, and customer segments. It uncovers insights into **sales performance, customer behavior, and product trends**, helping stakeholders make **data-informed decisions** in marketing, inventory, and product strategy. A Custom Calendar table was created with columns like Day Name, and linked with the sales data for accurate time-based analysis. 

---

##  Dataset Information

- The dataset is sourced from **Kaggle**

##  Project Structure

```text
Smart-Phone-Market-Insights-Sales-Analytics-Dashboard/
│
├── SmartPhones Analysis Report.pbix        # Power BI Report file
├── SmartPhones Data.xlsx                   # Raw dataset used in the project
├── SmartPhones_dashboard_2.png             # Dashboard screenshot (view 2)
├── Smartphones_dashboard_1.png             # Dashboard screenshot (view 1)
└── README.md                               # Project overview and documentation
```

##  Key Insights

### **Dashboard 1: Sales Performance Overview**

- **Total Sales**: ₹769 million from 3,835 transactions  
- **Average Selling Price**: ₹40.11K  
- **Quarter-wise Sales Comparison**: Highlights performance and year-over-year growth across all four quarters  
- **Monthly Sales Trends**: Seasonal sales spikes and dips visualized  
- **Annual Sales Growth**: Breakdown of revenue trends over the years  
- **Performance Table**: Side-by-side comparison of current vs. previous year/quarter metrics  

---

### **Dashboard 2: Deep-Dive Analysis**

- **Sales by Day**:  
  - **Saturday** had the highest sales (₹115M)  
  - **Wednesday** had the lowest (₹105M)  
- **Top-Selling Models**: iPhone, OnePlus, and Samsung Galaxy  
- **City-wise Sales**: Delhi, Mumbai, Bangalore, and Kolkata were top performers  
- **Payment Methods**: UPI, Debit Card, Credit Card, and Cash each contributed ~24–26%  
- **Customer Ratings**: Majority rated products as **Good**, followed by **Average** and **Poor**  
- **Monthly Quantity Sold**: Peaks in **January, April, August, and December**  
- **Brand-wise Revenue**:  
  - **Apple**: ₹304M+  
  - Followed by Xiaomi, Samsung, and Vivo  

---

##  Features

- built in **Power BI**
- Fully **interactive dashboard** with drill-downs
- Slicers for **month, mobile model, and payment method**
- Clean, **user-friendly design**
- Visual **KPIs**, charts, and dynamic tables

---

## Tools & Techniques Used

- **Power BI**: Data cleaning, modeling, and visualization  
- **Power Query**: Used to create new fields like the **Customer Ratings** column  
-  **Custom Calendar**:
- A separate **Custom_Calendar** table was created using Power Query  
- Linked with the `Mobile_Sales` table via the **Date** column  
- Includes **Day Name** and allows accurate time-based slicing
- **DAX Measures**:  
  - Total Sales  
  - Quantity Sold  
  - YOY Growth  
  - Average Selling Price  
  - Ratings Breakdown  


---

##  Business Value

This dashboard empowers businesses to:

- Identify **top-performing products and regions**
- Understand **seasonal demand and customer preferences**
- Track **payment and purchase behaviors**
- Take **faster and more strategic actions** in sales and marketing

---

## Future Enhancements

- Add **cost & profit** metrics for margin analysis  
- Enable **real-time updates** via API or scheduled refresh  
- Use **time-series models** to forecast future sales  
- Incorporate **customer segmentation** for targeted marketing  

---
