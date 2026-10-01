# CAB-S-Cab-Booking-Data-Analytics-Project
Cab booking data analysis project using Excel, SQL, and Power BI to analyze ride trends, revenue, cancellations, vehicle performance, and customer ratings.
Project Overview

The objective of this project is to transform raw cab booking data into meaningful business insights through SQL analysis and an interactive Power BI dashboard.

The project covers the complete analytics workflow, from working with structured booking data and writing SQL queries to visualizing key business metrics in Power BI.

Tools & Technologies
Microsoft Excel: Working with structured data, organizing columns, and preparing data for analysis.
SQL: Querying booking data, applying aggregations and filters, ranking customers, and creating reusable SQL views.
Microsoft Power BI: Building an interactive dashboard with charts and visualizations to analyze booking trends, revenue, cancellations, vehicle performance, and ratings.
Microsoft Word: Documenting SQL questions, queries, and answers for project reference.
Dataset Overview

The dataset contains cab booking and ride-related information, including booking details, vehicle types, pickup and drop locations, ride distances, payment methods, booking values, cancellations, and ratings.

Key Data Columns
Category	Columns
Booking Details	Date, Time, Booking_ID, Booking_Status
Customer & Vehicle	Customer_ID, Vehicle_Type
Trip Information	Pickup_Location, Drop_Location, Ride_Distance
Trip Timing	V_TAT, C_TAT
Cancellations	cancelled_Rides_by_Customer, cancelled_Rides_by_Driver
Incomplete Rides	Incomplete_Rides, Incomplete_Rides_Reason
Revenue & Payments	Booking_Value, Payment_Method
Ratings	Driver_Ratings, Customer_Rating
SQL Analysis

I developed SQL queries to answer 10 business questions and created reusable SQL views for retrieving the results.

Retrieve all successful bookings.
Calculate average ride distance for each vehicle type.
Count rides cancelled by customers.
Identify the top 5 customers by number of rides booked.
Count driver cancellations caused by personal and car-related issues.
Find the maximum and minimum driver ratings for Prime Sedan bookings.
Retrieve rides paid for using UPI.
Calculate average customer ratings for each vehicle type.
Calculate the total booking value of successfully completed rides.
Retrieve incomplete rides along with their reasons.

SQL concepts used: SELECT, WHERE, GROUP BY, aggregate functions such as COUNT(), AVG(), SUM(), MAX() and MIN(), ORDER BY, LIMIT, and CREATE VIEW.

Power BI Dashboard

The Power BI dashboard presents booking data through visualizations designed to support business analysis.

Dashboard Analysis Areas

1. Overall Performance

Ride volume over time
Booking status breakdown

2. Vehicle Performance

Top 5 vehicle types by ride distance
Average customer ratings by vehicle type

3. Revenue Analysis

Revenue by payment method
Top 5 customers by total booking value
Ride distance distribution by day

4. Cancellation Analysis

Customer cancellation reasons
Driver cancellation reasons

5. Ratings Analysis

Driver rating distribution
Customer ratings
Comparison of customer and driver ratings

These visualizations help explore booking patterns, vehicle usage, cancellation trends, payment preferences, revenue distribution, and customer experience.

Project Workflow
Data Preparation — Excel: Work with the booking dataset and organize the data for analysis.
Data Analysis — SQL: Write queries to answer business questions and create reusable views.
Data Visualization — Power BI: Present key metrics and trends through a dashboard.
Documentation — Word: Maintain the SQL questions, queries, and answers for reference.
Business Value

This project demonstrates how data analytics can support cab-booking operations by helping stakeholders:

Monitor ride volumes and booking status.
Identify frequently used vehicle types and ride-distance patterns.
Track customer and driver cancellation reasons.
Analyze booking value across payment methods and customers.
Compare customer and driver ratings.
Use data-driven insights to support operational monitoring and decision-making.
Project Files
CAB_S Dashboard.pbix — Power BI dashboard file.
CAB-S Data-Analyst-Project.docx — SQL questions, queries, answers, and dashboard analysis documentation.
Excel Dataset — Add the source Excel file to the repository if it is available to share.
Skills Demonstrated

Microsoft Excel | SQL | Power BI | Data Analysis | Business Intelligence | Data Visualization | KPI Monitoring | Business Reporting

Author

Abhinav Dwivedi

Aspiring Data Analyst interested in using data, analytics, and business intelligence tools to turn raw data into meaningful insights.
