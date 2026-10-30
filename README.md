# hotel-booking-performance-analysis
An Excel-based hotel booking analytics project exploring revenue trends, hotel performance, customer segments, guest data and cancellation-related revenue loss through interactive dashboards and visualisations.
## Hotel Booking Performance Analysis Dashboard

An Excel-based hotel booking analytics project designed to explore reservation activity, revenue performance, guest segments, hotel-type performance, and cancellation-related revenue loss.


Hotel Performance Dashboard


## Project Overview

This project uses a hotel booking dataset to build an interactive performance dashboard for comparing City and Resort hotels. The workbook combines booking-level records, summary tables, KPI cards, charts, and date filters to support operational and revenue-focused analysis.


The dashboard is intended to help hotel managers and business analysts identify revenue patterns, understand customer segments, monitor cancellation exposure, and spot areas that may need commercial attention.


## Business Questions


How does hotel revenue change across the months?

Which property type contributes more revenue: City Hotel or Resort Hotel?

Which customer types contribute the most revenue?

How do booking and cancellation patterns differ by hotel type?

Which guest markets and customer segments could be prioritised?

What opportunities exist to improve off-peak demand and reduce revenue loss?


## Dataset

The workbook contains 119,390 booking records and fields including:


Field	Description
Booking ID	Unique booking identifier
Hotel	Property type (City or Resort)
Booking Date	Date the reservation was made
Arrival Date	Guest arrival date
Lead Time	Days between booking and arrival
Nights	Length of stay
Guests	Number of guests associated with the booking
Distribution Channel	Channel through which the booking was made
Customer Type	Customer segment
Country	Guest's country
Deposit Type	Deposit arrangement
Avg Daily Rate	Average daily rate
Status	Booking outcome/status
Status Update	Date of the latest status update
Cancelled (0/1)	Cancellation indicator
Revenue	Revenue value used in the analysis
Revenue Loss	Revenue loss value used in the analysis
Cancel Status	Cancellation category

The workbook includes multiple tabs containing booking data. Review the DATABASE, Data, and Sheet6 tabs before publishing to confirm which is the intended source/working table and whether all three are necessary.


## Workbook Structure

Worksheet	Purpose
DASHBOARD	Main visual dashboard with date filters, KPI cards, charts, key insights, and recommendations
KPI	Summary KPI values
PIVOT TABLE	Aggregations supporting the charts and analysis
DATABASE	Booking-level dataset
Data	Booking-level data table
Sheet6	Booking-level data table with calculated/analysis fields
READ ME	Workbook notes and external profile links

## Dashboard Features


Booking Date and Arrival Date filters

Revenue and revenue-loss KPI cards

Guest-volume summary

City vs. Resort revenue comparison

Monthly revenue trend

Customer-type revenue analysis

Country-level booking/revenue visual

Booking status and cancellation comparison

Recommendations for improving hotel performance


## Selected Findings

The existing pivot summaries report the following:



Total revenue: approximately 29.60 million in the workbook's displayed currency.

Revenue loss: approximately 13.12 million (stored/displayed as a negative value).

Guests: 234,988.

City Hotel revenue: approximately 17.56 million.

Resort Hotel revenue: approximately 12.04 million.

Transient customer revenue: approximately 22.70 million, the largest customer-type contribution in the pivot summary.

Monthly revenue: January is the highest month in the monthly revenue pivot (approximately 4.29 million); June is the lowest (approximately 1.91 million).


These are workbook outputs, not independently audited financial results. The currency and the precise revenue calculation should be documented before the figures are used outside this portfolio project.


Data Quality and Metric Notes

A few metric definitions should be corrected or validated before treating every dashboard visual as decision-grade:



The KPI currently labelled Total Booking ID displays 7,127,045,745, which is the sum of booking identifiers, not the number of bookings. The data contains 119,390 booking rows. Use Count of Booking ID (or distinct count where appropriate) for a bookings KPI.

The cancellation comparison pivot currently aggregates Sum of Booking ID. Change this to Count of Booking ID to compare cancelled and non-cancelled bookings accurately.

The country visual is titled as a revenue ranking, but its supporting pivot currently uses Sum of Booking ID. To show revenue by country, aggregate Sum of Revenue; to show booking volume by country, use Count of Booking ID and change the chart title accordingly.

Confirm the currency represented by Revenue, Revenue Loss, and Avg Daily Rate. The dashboard uses a currency symbol, but the workbook should explicitly identify the currency and calculation method.

The READ ME worksheet contains LinkedIn and X profile links. Confirm that these links belong to the project owner or remove/replace them before making the workbook public.


These checks are included to make the analysis transparent and to distinguish current workbook outputs from metrics that still need validation.


## Tools and Skills Demonstrated


Microsoft Excel

Data inspection and preparation

PivotTables and summary analysis

## KPI design

Interactive date filtering/slicers

Charts and dashboard design

Revenue trend analysis

Customer and hotel-segment analysis

Business insight communication


## Recommendations Highlighted in the Dashboard


Encourage bookings during off-peak periods.

Build on the revenue contribution of City Hotel bookings.

Target valuable guest markets after validating country-level metrics.

Investigate cancellation drivers and reduce avoidable cancellations.

Develop offers for the high-contribution Transient customer segment.



## How to Review the Project


Open the Excel workbook in Microsoft Excel.

Navigate to the DASHBOARD worksheet.

Use the Booking Date and Arrival Date filters to explore the dashboard.

Review the PIVOT TABLE and KPI worksheets to understand the supporting calculations.

Check the data-quality notes above before relying on booking-count, cancellation, or country-level conclusions.


## Data Attribution and Usage

The original dataset source and its redistribution terms are not identified in the workbook. Add the original dataset name, source URL, and attribution here before publishing the data publicly. Do not redistribute the underlying records unless the dataset licence or source terms permit it.


## Project Purpose

This project is part of a data analytics portfolio and demonstrates how spreadsheet-based analysis can turn hotel booking records into business-focused summaries and visual insights.

