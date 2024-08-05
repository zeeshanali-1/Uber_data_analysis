Uber Data Analysis

The Uber dataset contains 31 million rows of data from September 2014 to August
2015, including information about trip origin, destination, pickup and drop-off
dates/times, trip distance and duration. 
The data allows for estimating Uber's revenue per trip in NYC.

Here, I did an EDA on the uber dataset, which consisted of data from rides booked in
NYC over the course of one year, from September 2014 to August 2015, and eventually
computed the income of Uber in one year as well as the revenue trend during the year.

I have used Pandas data frame to check for the presence of null values in the dataset. I utilized the mean and mode imputation approach to address missing values.
Also, feature engineering was used to construct several columns that can help with analysis and expand the area of study. As a result, I made distinct columns for the year,
month, and day of the trip. These columns were then utilized to determine the data's monthly trend. Also included a column for trip revenue, which was used to determine total revenue and average revenue. 

The revenue consisted of various components like:
Base fare = 2.55
Per minute = 0.35
Per mile = 1.75
Minimum fare = 8

Findings:

-We found that the demand for Uber is higher from 4 PM until around midnight.

-We saw that the demand is gradually increasing from Monday to Saturday and Saturday has the highest demand. Interestingly, Sunday shows a level of demand similar to Wednesday, which is higher than Monday or Tuesday.

-We also found that the number of trips have also been effected because of various events like Thanksgiving, Christmas, Memorial Day, and Independence Day.

-We finally found that the total revenue of Uber in 1 year was 595 Million USD, growth in NYS as 84% and Gross Margin of 149 Million USD
