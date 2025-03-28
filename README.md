# Facility Booking Management Dashboard

## Project Overview

This project involves analyzing facility booking data to provide actionable insights through an interactive dashboard. The dashboard highlights booking trends, peak time slots, revenue analysis, and instructor demand to help optimize operations.

## Objective

The goal of this project was to assess booking data quality, clean inconsistencies, and extract meaningful insights. The dataset includes booking details such as Service Name, Facility, Booking Type, Price, Duration, and Instructor Allocation.

## Deliverables

- 📊 **Interactive Dashboard**: A Power BI dashboard showcasing key insights.
- 📝 **Written Report**: A detailed explanation of the approach, methodology, and key observations.
- ❗ **Data Discrepancy Report**: Documentation of inconsistencies or inaccuracies found in the dataset.
- 📂 **Final Dataset**: The cleaned and processed dataset used for analysis.
- 🎥 **Video Walkthrough**: A short recorded explanation of the dashboard and insights.
- 🖥️ **Code Files**: SQL and Python scripts used for data processing and analysis.

## Data Sources

The dataset contains information related to:

- 🏢 Service Name, Facility, Class Type, and Booking Type
- 📌 Booking Status (Pending/Confirmed)
- ⏳ Time Slots and Booking Trends
- 💰 Revenue and Instructor Demand

## Data Cleaning & Exploration

- The dataset was loaded using Pandas and explored using `df.info()`, `df.describe()`, and `df.nunique()`.
- Missing values were handled based on logical relationships:
  - 🏢 *Facility & Class Type*: One was missing when the other was present.
  - 👨‍🏫 *Instructor*: Filled as "No Need" for non-class bookings and "Unknown" for missing values in class bookings.
  - 🕒 *Time Slot*: Missing values replaced with "Not Specified."
  - 📏 *Duration & Price*: Missing values replaced with the median to avoid skewing analysis.
- Duplicate and redundant columns were reviewed but retained where necessary to avoid loss of critical data distinctions.

## Key Insights

1. ⏰ **Peak Booking Hours**: Most bookings occur between 14:00 and 15:00.
2. 📅 **Day-wise Trends**: Saturdays and Mondays have the highest number of bookings.
3. 💵 **Revenue Breakdown**: Facility, Class, and Birthday Party bookings contribute almost equally to total revenue.
4. 📝 **Pending vs Confirmed Status**: 49% of bookings are still pending confirmation.
5. ⚠️ **Data Discrepancies**: Columns like Service Name, Facility, Class Type, and Booking Type contain similar data, but they cannot be removed as they might represent different booking statuses.

## Tools & Technologies Used

- 📊 **Power BI**: Data visualization and dashboard creation.
- 🐍 **Python**: Data cleaning and preprocessing.
- 🗄️ **SQL**: Data extraction and transformation.

## How to Access the Dashboard

The Power BI file is included in the submission. Open it in Power BI to interact with the visualizations.

## Insights Preview

![Dashboard Insights](https://github.com/Shubham9975/Facility_Bookings_Data_Analysis/blob/main/Booking%20Management%20Dashboard.gif?raw=true)


## Contact

For any queries, feel free to reach out to me at **[rampurkarshubham91@gmail.com](mailto:rampurkarshubham91@gmail.com)**.

---

**Author**: Shubham Rampurkar  
**Date**: March 2025  

