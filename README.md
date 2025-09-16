# Airbnb-Data-Visualization
Performing EDA on Airbnb listings file and creating interactive dashboard using Power  BI


Project Overview:
This project focuses on analyzing Airbnb listing data from two major US cities - Chicago and New Orleans to gain meaningful insights into local market trends, host behaviour, pricing patterns and property distribution. Utilizing PowerBI, the project transforms raw listing data into interactive visual dashboard that helps explore and compare Airbnb across urban environments.

The goal is to conduct an Exploratory Data Analysis (EDA) and covert the insights into a well organized dashboard that provide stakeholders, hosts or  analysts with a clear understanding of how Airbnb performs in different neighbourhoods, how prices vary what property types dominates and how user experience relates to review and pricing.

The dataset comprises detailed attributes such as room type, neighbourhood, price, host information, availability and number of reviews etc. A combination of data cleaning, transformation using Python and visual story telling using PowerBI enables the creation of a dashboard categorized into four key areas:

1.Overview of Airbnb
2.Host Analysis
3.Pricing Analysis
4.Property Analysis

The  dashboard  supports  interactive  filtering by city, room type, and price category enabling a flexible and  user - centric experience. It serves as a decision  support tool to identify high performing neighbourhood, competitive  pricing strategies and impact of host experience on customer engagement.


Data Source : 

 The data is sourced from open Airbnb datasets and consists of individual CSV files for each  city:
chicago.csv
new_orleans.csv

These dataset contains information such as :
Listing ID, Property, room type etc.
Host  details and review metrics
Availability and pricing
Neighbourhood information


Why Airbnb?
Airbnb Inc (Airbnb) operates as a global online marketplace for lodging and tourism experiences. Its primary activities involve facilitating unique stays and experiences for guests, provided by hosts across the world. The company's major services include facilitating bookings for a wide variety of homes and experiences through its online platform. Airbnb serves a diverse customer base, enabling guests to explore authentic community experiences across various regions. Its's services are accessible through its website and mobile app, which serve as the primary distribution channels. The company operates in multiple geographic locations, including North America, EMEA, Latin America, and Asia Pacific. Airbnb is headquartered in San Francisco, California, the US.  It operates in over 191 countries, with 4  million listings and 150 million users. Its vaule is estimated  at $32 billion with a global growth rate of 153% since  2009.



Github Link :-  

Methodology:

1.Data Cleaning and Transformation :

Using Python(Pandas):



DAX calculated columns in Power BI: -

1.


2.

3.

4.

5.

Dasboard Visualization :-

Airbnb listings overview : Comparative analysis of Chicago and New Orleans

KPI Card :-
Metric displayed :  
Average Price -  It shows the average price across both the cities is $230.22, 
Total count of hosts : - It shows  the count of distinct hosting IDs i.e. approximately 16K
Total Estimated Revenue : - It provides a quick snapshot of sum of estimated revenue across both cities.
Total Listings : - It shows  the sum of total listings across both the cities.

Slicer  : -  
City : -  This interactive filter allow users to explore the data by selecting specific city,which enables focused  analysis.
Listing count by city : -  Pie Chart
The Donut chart provides a snapshot of the number of listings by city.
As per the chart Chicago dominates in terms of listings with over 53.35 % out of total listings.
Estimated Revnue by city : -  Bar Chart
Bar chart  displays the total revenue by each city and can be easily compared.
Insights : - As per the chart Chicago gives more revenue than New Orleans the stake holders can analyse the reason behind less revenue of New Orleans and work on the  areas of opportunity.

Availability by city : -  Map Chart
Map chart  displays the availability in each city  with  the help of latitude and longitude which makes it easy  to locate and identify the areas where the availability is maximum or the places where it needs to be increased.
Insights : - As per the chart Chicago dominates in terms of availability the stake holders can identify the locations where availability needs to be increased to increase the revenue.



Host Analysis : - 

KPI Card : -  Metric displayed.
Number  of Hosts -  It shows the total number of hosts listed across both the cities i.e. 3374, 
Total count of listings : - It shows  the count of distinct listing IDs by different hosts i.e. approximately 16K
Total number of reviews : - It provides a quick snapshot of sum of reviews received for  the  each host.

Slicer : - 
City : -  This interactive filter allow users to explore the data by selecting specific city,which enables focused  analysis.
Host  Category : - Host are divided into different categories as  per the  number of reviews received. This filter allows the stakeholders to deep dive to compare the  performance of hosts.
Price Category :-  Property are divided  into  different categories as per the price of each night. This helps  the  stakeholders to to explore the data by selecting and differentiating  the host type as per the price offered ,which enables focused  analysis.

Host count by Neighbourhood : -  Pie Chart
As per the chart ‘Central Business District’  (with 1330 hosts) has the highest number of  hosts followed by Near North Side (985 hosts)and West Town (765 hostss) etc. 
Insights :- The stakeholders can identify the neighbourhood where business  can be  maximized and they  can further deep dive using different slicers.

