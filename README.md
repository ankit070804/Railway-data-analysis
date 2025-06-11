Railway Operations & Sales Analytics Dashboard 🚂📊
This repository contains an Excel-based dashboard designed for comprehensive analysis of railway operations and ticket sales. This dashboard provides key insights into passenger behavior, route performance, revenue trends, and operational efficiency, aiding in strategic planning and service improvements.

Features ✨
This dashboard enables detailed analysis through various key metrics and visualizations, likely covering:

Sales Performance Overview:
Total revenue generated from ticket sales.
Breakdown of sales by Purchase Type (Online vs. Station) and Payment Method (Credit Card, Contactless, Debit Card).
Analysis of ticket prices across different Ticket Class (Standard, First Class) and Ticket Type (Advance, Off-Peak, Anytime).
Journey Performance & Reliability:
Monitoring of Journey Status (On Time, Delayed, Cancelled).
Identification of Reason for Delay (e.g., Staffing, Weather Conditions, Technical Issue, Traffic, Signal Failure).
Tracking of Refund Request linked to journey disruptions.

Route and Station Analysis:
Insights into popular Departure Station and Arrival Destination pairs.
Performance metrics for specific routes.
Customer & Ticket Segmentation:
Analysis of Railcard usage (None, Adult, Senior, Disabled) and its impact on sales or passenger demographics.
Comparison of sales and usage across different Ticket Class and Ticket Type.

Temporal Trends:
Sales and journey patterns over time, broken down by Date of Purchase and Date of Journey.
Daily, weekly, and monthly trends using Month Name, Month, Day of Week, and Day Name.

Data Sources 📋
The dashboard is built upon detailed transactional data related to railway ticket purchases and journey outcomes. The primary dataset is expected to contain columns such as:
Transaction ID: Unique identifier for each ticket purchase.
Date of Purchase: Date when the ticket was bought.
Time of Purchase: Time when the ticket was bought.
Purchase Type: Method of purchase (e.g., 'Online', 'Station').
Payment Method: How the ticket was paid for (e.g., 'Credit Card', 'Contactless', 'Debit Card').
Railcard: Type of railcard used, if any (e.g., 'None', 'Adult', 'Senior', 'Disabled').
Ticket Class: Class of travel (e.g., 'Standard', 'First Class').
Ticket Type: Type of ticket purchased (e.g., 'Advance', 'Off-Peak', 'Anytime').
Price: Cost of the ticket.
Departure Station: Origin station of the journey.
Arrival Destination: Destination station of the journey.
Date of Journey: Date of the planned travel.
Departure Time: Scheduled departure time.
Arrival Time: Scheduled arrival time.
Actual Arrival Time: Actual arrival time, to assess punctuality.
Journey Status: Outcome of the journey (e.g., 'On Time', 'Delayed', 'Cancelled').
Reason for Delay: Explanation for delays or cancellations (if applicable).
Refund Request: Indicates if a refund was requested.
Month Name, Month, Day of Week, Day Name, etc.: Derived time-based attributes for analysis.
