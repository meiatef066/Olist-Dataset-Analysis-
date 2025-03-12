# Olist Dataset Analysis 
- used technology : sql - power-pi

## Overview  
This project analyzes the **[[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce`)]** , focusing on customer behavior, sales trends, product performance, and seller insights.  

## Process Followed  
1. **Understanding the Data**  
   - Examining dataset structure and attributes.  
2. **Understanding Relationships Between Tables**  
   - Analyzing entity relationships to enable cross-dataset analysis.  
3. **Data Cleaning**  
   - Handling missing values, duplicates, and inconsistent formats.  
4. **Exploratory Data Analysis (EDA)**  
   - Investigating distributions, trends, and anomalies.  

## Key Analyses  

### Customer Analysis  
- **Demographics & Behavior:** Analyzing customer purchase frequency and lifetime value.  
- **Reviews & Sentiment:** Examining positive vs. negative reviews and their correlation with delivery time.  

### Sales Analysis  
- **Best-Selling Products (Revenue & Volume):** Identifying top-performing products and categories.  
- **Seasonality & Growth:** Comparing total orders between **2017 and 2018** to detect trends.  
- **Orders by Day of the Week:** Identifying peak order days for better marketing and inventory strategies.  

### Product Analysis  
- **Revenue Contribution by Category:** Determining which categories drive the most revenue.  
- **Inventory Optimization:** Ensuring popular products are in stock to maximize sales.  

### Seller Analysis  
- **Top-Performing Sellers & Locations:** Evaluating seller performance across different regions.  
- **Revenue by State:** Identifying states with the highest sales revenue (e.g., São Paulo).  

## Dataset Breakdown  
| Dataset | Description |
|---------|------------|
| `olist_orders_dataset` | Order details including status and timestamps. |
| `olist_order_items_dataset` | Items per order (product ID, seller ID, price, freight value). |
| `olist_order_reviews_dataset` | Customer reviews with ratings and comments. |
| `olist_products_dataset` | Product details (category, name, dimensions). |
| `olist_order_payments_dataset` | Payment methods and installments. |
| `olist_customers_dataset` | Customer IDs and geolocation. |
| `olist_geolocation_dataset` | Zip codes and coordinates. |
| `olist_sellers_dataset` | Seller IDs and locations. |

## Visualizations 

Refer to the **[[presentation slides](https://www.canva.com/design/DAGMC5w9X48/qP88fLvHr-JgDLcvO9n0LQ/edit?utm_content=DAGMC5w9X48&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)]** for charts and graphs illustrating key findings.  


![ presentaion ](https://github.com/user-attachments/assets/bc6de0c3-f7aa-4840-a36a-71095da21296)


## Dashboard Insights (power pi) 
- Order Reviews 
- Payment Methods
- Order Status Distribution 
- Top Ordered Product Categories  
- Top Revenue-Generating Product Categories
  
![order analysis](https://github.com/user-attachments/assets/3a6944d2-93a6-4eaa-a033-3c83b5687cef)


## Insights & Recommendations  
- **Marketing Strategy:** Focus on top-selling products and optimize promotions.  
- **Inventory Management:** Ensure high-revenue products remain in stock.  
- **Customer Experience:** Address delays in delivery to improve reviews.  
- **Payment Flexibility:** Leverage installment trends to optimize pricing strategies.  

---

Feel free to contribute or reach out with any questions! 🚀
