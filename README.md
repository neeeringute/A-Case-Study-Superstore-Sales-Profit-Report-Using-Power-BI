# A Case Study: Superstore Sales & Profit Report Using Power BI

## Overview
This project involves the development of two interactive dashboards using **Power BI** to analyze the sales and profit performance of a US superstore. The data, sourced from the **Superstore retail transaction dataset** on **Kaggle**, covers the period from 2014 to 2018. By leveraging Power BI's data transformation and visualization capabilities, these dashboards provide insights into key metrics such as top products, sales by customer segments, geographic trends, and profit analysis.

## Tools Used
- **Power BI Desktop**: For data import, transformation, and visualization
- **Kaggle dataset**: Source of Superstore transaction data

## Prerequisites
Before starting, ensure you have:
- Power BI Desktop installed
- The Superstore dataset downloaded from Kaggle

---

## Sales Performance Dashboard

![image](https://github.com/user-attachments/assets/88a121fe-4ac4-4d97-a4c3-2c5fcda8fff1)


### Dashboard Overview
The **Sales Performance Dashboard** provides a comprehensive view of the superstore's sales metrics. The goal is to analyze top-selling products, total sales, customer count, and the geographic distribution of sales. Users can filter data dynamically to explore different time periods and customer behaviors.

### Key Visualizations

1. **Top 5 Products Based on Sales**:
   - A table that lists the top 5 products by sales amount. The product "HON 5400 Series Task Chairs for Big and Tall" ranks the highest with sales of $10,164.21.

2. **Total Sales and Total Customers**:
   - Two card visuals display:
     - **Total Sales**: $0.88M, representing the total revenue generated during the selected period.
     - **Total Customers**: 719, showing the distinct number of customers.

3. **Order Date Slicer**:
   - A slicer that allows users to filter the dashboard data by order date, enabling analysis of specific time ranges.

4. **Sales by Segments**:
   - A bar chart that breaks down sales by customer segments (Consumer, Corporate, Home Office). The **Consumer** segment has the highest sales.

5. **Sales and Profit by Sub-Category**:
   - A bar chart comparing sales and profit for various product sub-categories like Phones, Accessories, and Chairs. This provides insight into which product lines contribute the most to both sales and profit.

6. **Product Count by Ship Mode**:
   - This chart displays the number of products sold based on different shipping modes (Standard, Second Class, First Class, Same Day).

7. **Sales by City and State**:
   - A **TreeMap** visual displaying the sales performance in various cities and states. Cities such as **New York City** and **Los Angeles** are prominent sales hubs.

---

## Profit Analysis Dashboard

![Screenshot 2024-10-12 001218](https://github.com/user-attachments/assets/f5b6f994-d691-45e7-89cf-5bcb7b0061c0)

### Dashboard Overview
The **Profit Analysis Dashboard** offers a deeper dive into profit metrics, allowing users to explore profits across customer segments, regions, and product categories. By visualizing geographic and product-based profit data, the dashboard provides actionable insights into profitability trends.

### Key Visualizations

1. **Total Customers and Total Profit**:
   - Two card visuals show:
     - **Total Customers**: 719, representing unique customers.
     - **Total Profit**: $0.11M, reflecting the overall profit generated.

2. **Order Date Slicer**:
   - Similar to the Sales Dashboard, this slicer allows for filtering the profit data by order date.

3. **Top 10 Cities Based on Profits**:
   - A map that visualizes the top 10 cities contributing the most to profit. Cities like **New York** and **Los Angeles** lead in terms of profit.

4. **Top 10 States Based on Profits**:
   - A geographic visualization of the top 10 states contributing the most profit. **California**, **Texas**, and **New York** are key states driving profitability.

5. **Profit by Segment**:
   - A bar chart illustrating the distribution of profit across segments: **Consumer**, **Corporate**, and **Home Office**. The **Consumer** segment has the highest profit contribution.

6. **Profit by Region**:
   - A **Waterfall Chart** visualizing profits across US regions (East, West, South, Central). The **East** region is the most profitable, while **Central** has the lowest profit.

7. **Count of Sub-Category by Category**:
   - A bar chart that shows the number of sub-categories under each major category like **Office Supplies**, **Furniture**, and **Technology**. The Office Supplies category has the highest number of sub-categories.

---

## Conclusion and Key Takeaways
Both dashboards provide valuable insights into the performance of the superstore in terms of both sales and profit. By analyzing top products, customer segments, and geographic distribution, the dashboards allow for better decision-making in optimizing sales strategies and improving profitability. Power BI's dynamic filtering, coupled with its intuitive visuals, makes it a powerful tool for real-time business intelligence.

### Future Enhancements
- Expand the analysis to include **time-based trend visualizations** such as line charts.
- Introduce **predictive analysis** based on customer purchase history to forecast future sales and profit trends.


