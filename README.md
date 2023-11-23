# Tableau_Docs_by_me
Files containing Data Visualization files based on Tableau. These files includes the dashboards that I've created with a help of a datasets from Kaggle.

# Project 1: Dashboard 1 - Basic Outline Dashboard
Hi all,

It's been sometime since I started my journey into the field of Data Analytics. Everyday is like a learning for me. Every mistake which I make is like a new lesson. Okay, let's get straight to the point. I have started a working on a dashboard for a Sales Transaction Datasets which higlights the purchases done by various customers around the world.
I have created a dashboard with very basic details of the datasets, like No. of Order placed or cancelled in various countries, Numbers of customers in a specific country and Country wise orders.
Let me emphasize on the columns in this datasets. They are:
Transaction No., Date, Product No., Product Name, Price, Quantity, CustomerNo, Country and Status. Status was the only column which I added for easier usage.

The first chart in the Dashboard namely 'PC_Orders_Distinct' shows the numbers of orders placed or cancelled in all the countries or specifically any country(The filter which I added on the side is for this chart)

The second chart in the Dashboard namely 'HighestCustomers_Distinct' shows the number of customer present in each country with UK being the highest.

The third chart in the Dashboard namely 'Highest_No_of_Orders_Distinct' again shows the number of orders placed in each country specifically. 

Kindly check out this link for looking into the dashboard.
https://public.tableau.com/app/profile/anusuyaa.mohandass/viz/Dashboard_Sales_Basic_Outline/Sales_Transaction_Basic_Idea?publish=yes

# Project 2 : Dashboard 2: Sales Transaction of UK 2019
Hi all,

Excited to share my second dashboard in my portfolio. This dashboard is based on the dataset I had taken as I had mentioned it earlier is from the website named 'Kaggle' and the title of this dataset is 'Sales Transaction v.4a'. 

I have worked in this dashboard based on the country 'United Kingdom' alone as it was the country which had the highest number of customers and sales according to the dataset (mentioned in my previous project). As you see the media file placed under this project, there are 4 charts in this dashboard. Let me give you a brief on these charts.

Chart 1: Sales_2019_UK_Products_Purchased
Chart 2: Sales_during_each_quarter_2019
Chart 3: Sales_during_Q1&Q2_2019
Chart 4: Sales_during_Q3&Q4_2019

## Chart 1: Sales_2019_UK_Products_Purchased
This chart displays the sales for the entire of 2019 in United Kingdom.
The parameters used for x-axis and y-axis were Month/Year and SUM(Quantity) respectively. I've excluded the orders which were cancelled. This Area chart shows only orders which were placed successfully. I've filtered the date and Status. In the marks section of tableau, I've added color for status and detailing for Date and distinct product names.

## Chart 2: Sales_during_each_quarter_2019
This chart explains the sales in all the 4 quarters in UK. I've worked this chart pretty much in the same way that I processed the previous chart.   The parameters used for x-axis and y-axis were Month/Quarters and SUM(Quantity) respectively.

## Chart 3: Sales_during_Q1&Q2_2019
Chart 3 shows the sales done in the first 2 quarters. The parameters used for x-axis and y-axis were Month/Quarters and SUM(Quantity) respectively.

## Chart 4: Sales_during_Q3&Q4_2019
The sales of Q3 and Q4 was explained in Chart 4. The parameters used for x-axis and y-axis were Month/Quarters and SUM(Quantity) respectively.

The insights from these charts.
-> The sales gradually started in the month of January and saw a dip in the February month. Then a gradual progression started in the Q2 and Q3. It shot up to the peak in the month of November in Q4 and saw a number lesser than the January month. 
-> Reason for an increase in the month of November was most obviously because of the upcoming holiday season.  
-> In the mid-quarter, there is no massive sales seen in the charts because of the economic crisis probably. The year saw some lack of affordable housing in the country. Could have been a reason for lesser purchases.
-> Common factor in all the charts is sales at its peak before the holiday season.

I know there is much more to these charts, but I'll stop at these points. To all the people who view these dashboards, your suggestions are welcome. If you want to see the bigger picture of these dashboards kindly view this Tableau public website.

https://public.tableau.com/app/profile/anusuyaa.mohandass/viz/Sales_Transaction_2019_Raw_Version/Dashboard1?publish=yes

Stay tuned for more such dashboards in the learning journey of Data Analytics.
