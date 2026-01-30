📌 Project Overview

The OLA Data Analyst Project analyzes ride-booking data for Bengaluru city over a one-month period to derive actionable business insights. This project simulates a real-world ride-hailing dataset containing 100,000 booking records, closely reflecting actual customer behavior, operational challenges, and revenue patterns.

The primary objective is to convert raw booking data into meaningful insights that can help improve service quality, operational efficiency, and data-driven decision-making for a ride-hailing platform.

🧠 Business Context

Ride-hailing platforms like OLA process massive volumes of data daily. Effective analysis of this data is essential to:

Improve customer satisfaction

Reduce ride cancellations

Optimize vehicle utilization

Increase revenue

Monitor driver performance

This project mirrors real-world challenges such as weekend demand spikes, match-day surges, payment preferences, incomplete rides, and cancellation reasons from both customers and drivers.

📂 Dataset Description

City: Bengaluru

Duration: One Month

Total Records: 100,000 ride bookings

Vehicle Types: Auto, Bike, eBike, Mini, Prime Sedan, Prime Plus, Prime SUV

Booking Success Rate: ~62%

Customer Cancellations: ≤ 7%

Driver Cancellations: ≤ 18%

Incomplete Rides: ≤ 6%

Key Patterns: Higher demand and booking value on weekends and match days

The dataset includes booking details, pickup and drop locations, ride distance, booking value, cancellation reasons, customer and driver ratings, and payment methods.

🎯 Key Objectives

Analyze overall booking performance and success rates

Identify cancellation patterns and root causes

Evaluate ride distance trends across vehicle types

Assess customer and driver ratings to measure service quality

Understand revenue contribution by payment methods

Identify high-value and frequent customers

Study ride demand fluctuations across dates and days

🗄️ SQL Analysis Overview

SQL was used to extract actionable insights, including:

Successful ride bookings

Average ride distance by vehicle type

Customer and driver cancellation counts

Top 5 customers by ride frequency

Driver rating extremes for Prime Sedan

UPI-based transactions

Total revenue from successful bookings

Incomplete rides and associated reasons

Views were created to ensure modular, reusable, and optimized query execution.

📊 Dashboard & Visualization Overview

Insights were visualized using interactive dashboards, grouped into the following sections:

1️⃣ Overall Performance

Ride Volume Over Time

Booking Status Breakdown

2️⃣ Vehicle Type Analysis

Top 5 Vehicle Types by Ride Distance

3️⃣ Revenue Analysis

Revenue by Payment Method

Top 5 Customers by Total Booking Value

Ride Distance Distribution Per Day

4️⃣ Cancellation Analysis

Customer Cancellation Reasons

Driver Cancellation Reasons

5️⃣ Ratings Analysis

Driver Ratings Distribution

Customer Ratings Distribution

Customer vs Driver Ratings Comparison

These dashboards enable stakeholders to quickly identify trends, problem areas, and opportunities for improvement.

🔍 Key Insights Generated

Weekends and match days show significantly higher booking volumes and booking values

Prime Sedan and Prime SUV generate higher revenue despite fewer bookings

UPI is one of the most preferred payment methods

Driver-initiated cancellations are higher than customer cancellations

Higher ride distances generally correlate with better ratings

A small percentage of customers contribute a large share of total revenue

🛠️ Tools & Technologies Used

SQL (MySQL) – Data querying and analysis

MS Excel – Data validation and preprocessing

Power BI – Dashboard creation and data visualization

📌 Conclusion

This project demonstrates how structured data analysis can deliver deep insights into ride-hailing operations. By analyzing booking behavior, cancellations, ratings, and revenue trends, the project highlights key performance drivers and operational gaps.

The insights generated can help ride-hailing companies optimize operations, enhance customer experience, and improve profitability. Overall, this project reflects real-world Data Analyst / Business Analyst responsibilities, combining data preparation, SQL-based analysis, and impactful visual storytelling.
