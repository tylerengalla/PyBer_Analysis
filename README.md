# PyBer_Analysis

# Overview
Using Python and Pandas, we created a summary DataFrame of ride-sharing data by city type taken from two seperate csv files that contain metadata on thounsands of rides. Then, using Pandas and Matplotlib, we created a multiple-line graph that shows the total weekly fares for each city type. 

# Results

Here is the breakdown of how city types compare to each other in terms of Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver. 

![](/analysis/pyber_summary.png)

- As we might expect, Urban cities have the highest number of Drivers and Rides. Given the higher frequency of rides and the number of drivers avialable this seems to drive the Average Fare per Ride and Average Fare per Driver down as compared to the Rural and Suburban cities. 
- With less supply of Drivers and a smaller demand of Rides in Rural cities - this drove the Average Fare per Ride and Average fare per Driver to be the highest out of the city types. 

---

Below is a line graph showing us a comparison of the city types in terms of Total Fare of rides they received, broken down by weekly increments between the time frame of January - April. 

![](/analysis/PyBer_fare_summary.png)

- This tells us that our biggest source of revenue is coming from Urban cities, with Suburban cities next, followed by Rural last. 
- We can kind of see similarities across the city types when it comes to spikes and drops of Total Fares. This tells us that there is a common thread of predicitabliity when it comes to Total Fares as it reates to the time of the ride.  

# Summary
- **Urban** city type is by far the **highest revenue generating** with **Total Fares doubling** that of our second highest, **Suburbans**. But at the same time, **Total Rides of Suburbans** was **less than half that of Urban cities** - and **Total Drivers** in **Suburbans** is **1/5** of the Drivers in **Urban cities**. So if we can promote more demand within Suburban cities this would return the highest yield of returns in terms of Total Fares.  
- **Rural** city type has the **highest Averge Fare per Ride** but the **lowest number of Total Rides**. If we can promote more business in this city type - through promotions we may be able to increase overall revenue and thus bringing our Total Fare up for Rural city. 
- **Urban** cities is the **only one** where **Average Fare per Ride** is **more** than the **Average Fare per Driver**. This is because the Total Drivers in Ubran cities is more than the Total Rides. If we want to increase Average Fare per Driver for Urbans we will need to either promote more volume of rides or dilute the amount of Drivers working within Urban cities. 

