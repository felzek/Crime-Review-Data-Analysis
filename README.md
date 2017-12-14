# Deep Data Dive of Crime in Austin

Our goal was to take an in-depth analysis into the crimes occurring in Austin, Texas. In addition to the overall crime spread of our city, we wanted to discover correlations between the Travis County zip codes and the demographics behind the crimes. 

#### But... why?

Because even though Austin is a pretty cool place, there are dusty corners and dark alleyways that we wanted to explore. For data!

### The Data

<html>
<body> 
  <p>
  <img width="65%" height="auto" align="right" alt="crime_data" src="https://user-images.githubusercontent.com/30611037/34005445-82a3e2a8-e0c0-11e7-84b3-dc62dfdc3b29.png"> We utilized the jupyter notebook and Python 3.6 to create our DataFrames and coerce our data to tell us a story.<br><br> After creating and cleaning the data, other questions we discovered we wanted answers to include: 
  <ul>
    <li>Are certain zip codes associated with certain crimes?</li>
    <li>Do affordable housing locations have a relationship with crime?</li> 
    <li>What about businesses - will the quality of their reviews be reflected in their location?</li></ul>
We also performed sentiment analysis using VADER sentiment analysis on the reviews for local businesses in the area, in hopes to find correlation between review polarity and location.  
  </p>
  </body>
  </html>
  
### The Code
examples of code here
  
### Tests
Stats/graphs pictures, info here

### Data Relationships

<html>
<body>
  <p>
    <img align="left" width="30%" alt="austin_burglary" src="https://user-images.githubusercontent.com/30611037/34004005-65bba742-e0bc-11e7-982b-8a9c49271232.png">After the research and data crunching, we discovered that there are a few relationships of note:
<ul>
  <li>Most crimes are committed in the South/Central Austin area</li>
  <li>There is no correlation, at all, between Yelp reviews and the crime data</li>
  <li>Areas with higher crime also have a higher number of affordable housing projects</li>
</ul>
  </p>
  </body>
  </html>
  
### Insights
One interesting trend we noticed during our exploration involves the sentiment analysis of the business reviews. Even if the compound sentiment polarity is negative, the overall rating for the business will not necessarily be low. Overall, Yelp reviews in Austin are overwhelmingly positive.   

### Challenges
Every project comes with its own set of challenges. Time (or lack of) is a fairly universal one. We also encountered limits with the data, such as the Yelp API only allowing three reviews per business.

Originally, we had planned to include more in-depth information about housing prices, family size, and median income, but we ran into complications involving the Zillow API and in aquiring additional market datasets.

The overall quality of the Yelp reviews was also called into question, as well as the Yelp business practices. We won't get into it here, but we do feel there is bias and a great deal of limitation using this interface. 
 
### Additional Questions
We feel that, given ample time, there are far more questions that can be answered and data to be explored. What are the schools like in these areas? We now know a bit about gender and racial demographics involving crime, but how are the demographics spread throughout the city? We have all of this crime data from 2014-2016, can we predict a trend for 2017 and 2018? 
  
#### Prerequisites
*include info here

#### Raw Data Sources
Public annual crime records (2014 - 2016), crime demographics, and affordable housing information were all obtained from <a href="https://data.austintexas.gov/">data.austintexas.gov</a>. 

Local business information and reviews obtained from the <a href="https://www.yelp.com/fusion">Yelp API</a>.




