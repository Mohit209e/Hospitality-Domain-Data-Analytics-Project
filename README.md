# Hospitality Domain Data Analytics Project

## Overview
This project, a resume challenge by Codebasics, focuses on AtliQ Grands, an imaginary company owning multiple five-star hotels across India. The company is facing a loss in market share and revenue in the luxury/business hotel category due to ineffective management decision-making.

### Objectives
The primary tasks for this data analytics project were:
1. Creating metrics according to a provided list.
2. Developing a dashboard based on a mock-up provided by stakeholders.
3. Generating relevant insights beyond the provided metrics and mock-up.

### Hotel and Data Overview
- **Hotel Chain**: AtliQ Grands, operating in 4 cities.
- **Properties**: 7, with branches in all 4 cities.
- **Room Categories**: Elite, Premium, Presidential, Standard.
- **Booking Platforms**: 6 main platforms plus others.

### Data Sets Used
- **[dim_date](https://github.com/Mohit209e/Hospitality-Domain-Data-Analytics-Project/blob/742fbfebdeb416bab23b59a5ebef0f2971465b43/dim_date.csv)**: Dates, week numbers, day types.
- **[dim_hotels](https://github.com/Mohit209e/Hospitality-Domain-Data-Analytics-Project/blob/742fbfebdeb416bab23b59a5ebef0f2971465b43/dim_hotels.csv)**: Property ID, name, category, cities.
- **[dim_rooms](https://github.com/Mohit209e/Hospitality-Domain-Data-Analytics-Project/blob/742fbfebdeb416bab23b59a5ebef0f2971465b43/dim_rooms.csv)**: Room ID, room class.
- **[fact_aggregated_bookings](https://github.com/Mohit209e/Hospitality-Domain-Data-Analytics-Project/blob/742fbfebdeb416bab23b59a5ebef0f2971465b43/fact_aggregated_bookings.csv)**: Property ID, check-in date, room category, bookings, capacity.
- **[fact_bookings](https://github.com/Mohit209e/Hospitality-Domain-Data-Analytics-Project/blob/742fbfebdeb416bab23b59a5ebef0f2971465b43/fact_bookings.csv)**: Booking ID, property ID, dates, guests, room category, booking platform, ratings, status, revenue.
- **[Metrics List](https://github.com/Mohit209e/Hospitality-Domain-Data-Analytics-Project/blob/742fbfebdeb416bab23b59a5ebef0f2971465b43/metrics%20list.xlsx)**: Various key measures and DAX formulas.

## Dashboard and Report
A comprehensive report and dashboard was created using the provided data, focusing on financial statistics and hotel performance.

- **Live Power BI Dashboard**
 [View the Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNDU0YThmZWQtMjAzZS00ZDJkLWI5OTEtYmIyYmVhMWIzZmMyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
- **Report**
 [View Report here.](https://github.com/Mohit209e/Hospitality-Domain-Data-Analytics-Project/blob/6b635e4a055e93ee3698e6edb2f2ca93ae882bee/Hospitality%20Domain%20Data%20Analysis%20Project.docx)

### Key Financial Metrics
- Revenue, RevPAR (Revenue per available room), ADR (Average Daily Rate).

### Performance Metrics
- DSRN (Daily Sellable Room Nights), DBRN (Daily Booked Room Nights), DURN (Daily Utilized Room Nights), Cancellation %, Average Rating, Day Type, Booking Platforms, Week Number, Property Name and ID, WoW (Week on Week performance).

### Filters Used in Analysis
- Week Number, Month, Property, City, Room Class, Booking Platforms.

### Finance View
Focused on financial performance with similar filters, excluding performance metrics.

## Key Insights
- **Financial Performance by Hotels**: Varied revenue, RevPAR, and ADR among AtliQ Grands properties.
- **By Room Class**: Performance differences across room categories.
- **By City**: Revenue and rate comparisons among cities where AtliQ Grands operates.

## Acknowledgments
- Codebasics for the challenge opportunity.

## Thank You!
