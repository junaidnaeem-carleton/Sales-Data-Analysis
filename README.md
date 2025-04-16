# 📊 Sales Data Analysis with MySQL & Tableau

This project connects **MySQL** with **Tableau** to perform a series of sales-driven calculations and visualizations. The database, named **`awesome chocolates`**, contains detailed records of dessert sales across multiple regions. The goal of this analysis is to derive business insights by calculating key performance metrics and visualizing them for strategic understanding.


``` The database is called, **awesome chocolates** and The database contains product-level information such as size, category, and pricing, linked to transactional sales data and sales personnel information across various locations and teams;
```
### Calculating Purchasing Power to Evaluate Customer Lifetime Value

####  Which location Brings the Most Valuable Customers?
Purchasing power is calculated by dividing the total sales amount by the number of customers, grouped by both location and team. This metric reveals how much value each customer contributes in different regions and team structures.
![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/new_tab1.png?raw=true)
![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/new_tab2.png?raw=true)



This map visualization provides a geographic overview of sales distribution, highlighting how different regions perform in terms of total sales volume. 

📌 **Insight** From the visual, it's clear that certain cities like Hyderabad, Seattle and Wellington are leading markets, indicating strong customer engagement and product movement in those areas.

![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/first.png?raw=true)
### Monthly Sales Performance & Category-Specific Insights

####  Which Month Brings the Most Revenue?
To analyze sales performance over time, monthly sales totals were calculated using SQL by grouping Amount by SaleDate. This helped identify patterns such as:

Which months experienced sales spikes

Seasonal performance trends

Growth or decline in customer spending behavior over time


![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/newtab4.png?raw=true)

![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/newtab5.png?raw=true)

![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/nt1.png?raw=true)

![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/nt2.png?raw=true)

The following visual on Tableau shows total sales incurred per month, offering a clear picture of how revenue varied across the year:
![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/new_tab3.png?raw=true)

📌 **Insight**:
The sales data reveals that Seattle consistently outperforms other regions, maintaining significantly higher sales volumes throughout the analyzed period. This indicates a strong and stable market presence in that location.


---

### Product Category Performance & Key Product Insights

To understand what types of products are performing best, a query was executed to **aggregate total sales by product category**. This allows us to identify which categories contribute the most to overall revenue and customer interest.

#### Which Product Types Sell the Most?
Product-Level Sales Trends Over Time

The following visuals track product-level sales by category:

![Product Category Analysis](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/final%201.png?raw=true)

📌 **Insight**:  
The chart indicates that **“Bars” are the most popular product category**, generating the highest number of sales and attracting the largest customer base. These are likely core offerings that appeal to a broad segment of customers.

In contrast, **“Special Items”** (previously labeled as “Other”) represent niche products typically associated with **limited availability or special occasions**. These items may have seasonal or event-driven demand rather than consistent year-round sales.

---

 

![Top-Selling Product Trends - View 1](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/g3.png?raw=true)
#### Top 5 Products in Top Performing Locations

To understand **where our best-selling products are generating the most traction**, we exported query results to Tableau. The visualization below highlights the **top 5 products** and how their sales are distributed across the **highest-performing locations**:

![Top-Selling Product Trends - View 2](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/ts1.png?raw=true)

![Top-Selling Product Trends - View 3](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/ts2.png?raw=true)

📌 **Insight**:  
This cross-analysis enables stakeholders to focus regional marketing strategies around specific high-demand products and prioritize stocking efforts in those areas.

![Top Products by Location](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/ds4.png?raw=true)


📌 **Insight**:  
This visualization showcases the top 5 best-selling products across the top 3 highest-performing sales locations. It highlights which products contribute the most to regional revenue, providing a focused view of what sells best and where.

For instance, products like "After Nines" and "Drinking Cocoa" are shown to consistently perform well in locations such as Seattle and Wellington, indicating a strong product-market fit in those cities. This insight is crucial for targeted stocking, promotions, and supply chain planning at the regional level.


---


---

### Final Interactive Tableau Dashboard

All insights were brought together in a **final interactive dashboard** built in Tableau. The dashboard provides a comprehensive view of **product performance, location-based trends**, and the ability to filter views dynamically.

![Interactive Tableau Dashboard - Full View](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/prj1.png?raw=true)

---

###  Drilldown: City-Level Sales Example

The image below shows a drilldown where **Wellington** was selected as the focus. The dashboard now displays metrics for Wellington only — including top products, purchasing power, and overall sales distribution:

![Interactive Dashboard - Wellington Focus](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/prj2.png?raw=true)

📌 **Insight**:  
This level of interactivity allows decision-makers to analyze **location-specific performance** and tailor product strategies to individual cities.

---
After conducting various analyses through SQL queries and visualizations, the final step is to consolidate these insights into a comprehensive Tableau dashboard. This allows the data to be presented in a clear, interactive, and summarized format, enabling stakeholders to easily interpret key performance trends and make informed decisions.
