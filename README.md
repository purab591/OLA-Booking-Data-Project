# OLA-Booking-Data-Project
Operational and Customer Insights Analysis for OLA Ride Bookings – Bengaluru
Project Overview
The OLA Data Analyst Project focuses on analyzing ride-booking data for Bengaluru city over a one-month period to derive actionable business insights. The project simulates a real-world ride-hailing dataset containing one lakh (100,000) records, designed to closely reflect actual booking behavior, customer preferences, operational challenges, and revenue patterns.
The primary objective of this project is to analyze booking performance, customer behavior, cancellation trends, ride distances, ratings, and revenue distribution. By applying structured data analysis techniques, the project converts raw ride data into meaningful insights that can help improve service quality, operational efficiency, and decision-making for a ride-hailing platform.
Business Context
Ride-hailing platforms like OLA handle massive volumes of data every day. Understanding this data is critical to:

Improve customer satisfaction

Reduce ride cancellations

Optimize vehicle utilization

Increase revenue

Monitor driver performance
This project mirrors real operational challenges such as weekend demand spikes, match-day surges, payment preferences, incomplete rides, and cancellation reasons from both customers and drivers.
Dataset Description

City: Bengaluru

 Duration: One Month

 Total Records: 1,00,000 bookings

 Vehicle Types: Auto, Bike, eBike, Mini, Prime Sedan, Prime Plus, Prime SUV

 Booking Success Rate: ~62%

 Customer Cancellations: ≤ 7%

 Driver Cancellations: ≤ 18%

 Incomplete Rides: ≤ 6%

 Higher demand & booking value on weekends and match days
The dataset includes comprehensive attributes such as booking details, pickup and drop locations, ride distance, booking value, cancellation reasons, ratings, and payment methods.
Key Objectives
1. Analyze overall booking performance and success rates
2. Identify cancellation patterns and their root causes
3. Evaluate ride distance trends across vehicle types
4. Assess customer and driver ratings to measure service quality
5. Understand revenue contribution by payment methods
6. Identify high-value and frequent customers
7. Study ride demand fluctuations across dates and days
SQL Analysis Overview
SQL was used to extract insights such as:

 Successful bookings

 Average ride distance by vehicle type

 Customer and driver cancellation counts

 Top 5 customers by ride frequency

 Driver rating extremes for Prime Sedan

 UPI-based transactions

 Total revenue from successful bookings

 Incomplete rides and their reasons
Views were created to ensure modular, reusable, and optimized query execution for analysis.
Dashboard & Visualization Overview
The insights were visualized using interactive dashboards, categorized into the following sections:
1. Overall Performance

 Ride Volume Over Time

 Booking Status Breakdown
2. Vehicle Type Analysis

 Top 5 Vehicle Types by Ride Distance
3. Revenue Analysis

 Revenue by Payment Method

 Top 5 Customers by Total Booking Value

 Ride Distance Distribution Per Day
4. Cancellation Analysis

 Customer Cancellation Reasons

 Driver Cancellation Reasons
5. Ratings Analysis

 Driver Ratings Distribution

 Customer Ratings Distribution

 Customer vs Driver Ratings Comparison
These visualizations help stakeholders quickly identify trends, problem areas, and opportunities for improvement.
Key Insights Generated

 Weekends and match days show significantly higher booking volumes and booking values

 Prime Sedan and Prime SUV contribute higher revenue despite fewer bookings

 UPI emerges as one of the most preferred payment methods

 Driver-related cancellations are higher than customer cancellations

 Higher ride distances generally correlate with better ratings

 A small percentage of customers contribute a large share of total revenue
Conclusion
This project demonstrates how structured data analysis can provide deep insights into ride-hailing operations. By analyzing booking behavior, cancellations, ratings, and revenue trends, the project highlights key performance drivers and areas requiring optimization. The insights generated can help ride-hailing companies improve operational efficiency, enhance customer experience, and increase profitability.
Overall, this project reflects real-world data analyst responsibilities, combining data preparation, SQL-based analysis, and insightful visual storytelling.
