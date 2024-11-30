# Atliq Grands - Business and Data Intelligence

## Project Overview
Atliq Grands owns multiple five-star hotels across India and has been in the hospitality industry for the past 20 years. Recently, they have faced challenges in retaining their market share and revenue in the luxury/business hotel category due to strategic moves by competitors and ineffective decision-making within the management.

In response, the Managing Director of Atliq Grands decided to incorporate Business and Data Intelligence into their operations to regain market share and increase revenue. However, Atliq Grands does not have an in-house data analytics team to provide these insights. As a result, they hired a third-party service provider to analyze their historical data and offer actionable insights.

The goal of this project is to provide actionable business insights to the Revenue Management team in the hospitality domain by utilizing historical data provided.

---

## Objective 🎯
**Objective:**  
Provide actionable insights to the Revenue Management team in the Hospitality Domain, focusing on metrics such as bookings, revenue, occupancy rate, cancellations, and customer ratings.

---

## Data Sources 📀
The project utilizes the following five CSV files which contain historical hotel booking data:

1. **dim_date** - Contains date-related information.
2. **dim_hotels** - Contains details about hotels.
3. **dim_rooms** - Contains details about rooms in the hotels.
4. **fact_aggregated_bookings** - Contains aggregated booking data for analysis.
5. **fact_bookings** - Contains detailed individual booking data.

---

## Tools and Technologies 🛠
- **Microsoft Power BI** - For data visualization, creating dashboards, and generating insights.
- **Data Processing and Analysis** - Tools like Python or SQL (if required) can be used for processing and preparing the data.

---

## Metrics to be Created 📊
The following key metrics will be calculated from the provided data:

- **Total Bookings** - Total number of bookings made.
- **Revenue** - The total revenue generated from all bookings.
- **Average Rating** - The average rating of the hotel (based on customer reviews).
- **Total Capacity** - The total available capacity (number of rooms).
- **Total Successful Bookings** - Number of bookings that were successfully completed.
- **Occupancy %** - Percentage of rooms occupied relative to total capacity.
- **Total Cancelled Bookings** - Number of bookings that were cancelled.
- **Cancellation Rate** - Percentage of bookings that were cancelled out of the total bookings.

---

## Dashboard Mock-up 📈
The dashboard will visualize the following information based on the metrics:

- Key performance indicators (KPIs) such as total bookings, revenue, and occupancy rates.
- Performance across various hotels and cities, including:
  - Booking trends over time.
  - Cancellation rates and occupancy trends.
  - Ratings distribution.
- Detailed views of metrics such as cancellations, successful bookings, and average ratings by hotel or city.

---

## Relevant Insights 💡
In addition to the required metrics, the following insights will be derived from the data:

1. **Revenue Growth Opportunity**:  
   Suggest ways to increase revenue by 29% through strategies such as promoting late bookings and encouraging longer stays.

2. **Occupancy Trends**:  
   Observing that occupancy is at its highest on weekends, identify opportunities for targeted pricing or promotions to increase weekend bookings.

3. **Booking Platforms Analysis**:  
   Identify the most effective booking platforms for attracting customers. It was found that bookings through third-party platforms such as "Others" and "MakeMyTrip" contribute significantly to the overall bookings.

4. **Average Ratings**:  
   The average customer rating across all hotels is between 3.6 and 3.65. This suggests room for improvement in customer satisfaction.

5. **City-based Performance**:  
   - **Delhi** shows high average ratings, which could be used as a marketing strength.
   - **Mumbai** and **Hyderabad** exhibit a significant drop in occupancy during the month of June. Investigating the factors behind this could reveal potential for revenue improvement.

---

## Conclusion 💡
By utilizing the insights derived from the provided data, Atliq Grands can focus on the following strategies to enhance revenue and occupancy:

- **Increase Revenue by 29%**: By focusing on late bookings, longer stays, and adjusting pricing strategies based on occupancy trends.
- **Weekend Occupancy Optimization**: Focus on boosting bookings on weekends, which show the highest occupancy.
- **Platform-Specific Strategies**: Optimize the use of popular booking platforms like "Others" and "MakeMyTrip" to enhance visibility and sales.
- **Improving Customer Satisfaction**: Investigate the factors affecting average ratings, especially in cities like Mumbai and Hyderabad, to improve the customer experience.

---

## How to Use This Dashboard
1. **Open the Power BI file**: The report is created using Microsoft Power BI. Open the `.pbix` file using Power BI Desktop.
2. **Explore the Dashboard**: Use filters and slicers to explore the data based on city, hotel, date, and other parameters.
3. **Analyze Metrics**: View KPIs such as total bookings, revenue, and occupancy rates across different dimensions.
4. **Derive Insights**: Look for patterns in bookings, cancellations, and ratings to draw actionable insights.

---

## Installation Instructions ⚙️
1. **Install Power BI Desktop**:  
   If you don’t have Power BI installed, download and install it from [Power BI Downloads](https://powerbi.microsoft.com/downloads/).

2. **Open Power BI File**:  
   Once installed, open the `.pbix` file to access the dashboard.

3. **Connect to Data Sources**:  
   If needed, configure data sources in Power BI to point to the CSV files provided.

4. **Start Exploring**:  
   Begin exploring the metrics and insights visualized in the dashboard.

---


---

## Acknowledgements
- Thanks to Atliq Grands for providing the data and giving us the opportunity to work on this project.
- All data sources and tools used in this project are attributed to their respective providers.

---

