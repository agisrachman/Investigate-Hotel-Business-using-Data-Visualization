# Background 
The development of tourist destinations has led to an increase in the number of hotel bookings. This should benefit the hotel business, but there are a number of bookings that have been canceled. So the purpose of this analysis is to find out the performance of the hotel business which is the first step to be able to predict the potential for bookings to be canceled.
# Objective
1. Analysis of Hotel Bookings Every Month.
2. Impact Of Stay Duration On Hotel Booking Cancellation Rate.
3. Analysis of Lead Time Distance on Hotel Booking Cancellation Rate.
# Exploratory
<b> Data Description </b><br>
This is open data (assumptions) not original data that occurred in Indonesia in 2017 - 2019. There are 2 types of hotels, namely city hotels and resort hotels spread across several cities in Indonesia. There are several facilities and criteria for customers who make reservations that will ultimately cancel the booking or not. 119,390 customers and 29 columns to be analyzed.<br>

<b> Data Preprocessing </b><br>
At this stage, in order to make the data easy to process, data type checking, data cleaning, troubleshooting (missing values, duplicates, etc.), and ensuring the suitability of the content in each column are carried out. <br>

1. To resolve missing values, delete rows or columns. If there are few empty rows in the column, delete the rows. But if there are many empty rows in the column then delete the column.<br>
2. All duplicates are deleted, leaving only the last data. Usually the last data is the most recent data, so the last data is very important to ensure the correctness and accuracy of the data. <br>
3. There are some contents in certain columns that have unknown values. The solution is to replace the word randomly, which means following the content in the previous row.<br>
4. In this analysis, outliers are ignored, because again the objective of this analysis, is simply to see the performance of the hotel business, not to predict hotel booking cancellations. <br>
5. The final result is 85,640 customers with 25 columns to be analyzed. This data will be stored and visualized either with python or other tools.<br>
