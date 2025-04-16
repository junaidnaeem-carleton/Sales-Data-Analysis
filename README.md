# 📊 Sales Data Analysis with MySQL & Tableau

This project connects **MySQL** with **Tableau** to perform a series of sales-driven calculations and visualizations. The database, named **`awesome chocolates`**, contains detailed records of dessert sales across multiple regions. The goal of this analysis is to derive business insights by calculating key performance metrics and visualizing them for strategic understanding.


``` The database is called, **awesome chocolates** and The database contains product-level information such as size, category, and pricing, linked to transactional sales data and sales personnel information across various locations and teams;
```

![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/new_tab1.png?raw=true)

Purchasing power is calculated by dividing the total sales amount by the number of customers, grouped by both location and team. This metric reveals how much value each customer contributes in different regions and team structures.

![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/new_tab2.png?raw=true)


Monthly Sales Performance & Category-Specific Insights
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



The sales indicate that Seattle is considerably ahead against others with Sales being consistantly high

Now, lets run a query indicating which type of products are sold the most
![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/final%201.png?raw=true)

The chart indicates that 'bars' attract more customers than others. Moreover, speciality items are those which are issued on special occasions only
![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/g3.png?raw=true)

![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/ts1.png?raw=true)
![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/ts2.png?raw=true)

Exporting thr csv to Tableau will give us the following to show the top 5 products sold at top performing locations
![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/ds4.png?raw=true)

To conclude, we have developed the interactive dashboard where we can see product and location performance
![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/prj1.png?raw=true)

In the second image, 'Welington location' is selected to show the performance of the city in terms of sales and most products sold
![Query Output](https://github.com/junaidnaeem-carleton/Sales-Data-Analysis/blob/main/prj2.png?raw=true)
