Uber Data Analysis
The Uber dataset contains 31 million rows of data from September 2014 to August
2015, including information about trip origin, destination, pickup and drop-off
dates/times, trip distance and duration. The data allows for estimating Uber's revenue
per trip in NYC.
Here, I did an EDA on the uber dataset, which consisted of data from rides booked in
NYC over the course of one year, from September 2014 to August 2015, and eventually
computed the income of Uber in one year as well as the revenue trend during the year.
I have used Pandas data frame to check for the presence of null values in the dataset. 
I utilized the mean and mode imputation approach to address missing values.
Also, feature engineering was used to construct several columns that can help with
analysis and expand the area of study. As a result, I made distinct columns for the year,
month, and day of the trip. These columns were then utilized to determine the data's
monthly trend. Also included a column for trip revenue, which was used to determine
total revenue and average revenue. The revenue consisted of various components like:
Base fare = 2.55
Per minute = 0.35
Per mile = 1.75
Minimum fare = 8
Findings:
-We found that the demand for Uber is higher from 4 PM until around midnight.
- We saw that the demand is gradually increasing from Monday to Saturday and Saturday
has the highest demand. Interestingly, Sunday shows a level of demand similar to
Wednesday, which is higher than Monday or Tuesday.
-When looking at the total demand per month along the period of time analyzed, seasonal
effects are masked by the consistent month-to-month growth.
●Sep Revenue = $29,967,741 Growth % = 0.0%
● Oct Revenue = $35,531,001 Growth % = 18.6%
● Nov Revenue = $38,170,687 Growth % = 7.4%
● Dec Revenue = $41,661,569 Growth % = 9.1%
● Jan Revenue = $41,457,151 Growth % = -0.5%
● Feb Revenue = $47,252,852 Growth % = 14.0%
● Mar Revenue = $52,154,385 Growth % = 10.4%
● Apr Revenue = $54,095,066 Growth % = 3.7%
● May Revenue = $61,539,912 Growth % = 13.8%
● Jun Revenue = $63,667,666 Growth % = 3.5%
● Jul Revenue = $63,607,348 Growth % = -0.1%
● Aug Revenue = $65,961,099 Growth % = 3.7%
Cumulative % Growth Over Period: 83.54793827524823
-We also found that the number of trips have also been effected because of various events like Thanksgiving, Christmas, Memorial Day, and Independence Day.
-We finally found that the total revenue of Uber in 1 year was 595 Million USD, growth in NYS as 84% and Gross Margin of 149 Million USD
