# Uber Trip Analysis – Power BI Dashboard

## Project Overview

This project presents a Power BI dashboard designed to analyze **Uber trip booking data** to understand booking trends, revenue patterns, trip behavior, customer preferences, and operational efficiency.

The dashboard enables stakeholders to gain insights into **trip volume, booking value, distance, time patterns, payment behavior, vehicle performance, and location-based demand**, supporting data-driven decision-making in a ride-hailing business context.

---

## Business Objective

Ride-hailing platforms like Uber operate in a highly dynamic, demand-driven environment.  
The objective of this project is to support business and operations teams in:

- Monitoring overall booking and revenue performance
- Understanding trip demand by time, day, and location
- Analyzing customer payment preferences
- Evaluating vehicle category performance
- Identifying high-demand pickup and drop-off locations
- Optimizing fleet allocation and operational planning

---

## Overview Dashboard

![Overview Dashboard](https://github.com/sagar201993/Ube_Analysis_PowerBI/blob/main/dash1.png)

### Business Questions Answered
- How many total trips were completed?
- What is the total and average booking value?
- What are the average trip distance and duration?

### Insights and Business Interpretation
- A high number of total bookings combined with a stable average booking value indicates **consistent ride demand**.
- Average trip distance and duration suggest that **short-to-medium distance trips dominate**, which is typical for urban mobility services.
- These metrics provide a high-level health check of the business.

### Business Impact
- Helps leadership quickly assess platform performance
- Supports revenue monitoring and operational benchmarking

---

## Time Analysis Dashboard

![Time Analysis Dashboard](https://github.com/sagar201993/Ube_Analysis_PowerBI/blob/main/dash2.png)

### Business Questions Answered
- At what times of day is demand highest?
- Which days of the week generate the most bookings?
- How does demand vary by hour and weekday?

### Insights and Business Interpretation
- Booking trends show **clear peak demand during daytime and evening hours**, indicating commuter and leisure usage.
- Weekday vs weekend patterns highlight **different travel behaviors**, with weekends showing higher leisure-related demand.
- Hourly heatmap analysis identifies **critical peak hours** where demand significantly increases.

### Business Impact
- Supports driver supply and shift planning
- Helps reduce wait times during peak demand
- Enables time-based pricing and incentive strategies

---

## Trip Details Dashboard

![Trip Details Dashboard](https://github.com/sagar201993/Ube_Analysis_PowerBI/blob/main/dash3.png)

### Business Questions Answered
- What are the characteristics of individual trips?
- How do booking value and distance vary across trips?
- Which routes and locations are frequently used?

### Insights and Business Interpretation
- Trip-level analysis shows **variation in fare amounts based on distance and pickup/drop-off locations**.
- Certain routes consistently generate higher fares, indicating **high-value corridors**.
- Passenger count and payment method data help understand user behavior at a granular level.

### Business Impact
- Enables detailed auditing and operational analysis
- Supports pricing and route optimization decisions
- Helps identify anomalies or unusual trip patterns

---

## Location Analysis

### Business Questions Answered
- Which locations generate the most pickups and drop-offs?
- What are the most frequent travel routes?
- Which locations require higher vehicle availability?

### Insights and Business Interpretation
- High-frequency pickup locations such as major transit hubs indicate **strong demand around transportation centers**.
- Frequent drop-off locations highlight **residential and commercial demand zones**.
- The longest-distance trips represent **edge cases with higher revenue impact**.

### Business Impact
- Supports geo-based fleet positioning
- Improves driver allocation efficiency
- Helps reduce idle time and operational costs

---

## Vehicle Type Analysis

### Business Questions Answered
- Which vehicle categories generate the most bookings?
- How does booking value differ by vehicle type?
- Which vehicle types are preferred by customers?

### Insights and Business Interpretation
- Standard vehicle categories (e.g., UberX) dominate total bookings, indicating **price-sensitive customer behavior**.
- Premium vehicle categories contribute fewer trips but generate **higher revenue per booking**.
- This reflects a balanced demand between affordability and premium services.

### Business Impact
- Supports fleet mix optimization
- Guides incentive strategies for different vehicle categories
- Helps maximize revenue per trip

---

## Payment Type Analysis

### Business Questions Answered
- Which payment methods are most commonly used?
- How does payment preference impact booking behavior?

### Insights and Business Interpretation
- Digital payment methods dominate, indicating **strong adoption of cashless transactions**.
- Cash usage still exists, highlighting the need to support **multiple payment options**.
- Payment trends can influence promotional and partnership strategies.

### Business Impact
- Improves payment system planning
- Supports partnerships with digital payment providers
- Enhances customer checkout experience

---

## Data Model Overview

![Data Model](https://github.com/sagar201993/Uber_Trip_Analysis_Dashboard/blob/main/model.png)

### Tables Used
- Trip Details: Trip-level booking, fare, distance, time, and payment data
- Location Table: Pickup and drop-off location mapping
- Calendar Table: Date and time intelligence
- Dynamic Measure Table: Measure switching for interactive analysis

### Modeling Approach
- Star schema design
- Dedicated calendar table for time-based analysis
- Optimized relationships for accurate filtering and performance

---

## Data Source and Assumptions

The dataset used in this project represents a structured dataset simulating real-world Uber trip activity.

Key assumptions:
- Each record represents a completed trip
- Fare amount reflects total booking value per trip
- Trip distance is measured in miles
- Pickup and drop-off locations are correctly mapped
- All monetary values are assumed to be in USD

---

## Key KPIs and Metrics

- Total Bookings
- Total Booking Value
- Average Booking Value
- Total Trip Distance
- Average Trip Distance
- Average Trip Duration
- Bookings by Time, Day, and Hour
- Bookings by Location
- Bookings by Vehicle Type
- Bookings by Payment Type

Each KPI is aligned with operational efficiency and revenue optimization goals.

---

## Technical Highlights

- Time intelligence using a calendar table
- Dynamic measure switching for interactive visuals
- Hourly and daily demand analysis
- Structured Power Query transformations
- Optimized DAX measures for performance and clarity

---

## Performance and Best Practices

- Star schema data modeling
- Removal of unused columns during data preparation
- Measures preferred over calculated columns
- Consistent naming conventions
- Optimized relationships for scalability

---

## Limitations and Future Improvements

Current limitations:
- Dataset represents a simulated scenario
- Real-time trip tracking is not implemented

Potential future enhancements:
- Real-time data integration
- Predictive demand forecasting
- Surge pricing simulation
- Driver performance analysis
- City-level expansion analysis

---

## How to Use the Dashboard

1. Open the `.pbix` file in Power BI Desktop
2. Use date and city slicers to filter data
3. Navigate between dashboard pages using the menu
4. Hover over visuals for detailed insights
5. Drill down into trip-level data for deeper analysis

---

## Tools and Technologies

- Power BI Desktop
- Power Query for data transformation
- DAX for KPI and time-based calculations
- Data modeling and relationship management

---

## Key Skills Demonstrated

- Transportation and mobility analytics
- Time-series and demand analysis
- Revenue and pricing insights
- Data modeling best practices
- Business-focused dashboard storytelling

---

## Portfolio Summary

This project demonstrates how data analytics can be applied to ride-hailing platforms to understand demand patterns, optimize operations, improve revenue performance, and enhance overall service efficiency.
