# Data-Charectarization

Exploratory data analysis of Airbnb listings in the major cities of California – San Francisco, Santa Cruz, Santa Clara, Oakland and Los Angeles

### Data Source:
http://insideairbnb.com/get-the-data.html 

The subject website provides Airbnb listings and reviews data for the major cities in the world.

### Overview of the data:
Data consists of the Airbnb listings from December 2019. I choose December 2019 to ensure to study the pre-covid behavior. 
Data consists of 16 columns which are:
1.	id – represents the id of the listing
2.	name – It is the name of the listing
3.	host_id – Host id is a unique Id associated to each host in Airbnb
4.	host_name – the host’s name
5.	neighbourhood_group – The city in which the listing is present
6.	neighbourhood – location of the listing
7.	latitude – latitude value of the listing
8.	longitude – longitude value of the listing
9.	room_type – Category of the type of listing like entire house, private room etc.
10.	price – cost per night
11.	minimum_nights – minimum number of nights that the listing should be booked for
12.	number_of_reviews – total reviews received by the listing
13.	last_review – Date when the property received its last review
14.	reviews_per_month – the ratio of reviews received, and the time property is listed
15.	calculated_host_listings_count – the count of listings a host has on Airbnb
16.	availability_365 – the number of days a listing is available in a year

Records count or the row count of the data is 61,540.
Size of the data: 28.7 MB

### Objectives of the project:

•	Explore and clean the data for any missing values and duplicate data.

•	Perform analysis on the price distribution in various major cities of California.

•	Check if the price has a relation with the minimum stays as well as property type along with location.

•	Perform geographical plotting of the price and location, and to see of if I can find any interesting aspects near the Silicon Valley and the tourist locations in LA.

•	 Analyze the behavior of hosts with multiple listings.

•	Understand the relation between reviews count and neighborhood.

•	Create appropriate visualizations and build a summary of findings from the data.

### Conclusions from the data analysis:

I used the various data cleaning, data summary and data visualization, geo spatial visualization techniques to analyze the AirBnB listings of the Los Angeles and San Francisco Bay region and found the following summary:

1] Noticed that Los Angeles has nearly 4.7 times the listings when compared to San Francisco.

2] Noticed that the price distribution is righ skewed with very few listings as costly as 25k per night.

3] The mean price of listings in LA is less by $40 when compared to the listings in San Francisco per night.

4] There are a lot of listings available for a minimum stay of 1, 2 as well as 30 days.

5] Also one can notice that, majority of the listings are of Entire home and Private room type.

6] Noticed that majority of lisitngs are concentrated near the downtown and tourist regions.

7] Most of the highly reviewed listings are present in Santa Cruz, Los Angeles and San Francisco.

8] Noticed that the most common words used in listing names are "private", "cozy", "beautiful", "home", "room", "spacious", "studio" etc.
