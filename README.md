# Bike-Share Analysis (R)

Google Data Analytics capstone. Business question: **how do annual members and casual riders use the bike-share service differently?**

## Data
Divvy trip data, Q1 2019 and Q1 2020 (public dataset).

## Tools
R: dplyr, lubridate, ggplot2

## Process
1. Renamed the 2019 columns to match the 2020 schema and fixed data types
2. Combined both quarters into one dataset
3. Dropped unused columns and recoded user types (Subscriber → member, Customer → casual)
4. Added date, month, day and weekday fields and calculated ride length in minutes
5. Removed test rides (HQ QR station) and negative ride lengths
6. Compared ride counts and average ride length by user type and weekday

## Key Findings
- [e.g. Casual riders take longer rides on average: X min vs Y min for members]
- [e.g. Members ride most on weekdays; casual riders peak on weekends]
- [Your recommendation, e.g. a weekend membership offer to convert casual riders]

## Charts
![Rides by weekday](rides_by_weekday.png)
![Average duration by weekday](avg_duration_by_weekday.png)