Estimated revenue by top  5 hosts : - Bar Chart
The bar chart  shows the clear comparison by top host who contributes maximum in terms of  revenue. As per the chart 
Insights : -  As per the chart ‘Blueground’ is the topmost  revenue earner (i.e. approx. $ 44M) followed by Cloud9 earning approximately $38 M.  However there are only 4 host that  earns more  than $20 M.

Number  of reviews received by top hosts : - Bar Chart
The bar chart  shows the clear comparison by top host who received maximum reviews. Number of reviews shows the engagement of host with the  guests. More engagement may  lead to increase in revenue if the reviews are positive and may harm if most of the  reviews are negative. 
Insights : -  As per the chart ‘Michael’ and ‘David’ are the top  hosts getting approximately  14K reviews followed by Daniel getting approximately 11K reviews.  However there are only 3 host who has received reviews more than 10K so other host also need to learn from these  top host so they can increase their engagement which in turn will build more trust resulting in better business.

Availability by hosts: - Bar Chart
The bar chart  shows the clear comparison by top host who provides maximum availability throughout the year. Higher the availability maximize the opportunity of getting more business. 
Insights : -  As per the chart ‘LuxurybookingsFZE’ is the top  host offering highest availability followed by ‘Level’  then ‘Cloud9’.  Most of the hosts  with higher availability are also the  top hosts in term of estimated revenue.




Price Analysis : -

Slicers : -  
City : -  This interactive filter allow users to explore the data by selecting specific city,which enables focused  analysis. 
Host  Category : - Host are divided into different categories as  per the  number of reviews received. This filter allows the stakeholders to deep dive to compare the  performance of hosts. 
Price Category :-  Property are divided  into  different categories as per the price of each night. This helps  the  stakeholders to to explore the data by selecting and differentiating  the host type as per the price offered ,which enables focused  analysis.





Listings with  Highest Price : - Table
The table shows the listing Id with highest price it also shows the neighbourhood, property type and the price for the particular listings.
Insights :- As per the table the highest price is $32,201 and the top ten listing are above $5000. All the listings with highest price are for Entire home/apt.  

Price Distribution : - Histogram Chart
The chart shows that  maximum number of listing are between the  price of  $200 to $400. There are very  few listings (less than 10) above $600 price bin.
Insights : -  As the  maximum number of listings are between $200 to $400 so it  shows that the customer prefer properties between $200 to $400 if the properties are increased in this price bin then the revenue  can be increased.

Listings by Price  Category : - Pie Chart
The chart shows that  maximum number of listing are in the ‘Moderate Price’ category i.e 8294 followed by ‘Low Price’ category.
Insights : -  As the  maximum number of listings are in the Moderate price category so it  shows that the customer prefer properties in ‘Moderate Price’ or ‘Low Price’ category if the properties are increased in this price category then the revenue  can be increased.

Engagement rate by Price : - Scatter Chart
The chart shows the relation between engagement rate and price.
Insights : -  The engagement rate is  highest for listings between the price of $50 to $200. 




Property Analysis : - 

Slicers : -
City : -  This interactive filter allow users to explore the data by selecting specific city,which enables focused  analysis.
Host  Category :-  This interactive filter allow users to explore the data by selecting the  Host category (i.e.  experienced, Moderat, or  New)

Ratings by Property Type - Donut Chart
Donut  chart  displaying the proportion of sum of number of reviews by each property type.
Common Categories : - 
Entire  Home/ Apt
Private Room
Shared Room
Hotel Room
Insights : -  It shows that the dominant room type is ‘Entire Home/apt’, which received the maximum reviews.
This helps the stakeholders understand the preferred room type and which of the different type receives maximum engagement and talked about.

Listings count by Property type : - Pie Chart
Pie chart displaying the proportion of listings count by property type.
Insights : - As per the chart ‘Entire Home/apt’ room type has  the maximum number of listing across cities.
This helps the stakeholders to understand the property type  which is dominating the listings so they can diversify the listings.

Number of host by property type and neighbourhood :-  Ribbon Chart
Ribbon chart  displaying the relation and comparison between number of host in top 10 neighbourhood and property type listed by them.
Insights : - As per the chart ‘Central Business District’ has the  maximum number of host listed followed by ‘Near  North Side’.
This chart can help us understand the  neighbourhood which contributes maximum in terms of listings and where they can focus to maximize their business.

Engagement rate by Price Category & Property Type :- Bar Chart
As per the chart that  comes under the moderate pricing has the highest engagement rate followed by highly priced rate however properties with  low pricing has the least engagement rate.
Insights :- This chart can understand the preference of the guest in the price category which type  of property can help them get maximum business.

