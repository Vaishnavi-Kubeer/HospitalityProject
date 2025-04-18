# 🏨 Hotel Booking Analysis Power BI Dashboard

## 📌 Overview
This project involves analyzing hotel booking data to uncover business insights and booking trends using Power BI. The analysis includes bookings made across various hotels and room types during the months of May, June, and July. The primary focus is to identify occupancy rates, booking behavior, customer satisfaction, and revenue generation.

## 🎯 Objective
The goal of this project is to:
- Analyze booking patterns across properties
- Understand room utilization and capacity
- Identify revenue trends and booking status distribution
- Segment data by city, hotel category, room class, and booking platforms

## 📊 Dataset Description
The project uses 5 CSV files:

- **dim_date.csv**: Contains dates, week numbers, and whether the day is a weekday or weekend.
- **dim_hotels.csv**: Includes hotel IDs, names, categories (Luxury/Business), and cities.
- **dim_rooms.csv**: Lists room types (RT1–RT4) and their classes (Standard to Presidential).
- **fact_aggregated_bookings.csv**: Shows daily room-wise bookings and available capacity for each hotel.
- **fact_bookings.csv**: Detailed booking info like dates, guests, room type, booking platform, status, ratings, and revenue.

## 📈 Power BI Dashboard Highlights
- **Booking Trends Over Time**: Visualize daily and weekly bookings
- **Hotel Performance**: Track booking vs. capacity per property
- **Revenue Insights**: Compare revenue generated and realized
- **Customer Ratings**: Analyze feedback across hotel classes
- **Booking Status Impact**: Evaluate effect of cancellations and no-shows

## ⚙️ Tools & Technologies
- Power BI
- CSV files (as data sources)
- Star schema data modeling
- DAX for calculated columns and KPIs

## 👩‍💻 How to Use
1. Clone the repository or download the `.pbix` file
2. Open the file in **Power BI Desktop**
3. Ensure all CSV files are in the correct folder or relink the data sources
4. Explore the dashboard and insights
