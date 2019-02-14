# FordGoBike
### Analyzing Share Bikes
### Introduction
 Ford GoBike is a regional public bicycle sharing system in the San Francisco Bay Area, California. Beginning operation in August 29th 2013 as Bay Area Bike Share, the Ford GoBike system currently has over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. From it's early development, many other cities began adopting this system.
 This is the link for the dataset https://s3.amazonaws.com/fordgobike-data/index.html. This data set includes information about individual rides made in a bike-sharing system covering the San Francisco Bay area.
Our goal as a data analyst, is to increase it's rideship and to offer deals through the mobile app. What deals can be offered? Currently, it has three options: a flat price for a single one-way trip, a day pass that allows unlimited 30-minute rides for 24 hours and an annual membership. In addition to using bicycles, Ford has introduced electric bikes called Ford GoBike Plus (ebike) https://www.fordgobike.com/how-it-works/meet-the-bike.
Some of the questions that would be good to answer are:
1. When are most trips taken in terms of time of day, day of the week, or month of the year?
2. How long does the average trip take?
3. Does the above depend on if a user is a subscriber or customer?

The Data Structure are as follows:
Each trip is anonymized and includes:

 * Trip Duration (seconds)
 * Start Time and Date
 * End Time and Date
 * Start Station ID
 * Start Station Name
 * Start Station Latitude
 * Start Station Longitude
 * End Station ID
 * End Station Name
 * End Station Latitude
 * End Station Longitude
 * Bike ID
 * User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
 * Member Year of Birth
 * Member Gender

This project is divided into 2. The first part in FordGoBikePart1.ipynb which deals with data from july 2017 through Jan 2018 
and the second part is FordGoBikePart2.ipynb which deals with data from the year 2018.
