#                                         🚗 Data Analytics in Uber Dataset

1. Dataset Summary:
   
- Total Data Entries: 1156
- Columns Used: 'START_DATE', 'END_DATE', 'CATEGORY', 'START', 'STOP', 'MILES',
       'PURPOSE', 'Time', 'Date', 'Hour', 'Day-Night', 'Month', 'Day'.
  
---
2. Preprocessing:
   
- Converted Date/Time to datetime format
- Extracted:
- Hour: 0–23
- Day of Week: Monday–Sunday
- Month: April–September
- Removed missing values (if any)
---
3. Key Quantitative Insights from EDA:
   
- A. Rides Per Day
Peak Day: Highest number of rides recorded on April 30th: ~250 rides

Average Daily Rides: ~200–250 per day

- B. Hourly Trends
Peak Hours: 5 PM – 6 PM (17:00–18:00) had the most rides

Lowest Activity: 3 AM – 4 AM

- C. Monthly Distribution
  
Rides by month:

April: ~5,000

May: ~3,500

June: ~3,300

July: ~2,600

August: ~2,400

September: ~1,800

April was the busiest month

- D. Day of Week
Busiest Day: Friday (~1,200+ rides)

Least Busy: Sunday (~800 rides)

- E. Heatmap Analysis
- 
Generated heatmaps showing frequency of rides:

By Hour vs Day

By Day vs Month

Densest activity on weekday evenings

---
4. Quantitative Role of Data Analytics :- Data analytics contributed to the following:

- Role	Output / Value Generated
- Time Optimization	Identified peak hours (17:00–18:00) for demand
- Demand Forecasting	Monthly trend showed peak in April
- Resource Allocation	Busiest bases optimized fleet deployment
- Performance Monitoring	Trends by base IDs and weekdays measured
- Operational Strategy	Low-demand periods identified for cost-cutting
- Geospatial Planning	Pickup hotspots for potential service expansion
 --- 
5. Conclusion:- Quantitative data analytics enabled:

- Precise identification of temporal and spatial trends
- Informed decision-making using hourly, daily, and monthly metrics
- Strategic improvements in fleet, service availability, and customer engagement
