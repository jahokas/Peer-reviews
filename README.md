# Peer-graded Assignment Week 1: Capstone Project 
## The Battle of Neighborhoods

### 1. Introduction - Business Problem Description

In this assignment, I prepare a market research for a nordic coffee shop chain that plans to establish new francises in France, potentially in Lyon. 

The chain runs also a cutlery online store. The design is presented in coffee shops. Customers can purchace nordic tableware such as cups, mugs, jugs, serving dish, bowls and serving dishes.

I prepare a detailed study that describe in which districts and neigborhoods the chain should locate their coffee shops in Lyon.

**concept**
+ nordic style table-ware and pastries
+ sell cups and tellers, mugs, jugs, serving dish, bowls, serving dishes, plates
+ vegetarian food prepared from local raw materials
+ nordic design online store

**customer profile**
+ _often connected to another activity like shopping_
+ _Bar & Bistro: 25-45 age range, high disposable income, often takes place after work, often spontaneous, most customers drink alcohol, relaxed social ambiance is important, price point depends on the neighborhood._
+ women and their female friends, frequent fine dining establishments usually plan ahead, book reservations in advance, and want a high level of service. So forthsquare is an excellent place to study different options for locations.
+ Early 40s, married, well-educated, upper-middle class, plans ahead, relies on friends’ recommendations, median income of $80k annually, married, two children, family-oriented

Clearly the Foursquare location data is an excellent platform to solve or execute.

**Locations**
+ clear quata foreigners, maybe expats or diplomats
+ clearly positive birthrate, 30-45 years old female consumers, yearly population growth rate % minimum 0.8%
+ A rule of thumb is that your restaurant should be located in a community accessible to at least 50,000 people, as noted by NerdWallet.

_A description of the problem and a discussion of the background_

_Clearly define a problem or an idea of your choice, where you would need to leverage the Foursquare location data to solve or execute. Remember that data science problems always target an audience and are meant to help a group of stakeholders solve a problem, so make sure that you explicitly describe your audience and why they would care about your problem._


***How to Choose the Best Restaurant Location for Your Business**

https://fitsmallbusiness.com/choose-a-restaurant-location/

***How Restaurant Analytics Can Make Your Business More Profitable**

https://www.datapine.com/blog/benefit-from-your-data-with-restaurant-analytics

***Dining on Big Data: How Analytics is Reshaping the Restaurant Industry**

https://www.michiganstateuniversityonline.com/resources/business-analytics/dining-on-big-data/

### 2. Data

_A description of the data and how it will be used to solve the problem_

_Describe the data that you will be using to solve the problem or execute your idea. Remember that you will need to use the Foursquare location data to solve the problem or execute your idea. You can absolutely use other datasets in combination with the Foursquare location data. So make sure that you provide adequate explanation and discussion, with examples, of the data that you will be using, even if it is only Foursquare location data._

_This submission will eventually become your Data section in your final report. So I recommend that you push the report (having your Data section) to your Github repository and submit a link to it._

I have explored, segmented, and clustered the neighborhoods in the city of Lyon. Feel free to explore the notebook by adding your Fourtsquare credentials you can perform the same analysis (CLIENT_ID and CLIENT_SECRET).

You can found the analysis also in html-form in the repository.

### Statistics

**The National Institute of Statistics and Economic Studies**
The National Institute of Statistics and Economic Studies collects, analyses and disseminates information on the French economy and society
https://www.insee.fr/fr/statistiques/2021173?geo=COM-69123

**The Open Data Census**
The Open Data Census of the municipalities of France assesses the openness of data in the main French cities. This collaborative project is coordinated by the Open Knowledge Foundation France.
http://fr-city.census.okfn.org/place/lyon

**Lyon population statistics**
+ Historical data of the population of Lyon from 1968 to 2007
+ Population distribution of Lyon by sexe
+ Population of Lyon from 1968 to 2007
+ Lyon : births and deaths from 1999 to 2008
+ Distribution of the population of Lyon by age in 2007
+ Men population distribution of Lyon by age in 2007
+ Women population distribution of Lyon by age in 2007
+ Districts and their latitudes and longitudes

http://www.map-france.com/Lyon-69000/population-Lyon.html

**World Population Review - Lyon**

https://worldpopulationreview.com/world-cities/lyon-population/

**Foursquare**

I replicated the analysis similar to the New York City dataset. I explored and clustered the neighborhoods in the city of Lyon. The work was separated in the following subchapters:
+ Restricting the analysis into neighborhoods with name 'Lyon'
+ Presenting the map of Lyon
+ The Foursquare part - locate venues around neigbourhoods
+ Explore neighborhoods in Lyon
+ Analyzing each neighborhood by neighborhood
+ Clustering the neighborhoods
+ Examining clusters and giving them names

------

## Previous submitted and accepted peer-graded assignments

### Peer-graded Assignment: Segmenting and Clustering Neighborhoods in Toronto

In this assignment, I have explored, segmented, and clustered the neighborhoods in the city of Toronto. Feel free to explore the notebook by adding your Fourtsquare credentials you can perform the same analysis (CLIENT_ID and CLIENT_SECRET).

You can found the analysis also in html-form in the repository.

**Task 1: Creating the preliminary dataframe and printing the number of rows**

I wrangled the Toronto neighborhood data, cleaned it, read it into a pandas dataframe, and finally presented it in a structured form like the New York dataset.

The link to the source data can be found here: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M).

The dataframe is presented in the end of the chapter 1.

**Task 2: Adding latitudes and longitudes of neighbourhoods in the dataframe**

In order to utilize the Foursquare location data, I added the latitude and the longitude coordinates of each neighborhood.
The new dataframe is presented in the end of the chapter 2.

**Task 3: The replication of the analysis with Toronto data set**

I replicated the analysis similar to the New York City dataset. I explored and clustered the neighborhoods in the city of Toronto. The work was separated in the following subchapters:

+ Restricting the analysis into neighbourhoods with name 'Toronto'
+ Presenting the map of Toronto
+ The Foursquare part - locate venues around neigbourhoods
+ Explore neighborhoods in Toronto
+ Analyzing each neighborhood by neighborhood
+ Clustering the neighborhoods
+ Examining clusters and giving them names

I formed 6 clusters and gave them names describing the areas:
- Cluster 1 - Coffee Shops and Delicates (Red label)
- Cluster 2 - Bermunada Triangle (Purple label)
- Cluster 3 - Locks and Latches (Petrol Blue label)
- Cluster 4 - Boutiques (Darker Green label)
- Cluster 5 - Parks (Light Green label)
- Cluster 6 - Health and Beauty (Orange label)

The colour label is presented in the map. The clusters you can find in the end of the document.

**Table of contents**
1. Creating the preliminary dataframe and printing the number of row
2. Adding latitudes and longitudes of neighbourhoods in the dataframe
3. The replication of the analysis with Toronto data set
