# UBER TRIP ANALYSIS DASHBOARD (POWERBI,EXCEL,POWERQUERY)
**Analyse Uber trip data to gain insights into booking trends, revenue 💰, trip efficiency 🚗, and customer behavior. Includes interactive dashboards, dynamic KPIs, time-based analysis, location insights 📍, vehicle type breakdown 🚘, and drill-through for granular data exploration.**

## 📌 DASHBOARD 1: OVERVIEW ANALYSIS
Analyse Uber trip data using Power BI to gain insights into booking trends, revenue, and trip efficiency, helping stakeholders make data-driven decisions.

## 💠 KPI's 
1. Total Bookings - How many trips were booked over a given period?
2. Total Booking Value - What is the total revenue generated from all bookings?
3. Average Booking Value - What is the average revenue per booking?
4. Total Trip Distance - What is the total distance covered by all trips?
5. Average Trip Distance - How far are customers traveling on average per trip? 6. Average Trip Time - What is the average duration of trips?
   
## 👉 Dataset used
<a href="https://github.com/harshgholap05/Uber-Trip-Analysis-Dashboard/blob/main/Location%20ID.xlsx">**LOCATION ID**</a>

<a href="https://github.com/harshgholap05/Uber-Trip-Analysis-Dashboard/blob/main/Uber%20Trip%20Details.xlsx">**UBER TRIP DETAILS**</a>

## 💠 Expected Outcomes
✔ Identify trends in ride bookings and revenue generation.

✔ Analyse trip efficiency in terms of distance and duration.

✔ Compare booking values and trip patterns across different time periods.

✔ Provide insights to optimize pricing models and improve customer satisfaction.

## 👉 Dashboard Interation
<a href="https://github.com/harshgholap05/Uber-Trip-Analysis-Dashboard/blob/main/Uber%20Trip%20Dashboard.pbix">**UBER TRIP ANALYSIS DASHBOARD**</a>

## 💠 CHART's
Create a Measure Selector using a Disconnected Table with the following values:

• Total Bookings

• Total Booking Value

• Total Trip Distance

Then, use a measure to dynamically update the visualizations based on user selection.

• By Payment Type (Card, Cash, Wallet, etc.)

• By Trip Type (Day/Night)

## 💠 Additional Enhancements:
➤ Dynamic Title - Update the chart title based on the selected measure.

➤ Slicers - Add filters for Date, City, and other interactive filters for deeper analysis.

➤ Tooltips - Show additional details like Average Booking Value or Trip Distance.

## 💠 Vehicle Type Analysis - Grid View in Power BI
Create a grid table (matrix or table visual) to analyse key performance indicators like Total Bookings, Total Booking Value, Avg Booking Value, Total Trip Distance across different Vehicle Types in Uber trips.

## 💠 Power BI Implementation:
 Use Table or Matrix Visual to display Vehicle Type with the KPIs.

 ➤ Apply Conditional Formatting to highlight high and low values. > Enable Sorting & Filtering for user interaction.

## 💠 Total Bookings by Day
 Detecting trends and fluctuations in daily trip volumes.

• Identifying peak and off-peak booking days.

• Understanding the impact of external factors (holidays, events, weather) on ride demand.

• Supporting strategic planning for resource allocation and pricing adjustments.

## 💠 Location Analysis
 Understanding trip locations is crucial for optimizing ride distribution, demand forecasting,
and operational efficiency. This analysis focuses on:

➤ Most Frequent Pickup Point

• Identify the most common starting locations for trips.
Helps in optimizing driver availability and dynamic pricing strategies.

➤ Most Frequent Drop-off Point

• Find the most common drop-off locations.

• Requires activating an inactive relationship in Power BI between Pickup Location
and Drop-off Location in the data model.

## 💠 Farthest Trip

• Determine the longest trip based on distance travelled.

• Useful for analysing outlier trips, long-distance demand, and fare optimization.

## 💠 Total Bookings by Location (Top 5)

• Identify the top 5 locations with the highest trip bookings.

• Helps in demand forecasting and optimizing driver availability in high-traffic areas.

## 💠 Most Preferred Vehicle for Location Pickup

• Determine the most frequently booked vehicle type at each pickup location.

• Supports strategic vehicle distribution based on customer preferences and location demand.

## 👉 Overview Analysis Dashboard 
<img width="1324" height="797" alt="image" src="https://github.com/user-attachments/assets/96caf37e-4550-4c2f-9aad-03b844988231" />

# 📌 Other Implementation Enhancements for Uber Trip Analysis Dashboard

##  💠 Bookmark for Data Details
• Add a "Data Details" bookmark to display a pop-up or side panel explaining:

• Meaning of key metrics (Total Bookings, Total Trip Distance, etc.)

• Description of tables used in the analysis.

• Data source and refresh frequency.

➤ Clear Slicer Button

• Add a "Clear Filters" button using a blank button with a Reset Slicers action to reset all selections in one click.

• Improves user experience for quick dashboard resets.

## 💠 Download Raw Data Button

• Add a button to export raw data in CSV or Excel format.

• Use Power Automate or built-in Power BI Export functionality.

• Enables users to analyse raw data outside Power BI if needed.


# 📌 DASHBOARD 2: TIME ANALYSIS
To understand trip patterns based on time, Uber needs to analyse ride demand and trends across different time intervals. This dashboard will help in optimizing operations, pricing, and driver availability.
Global Dynamic Measure (Filters All Charts)
A measure selector will be created for:

✓ Total Bookings

✓ Total Booking Value

✓ Total Trip Distance

This dynamic measure will update all visuals based on user selection


<img width="1280" height="782" alt="image" src="https://github.com/user-attachments/assets/1980ad9a-ca64-4cce-a631-a4a25dee1869" />

## 💠 Visualizations:
By Pickup Time (10-Minute Intervals) - Area Chart

•Groups trip bookings into 10-minute intervals throughout the day.

•Helps in identifying peak and off-peak demand periods.

## 💠 By Day Name Line Chart

• Shows booking trends across Monday to Sunday.

• Useful for analysing weekday vs. weekend demand.

## 💠 By Hour and Time - Heatmap (Matrix Grid)

• Rows: Hours of the Day (0-23)

• Columns: Days of the Week (Mon-Sun)

• Values: Selected Dynamic Measure (e.g., Total Bookings)

• Highlights peak booking hours across different days.



# 📌 DAHBOARD 3: DETAILS TAB
To provide in-depth insights and allow users to explore granular data, a Grid Tab will be created. This tab will enable drill-through functionality, allowing users to access detailed records based on selections made in other dashboards.


<img width="1282" height="781" alt="image" src="https://github.com/user-attachments/assets/2369c887-026b-4df4-a617-c3ba50324986" />


## 💠 Features of the Grid Tab:

➤ Grid Table with Key Fields:

• Displays essential trip details

➤ Drill-Through Functionality:


• Users can right-click on a data point from other visuals (e.g., charts, heatmaps) and drill through to this Grid Tab.

• Displays detailed records related to the selected data point.

## 💠 Bookmark for Full Data View:

• A "View Full Data" bookmark to toggle between filtered drill-through data and the complete dataset.

• Allows users to reset filters and see all records easily.

