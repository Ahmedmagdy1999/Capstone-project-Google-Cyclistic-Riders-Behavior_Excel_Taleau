# Cyclistic Bike-Share Analysis (April - June 2023)
## Project Overview:
In this project, I performed an in-depth analysis of the bike-share program data from Cyclistic, a bike-sharing service in Chicago. The goal was to understand the differences in usage between casual riders and annual members, with a focus on identifying opportunities to convert casual riders into annual members. The analysis involved cleaning and processing the data, as well as generating meaningful insights to support the marketing strategy.

## Key Business Question:
How do annual members and casual riders use Cyclistic bikes differently?

## Data Source:
The data used in this analysis was provided by Motivate International Inc. and is publicly available through Divvy Bike Share Data. I downloaded trip data for the months of April to June 2023, which represents the peak cycling season in Chicago. The dataset contains information about ride times, stations, trip length, bike type, and rider type.

## Steps Taken:
Data Collection: Downloaded 12 months of trip data (April to June 2023) from Divvy Bike Share Data.

### Data Cleaning:

Renamed files and ensured consistency in column headers.

Addressed missing values in station names by replacing them with "unknown."

Removed rows with zero values in ride duration.

### Data Transformation:

Split start and end times into separate columns for easier analysis.

Created a custom column for ride length and calculated the duration in minutes.

Created additional columns for the day of the week, hour of the trip, and month of the trip to identify peak times.

### Data Analysis:

Used Power Query to combine all the CSV files into a single Excel file.

Imported the cleaned data into Tableau for further visualization.

Created calculated fields for total rides and average ride duration.

Built a dynamic dashboard to visualize trip patterns, peak times, and other insights.

## Key Insights:

The peak hour for trips is 5 PM (17:00), and the least busy hour is 4 AM.

The peak month for rides is May, while June has the lowest number of trips.

The preferred bike type for both riders is the electric bike, while the docked bike has the least usage.

Annual members tend to make more trips during the 3-month period compared to casual riders.

Monday, Wednesday, and Friday are the most popular weekdays for riding, while Thursday, Saturday, and Sunday are less popular.

Total rides for both groups: 1,048,575.


![Peak usgae hour](https://github.com/user-attachments/assets/67ae853b-7e9f-4520-893d-e28ea04ebf18)


![Riders by weekday and user type](https://github.com/user-attachments/assets/f55ccb44-baee-4838-8aa1-fdb0c7690a68)
![Top 5 start station by users](https://github.com/user-attachments/assets/b92c6bbe-f5c1-44d4-bc03-a08383cd0635)
![FinalDashboard](https://github.com/user-attachments/assets/ed06cc53-23dd-4642-b96e-c4167239a8d7)


Average ride duration for both groups: 13 minutes, but casual riders tend to have longer ride durations than members.

## Recommendations:
Station Improvements: The "unknown" station issue suggests that there might be tracking or registration issues. It's crucial to improve the accuracy of data collection at these stations and ensure proper GPS tracking.

Targeted Marketing Campaigns: Based on the peak months and times, consider focusing marketing efforts during May and targeting casual riders who frequent the service at peak hours (5 PM). Highlight the convenience of annual memberships for frequent riders.

Bike Type Promotion: Since electric bikes are the most popular choice, Cyclistic could consider offering special promotions or discounts on electric bike rentals for new annual members.

Incentivize Off-Peak Riders: To balance usage, special offers could be introduced for casual riders during off-peak times, such as early mornings or late evenings.

##Tools Use 
Excel(power query)+ Tableau

### Dashboard link on Tableau public: https://public.tableau.com/views/CapstoneprojectGoogleCyclisticRidersBehavior/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

### My linkedin: https://linkedin.com/in/ahmed-magdy-yahia-0b456a1a6
### Mail: ahmedmagdy28.1999@gmail.com
### Github: https://github.com/Ahmedmagdy1999
