# Metro Transport Company Data Analysis
## Overview
This is a comprehensive data analysis of Metro Transport Company's current bus lines. As a Data Analyst, the objective was to assess the operational efficiency and financial performance of the bus lines, providing actionable insights for potential improvements.

## Project Structure
* **Assessment_Data_Sababi.xlsx:** The Excel file with three key datasets - Routes, Times, and Passengers.
* **transportanalysis.ipynb:** Jupyter notebooks used for data analysis and visualization.
* **README.md:** Project overview, findings summary, recommendations, and conclusion.

## Data Understanding
### Routes Table:
* **bus_num:** Bus line number
* **intercity:** Indicates if the bus line operates between cities (yes/no)
* **type:** Type of bus service (express/regular)
* **num_stops:** Number of stops made by the bus
* **fare:** Cost of a single bus ticket

### Times Table:
* **time_of_week:** Weekday or weekend
* **bus_num:** Bus line number
* **first_bus:** Departure time of the first bus
* **last_bus:** Departure time of the last bus
* **frequency:** Number of times the bus completes its route daily

### Passengers Table:
* **day:** Day of the week
* **bus_num:** Bus line number
* **average_num_passengers:** Average number of passengers per route

## Exploratory Data Analysis (EDA)
### Key Findings
1. **Problematic Bus Lines:** Identified 13 bus lines facing potential operational issues over weekends due to high costs compared to revenue.
2. **Lowest Revenue Bus Line:** Bus line 1 exhibited the lowest average weekly revenue from ticket sales, signaling a potential area for improvement.
3. **Revenue Trends Across Days:** Friday emerged as the most profitable day, while Saturday experienced the lowest revenue. 

### Recommendations
1. **Optimize Problematic Bus Lines:** Consider discontinuing or restructuring bus lines flagged as problematic to mitigate financial losses.
2. **Revenue Enhancement:** Explore strategies to increase revenue on weekends, especially on Saturdays, through promotional offers, route adjustments, or marketing campaigns.
3. **Efficiency Improvements:** Analyze operational processes to identify areas for cost reduction and efficiency enhancement, potentially reducing operational costs per route.

### Conclusion
The analysis provides valuable insights into Metro Transport Company's bus operations. By addressing problematic bus lines, optimizing revenue generation, and improving operational efficiency, the company can enhance its overall performance and customer satisfaction. Continued data-driven decision-making will be essential for sustained success in the competitive transportation industry.
