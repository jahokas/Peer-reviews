# Peer-graded Assignment Week 1: Capstone Project 
## The Battle of Neighborhoods in Lyon, France

### 1. Introduction - Business Problem Description

In this assignment, I prepare a market research for a nordic coffee shop chain that plans to establish new franchises in France, potentially in Lyon. The coffee shop chain runs also a cutlery online store.

I will prepare a detailed study that names districts and neighbourhoods where to locate coffee shops in Lyon. The Foursquare is an excellent location data and technology platform to study different options for locations.

**The business concept**

The coffee shops infuse nordic vegetarian cuisine and pastries with nordic design cutlery. The design table-ware is presented in coffee shops. Customers can purchase nordic tableware such as cups, mugs, jugs, serving dish, bowls and serving dishes in online store.

**The customer profile**

The most potential customers are in their 30-45 years, median income, single and married women who value relax social ambiance and something extra in service. Their coffee shop visits are often connected to another activity like shopping or training in sport centres. They are often willing to change their basic kitchen table-wares to design cutlery. They rely on friends’ recommendations.

**Requirements for preferable locations**

Based on practical experiences of the management in the nordic coffee shop chain, a new ranchise should be established in a community accessible to at least 36,000 people in order to be profitable. The city should have minimum yearly population growth rate 0.8%. The cities with universities and diplomats are the most preferable.

City centres and pedestrian streets have been found good places to establish a new coffee shop. The city centre should have several complimentary cafes and restaurants, multiple eating options. Customers often seek out to window shop and find what they’re craving in the moment. However, very high number of cafes and restaurants may lead to fierce competition and bad service level what drives away customers and depletes good coffee shop culture in the area.

### 2. Data

Here, I describe the data that I will be using to solve the business problem prented in the first chapter. The Foursquare location data and technology plays a major role in the assignemnt. In addition, I will provide statistical facts that help to assess if the location meet requirements of the business concept pertaining to demographical and market growth rate.

The below I list data sources, their data elements and links to the data sources.

**Population statistics and demographical data**
+ Historical data of the population
+ Population distribution by sexe
+ Population
+ births and deaths
+ Distribution of the population by age
+ Men population distribution by age
+ Women population distribution by age
+ Districts and their latitudes and longitudes

link 1: http://www.map-france.com/Lyon-69000/population-Lyon.html
link 2: https://worldpopulationreview.com/world-cities/lyon-population/

The National Institute of Statistics and Economic Studies
The National Institute of Statistics and Economic Studies collects, analyses and disseminates information on the French economy and society

link: https://www.insee.fr/fr/statistiques/2021173?geo=COM-69123

The Open Data Census
The Open Data Census of the municipalities of France assesses the openness of data in the main French cities. This collaborative project is coordinated by the Open Knowledge Foundation France.

link: http://fr-city.census.okfn.org/place/lyon

World Population Review

link: https://worldpopulationreview.com/world-cities/lyon-population/

**Location, exploration and analysis**

Foursquare
I will explore and cluster the neighborhoods in the city of Lyon. The work was separated in the following subchapters:
+ the map of Lyon
+ location of venues around neigbourhoods
+ Explorion and analysis of neighborhoods
+ Clustering the neighborhoods and examining the cluster

link: https://foursquare.com

### 3. References

**'How to Choose the Best Restaurant Location for Your Business'**
(https://fitsmallbusiness.com/choose-a-restaurant-location/)

**'How Restaurant Analytics Can Make Your Business More Profitable'**
(https://www.datapine.com/blog/benefit-from-your-data-with-restaurant-analytics)

**'Dining on Big Data: How Analytics is Reshaping the Restaurant Industry'**
(https://www.michiganstateuniversityonline.com/resources/business-analytics/dining-on-big-data/)

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
