# Uber Intelligence
#### Visualizing Ride-Hailing Insights for Business Strategy
## Project Overview
This Power BI project dives into ride-hailing data using UberTrip datasets to uncover key trends in bookings, customer behavior, and operational efficiency.

I built a dynamic, multi page dashboard that enables stakeholders to explore performance metrics across locations, vehicles, payment methods, and time all driven by an efficient data model and interactive visuals.

This project reflects what I do best: turn messy datasets into clear, visual, business-relevant stories.

## What This Dashboard Solves
What’s the overall performance of Uber trips?

How do trip patterns vary by time of day and day of the week?

What payment types and vehicle types are preferred by riders?

Which cities and locations drive the most activity?

## Tools Used
- Power BI	Dashboard creation and data modeling
- Power Query	Data cleaning and transformation
- DAX	Calculated columns, measures, and KPI logic
- Excel	Initial cleaning and validation
- GitHub	Project showcase and documentation

## Data Model
UberTrip Table and Location Table joined via Location ID

Built a Calendar Table using DAX for time-based slicing

Implemented 1-to-many relationships for optimized visuals and filters

Follows a Star Schema structure for clean performance

![Data Model](https://github.com/Oluchiumeh/Uber-Trip-Analysis/blob/main/Data%20Model.png)

## Dashboard Structure
### Overview Analysis

High-level performance metrics and breakdowns:

KPIs:

- Total Bookings

- Total Booking Value

- Average Booking Value

- Total Trip Distance

- Average Trip Distance

- Average Trip Time

Measure Selector: Allows switching between key metrics for focused analysis

Visual Breakdown:

- Payment Type 

- Total Bookings by Trip Type

- Vehicle Type Analysis

- Top Pickup & Drop-Off Locations

Slicers: Date and City for granular exploration
  
![Overview Analysis](https://github.com/Oluchiumeh/Uber-Trip-Analysis/blob/main/Overview%20Analysis.png)

### Time Analysis
Unpacks booking trends based on time:

Daily and hourly trip volumes

Day vs Night travel behavior

Time-based impact on trip distances and values

![Time Analysis](https://github.com/Oluchiumeh/Uber-Trip-Analysis/blob/main/Time%20Analysis.png)

### Detail Analysis Table
A structured table visual to give users visibility into raw, yet filtered, data.

This dashboard is especially helpful for business teams that want to slice the data without touching raw files.

![Details](https://github.com/Oluchiumeh/Uber-Trip-Analysis/blob/main/Details.png)

## Key Insights Discovered
### Business Insight	Value
- Evenings have the highest bookings, especially in metro cities	
- UberPay is the most common payment method tho cash still used
- UberX are top vehicle type overall, followed by Uber Comfort	
- Most frequent pick-up and drop-off locations cluster around commercial zones	
- Average trip time spikes around evening rush hour	



