# Ola-Data-Analytics-Project

## Recommended Structure and Order
### 1.	Project Title / Headline
RidePulse — OLA Fleet Performance Dashboard  
A compact, interactive dashboard tracking bookings, revenue, cancellations, and ratings across vehicle types.
Visualizes vehicle-level KPIs including booking value, success rates, average distance, and total distance.
Designed for operations and product teams to spot trends, diagnose issues, and optimize fleet performance.


### 2.	Short Description / Purpose

An interactive Power BI dashboard (backed by SQL and Excel) that visualizes OLA ride-booking KPIs—bookings, revenue, cancellations, payment mix, distance metrics, and driver/customer ratings—for July 2025.
It exists to help operations and product teams quickly identify performance trends, diagnose cancellation drivers, optimize fleet allocation, and prioritize revenue‑boosting actions.

### 3.	Tech Stack

The dashboard was built using the following tools and technologies:

• 📊 Power BI Desktop – Main data visualization platform used to design interactive reports and publish the .pbix file.
• 📂 Power Query (Power BI / Excel) – ETL layer for data extraction, transformation, and loading; used to clean, merge, and shape raw booking and telemetry data.
• 🧠 DAX (Data Analysis Expressions) – Calculated measures, time‑intelligence metrics, and dynamic KPIs (e.g., cancellation rate, success rate, rolling averages).
• 🗄️ SQL (Postgres / MySQL / SQL Server) – Source queries and stored procedures for aggregating booking, payment, distance, and rating data; used for data pulls and pre‑aggregation.
• 📈 Excel (Power Query, PivotTables) – Ad‑hoc analysis, validation, and intermediate data staging; exports and sample datasets saved as .xlsx/.csv.
• 📝 Data Modeling & File Formats – Star/schema relationships between fact_bookings and dimension tables (vehicle_type, customer, driver, payment_method); deliverables: .pbix, .sql scripts, .xlsx, and .csv for snapshots.

### 4.	Data Source
#### Overview  
The dashboard is built from operational and analytical data collected from OLA’s ride‑hailing systems for the period shown (July 1–31, 2025). Data is ingested from transactional databases, telemetry feeds, and supporting CSV/Excel extracts to produce the booking, revenue, cancellation, distance, and rating KPIs.

### 5.	Features / Highlights
#### -Business Problem

Fragmented operational visibility across bookings, revenue, cancellations, and ratings makes it hard for OLA teams to quickly identify root causes of revenue leakage, high cancellation pockets, and underperforming vehicle segments.
Key questions include: Which vehicle types drive the most revenue? What are the dominant cancellation reasons and who cancels more (drivers or customers)? Which payment methods and customers contribute most to monthly revenue?

#### -Goal of the Dashboard

To provide a single interactive analytics surface that surfaces vehicle‑level performance, payment mix, cancellation drivers, and satisfaction metrics for July 2024 so operations, product, and finance teams can prioritize interventions, reduce cancellations, and increase revenue per trip.

#### -Walkthrough of Key Visuals

Top KPIs Panel  
Total Bookings, Total Booking Value, Succeeded Bookings, and Cancellation Rate give an at‑a‑glance health check for the month.


#### -Booking Status Breakdown Pie Chart 

Visualizes success vs driver/customer cancellations and driver‑not‑found cases to show where fulfillment fails.

#### -Vehicle Type Table

Compares Total Booking Value, Success Booking Value, Avg. Distance Travelled, and Total Distance Travelled across vehicle types (Prime Sedan, SUV, Mini, Auto, Bike, E‑Bike) to reveal high‑value and high‑utilization segments.

#### -Revenue by Payment Method Bar Chart  

Shows revenue contribution by Cash, UPI, Credit Card, Debit Card to prioritize payment reconciliation and promotions.

#### -Daily Ride Distance / Volume Trend  

Line/bar chart of daily ride distance and booking counts across July to detect seasonality, spikes, or operational anomalies.

#### -Cancellation Reason Pie Charts

Two charts split cancellations By Customer and By Driver, listing top reasons (driver not moving, change of plans, personal/car issues, customer behavior) to guide targeted fixes.

#### -Top Customers Table

Lists highest‑value customers to support retention, VIP offers, and fraud/reconciliation checks.

#### -Ratings Tables

Side‑by‑side Driver Ratings and Customer Ratings by vehicle type to monitor service quality and identify training or product issues.

#### -Business Impact and Insights Operational Efficiency

Pinpoints where driver availability or routing issues cause cancellations so dispatch and incentives can be adjusted to reduce failed pickups.

#### -Revenue Optimization

Identifies high‑value vehicle types and payment channels (e.g., Cash, UPI) to focus settlement reconciliation and targeted promotions that increase take‑rate.

#### -Customer Retention and Segmentation

Highlights top customers and satisfaction gaps by vehicle type to design loyalty offers and service improvements for high‑value segments.

#### -Product and Driver Interventions

Reveals recurring driver‑side cancellation reasons and rating dips, enabling targeted training, vehicle maintenance checks, or policy changes.

#### -Actionable Next Steps

Examples: prioritize driver re‑allocation during peak days, run targeted campaigns for UPI adoption, create driver incentives for pickup reliability, and launch follow‑up surveys for top cancellation reasons.

### 6.	Screenshots / Demos
Show what the dashboard looks like.
Example: ![Dashboard Preview](https://github.com/vanshchaudhary-data/Ola-Data-Analytics-Project/blob/main/snapshot%20of%20the%20Dashboard.png)

