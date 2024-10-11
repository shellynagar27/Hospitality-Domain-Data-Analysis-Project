# Hospitality-Domain-Data-Analysis-Project
I built this project by following [Python: Beginner to Advanced For Data Professionals](https://codebasics.io/courses/python-beginner-to-advanced) by [CodeBasics](https://codebasics.io/)

## About the Company:
**AtliQ Grands** (Imaginary Company) is a hotel chain operating in Delhi, Mumbai, and Hyderabad with over 20 years in business. The company provides various platforms for hotel bookings, including the official AtliQ Grands website.

## Problem Statement & Background:
AtliQ Grands has been facing significant challenges from competitors, leading to revenue losses and decreased market share. To address these issues, the management decided to onboard a Data Analyst to provide data-driven insights for informed decision-making and help increase revenue. </br>
Imagine yourself as the Data Analyst working on this project and help company in analyzing data for better data driven insights using Python.

## Dataset:
The analysis is based on the following datasets:

- **dim_hotels**: `property_id`, `property_name`, `category`, `city`
- **dim_rooms**: `room_id`, `room_class`
- **dim_date**: `date`, `mmm yy`, `week_no`, `day_type`
- **fact_aggregated_bookings**: `property_id`, `check_in_date`, `room_category`, `successful_bookings`, `capacity`
- **fact_bookings**: `booking_id`, `property_id`, `booking_date`, `check_in_date`, `checkout_date`, `no_guests`, `room_category`, `booking_platform`, `ratings_given`, `booking_status`, `revenue_generated`, `revenue_realized`
- **new_data_august**: `property_id`, `property_name`, `category`, `city`, `room_category`, `room_class`, `check_in_date`, `mmm yy`, `week no`, `day_type`, `successful_bookings`, `capacity`, `occ%`

## Steps Taken:

1. **Exploratory Data Analysis (EDA):**
   - Identified the dataset shape (~100,000 records).
   - Analyzed the types of room categories provided by AtliQ Grands.
   - Reviewed booking platforms and hotel categories available.
   - Examined the number of hotels owned by AtliQ Grands.
   - Investigated bookings made per property and the share of successful bookings.
   - **Identified outliers.**

2. **Data Cleaning:**
   - Replaced outliers (e.g., negative values for the number of guests, very high booking fees) using mean, median, and standard deviation.
   - Identified and filtered null values.

3. **Data Visualization:**
   - Created various graphs to show:
     - **Contribution of each booking platform to total bookings.**
     - Number of hotels per city.
     - **Revenue realized per booking platform.**

4. **Data Transformation:**
   - Calculated **occupancy percentage (occ%)**.
   - Merged data frames.
   - Applied proper formatting to data.

5. **Ad Hoc Analysis:**
   - **Average occupancy rate** for each room category.
   - **Average occupancy rate** per city.
   - **Occupancy comparison between weekdays and weekends**.
   - Occupancy in June for different cities.
   - **Revenue realized per city, by hotel type, and by property**.
   - **Average rating** per city.

6. **Data Updates:**
   - Added new data sheets to the data frames as they were created.

## Key Learnings:
- **Data transformation, exploration, and cleaning** using the Pandas library.
- Gained insights into hospitality domain-specific terms such as **occ%**.
- Developed data visualization skills using **Matplotlib**.
