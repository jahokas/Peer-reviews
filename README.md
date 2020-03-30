# Peer-graded Assignment Week 2: Capstone Project 
# The Battle of Neighborhoods

## Table of content
1. Introduction - Business Problem Description
2. Data
3. Methotology
4. Results
5. Discussion
6. Conclusions
7. References

## 1. Introduction - Business Problem Description

In this article, I prepare a study for a Nordic coffeehouse chain that plans to establish new franchises in Lyon. Lyon is a vibrant city in Southern France with 0,8% yearly population growth rate.  The detailed study names districts that could be optimal places to establish new coffee shops in Lyon. The Foursquare is an excellent location data and technology platform to study different options for locations. Next I will describe a business concept, requirements and assumptions for profitable business. Only districts that meet these requirements can be selected for potential locations for coffeeshops.

**The business concepts**
The coffee shops infuse warm and cold drinks prepared from Nordic berries, vegetarian light cuisine such as pastries, sandwiches and light snacks served on Nordic design cutlery. The design tableware is presented in coffee shops. Customers can purchase Nordic tableware such as cups, mugs, jugs, serving dish, bowls and serving dishes in online store.

**Requirements and business assumptions**
It is very essential that franchise entrepreneurs can make profitable business preferable already during the first year. Consequently, the business concept owner helps to locate potential districts and give transparent metrics and assumption for profitable business. Here I describe three essential areas:

+ Sales assumptions
+ Location selection criteria
+ Customer profiles

Sales assumptions: 
The space for customer area is planned to be ca. 150m2 in coffeehouses. If each customer needs space of 3 m2, coffeehouses can serve same time 50 people. With 6 table rounds, the coffeehouse can serve 300 customers daily. In case 10% of local people find the coffeeshop daily to their place to visit, the district should have 3000 potential local customers. 
 
Transit hubs such as train and tram stations are expected to bring occasional customers. 
Traditional coffeehouse products are expected to bring sales of 1800 euros and tableware online sale 1200 euros daily. Consequently, the total daily revenue were 3000 euros daily. The coffeeshop should be profitable also outside tourist seasons.
 
Location selection criteria: 
Public transportation hubs and near pedestrian streets have been found good places to establish a new coffee shop. On pedestrian streets people often seek out to window shop and find what they’re craving in the moment. The location should have several complimentary cafes and restaurants, multiple eating options, but not a one that has the same business concept. 

Complimentary venues are other restaurants, cafés, steakhouses, breakfast venues, noodle shops, bistros, burger and taco restaurants. However, very high number of cafes and restaurants may lead to fierce competition and bad service level what drives away customers and depletes good coffee shop culture in the area. 

Customer profiles: 
The most potential customers are in their 30-45 years, median income, single and married women who value relax social ambiance and something extra in service. Their coffee shop visits are often connected to another activity like shopping or training in sport centres. They are often willing to change their basic kitchen table-wares to design cutlery. They rely on friends’ recommendations.

## 2. Data

Data is acquired to test if the district meets the following criteria:
+ Growth rate of residents is increasing
+ Number of female potential customers in the age of 30-45 years is substantial - 20% of all women residents
+ number of customers divided by the number of total numbers of complimentary restaurants is minimum 3000
+ Local venues build an optimal profile with transit hub and attractive complimentary services

The primary date source to test first two criteria is the website 'Map-of-France’. 'Map-of-France’ has data sets such as historical data of the population, population distribution by sex, births and deaths, distribution of the population by age and women population distribution by age. The World of Population Review data sets will be used as an additional data source to get new data and check demographical data from other data sources. In addition, the National Institute of Statistics and Economic Studies collects, analyses and disseminates information on the French economy and society.

The Foursquare location data and technology is used to test two last criteria. Foursquare provides excellent data that enables us to explore and cluster venues in districts of the city of Lyon.

In the Reference section I provide a full list of data sources, their data elements and links to the data sources. In addition, the section lists literature that is used to create business assumption presented in the previous chapter.

## 3. Methotology

The methodology section describes step by step how the analysis is conducted. 
 
First, we check if demographic data meets the criteria by comparing the assumption and statistical facts presented in selected data sources. 
 
Second, city of Lyon is divided in 22 districts and population data per district is collected. The districts are Lyon 1 - Place des Terreaux, Lyon 2 - Place Bellecour, Lyon 3 - La Part-Dieu, Lyon 4 - Croix-Rousse, Lyon 5 - Old Lyon, Lyon 6 - Parc de la Tete dOr’, Lyon 7 - Rhone, Lyon 8 - Cinema, Lyon 9 - Vaise, Tassin-la-Demi-Lune, La Mulatière, Villeurbanne, Caluire-et-Cuire, Sainte-Foy-lès-Lyon, Saint-Cyr-au-Mont-dOr, Écully’, Oullins, Saint-Fons, Vaulx-en-Velin, Bron, Meyzieu and Rillieux-la-Pape.
 
Third, all districts are located by using latitude and longitude values and a map is produced.
 
Forth, Foursquare service is used to retrieve data of venues within a radius of 500 meters in district centre. The data element ’Venue category’ is used to identify complimentary restaurants and their number of occurrences

Fifth, 10 the most common venue categories per a district is identified and sorted.

Sixth, K-Means method is used to cluster district in 8 categories. The categories are labelled to describe the characteristics of the district.

Finally, the results are presented in a table and a map with clustering labels is printed.

## 4. Results

Lyon has ca. 500 000 inhabitants and 53% of them are women. The population is growing steadily ca. 0,8% in a year. New people are born much faster than dying. In 2008 Lyon new babies were 7 339 births and less than half of births,  3 324 inhabitants died. Women in the age group of  30-45 years is approximately 20%. Younger women are also potential customers and the age group of 15-29 forms 29% of all women in Lyon.

There are 15 districts had less than 10 complimentary restaurants and services in Lyon. They were dropped from the list of potential locations for new coffeeshops.

Clustering analysis resulted in 8 districts. However, one of the clusters, cluster 1, includes 14 different districts out of 22 total amount of districts. The results implies that several districts resemble each other in terms of venue categories.

I studied through all venue categories cluster by cluster. Based on the study I created clusters names that describe categories best based on my subjective opinion.  Cluster names are presented below. 

Cluster 0   International restaurants and shops       1 districts

Cluster 1   French restaurants and shopping streets   14 districts

Cluster 2   Bankers, boutiques and restaurants        1 districts

Cluster 3   Grocery shops and small food shops        1 districts

Cluster 4   Hotels, fancy dining and jewelry          2 districts

Cluster 5   Playgrounds and young adults              1 districts

Cluster 6   Medical centre and pharmacy               1 districts

Cluster 7   Amphitheater and outside hanging          1 districts

Four districts had less than 3000 inhabitants per total number of complimentary venues. These were Lyon 1 - Place des Terreaux, Lyon 2 - Place Bellecour, Lyon 4 - Croix-Rousse, Lyon 5 - Old Lyon and Lyon 6 - Parc de la Tete dOr’. Especially, the tourist location Lyon 1 and Lyon 2 have extreme fierce competition. Lyon 1 - Place Bellecour district have only 564 restaurants per an inhabitant.

Finally, only two districts turned out to be viable to establish restaurants in Lyon. Lyon 3 - La Part-Dieu that resides near railway station and big shopping center and Lyon 7 - Rhone that is located near southern tram and railway connection.

## 5. Discussion


## 6. Conclusions



## 7. References

Literature
* 'How to Choose the Best Restaurant Location for Your Business' (https://fitsmallbusiness.com/choose-a-restaurant-location/)
* 'How Restaurant Analytics Can Make Your Business More Profitable' (https://www.datapine.com/blog/benefit-from-your-data-with-restaurant-analytics)
* 'Dining on Big Data: How Analytics is Reshaping the Restaurant Industry'(https://www.michiganstateuniversityonline.com/resources/business-analytics/dining-on-big-data/)

Full data source list
* Map-of-France (link: http://www.map-france.com/Lyon-69000/population-Lyon.html)
* World of population Review (link: https://worldpopulationreview.com/world-cities/lyon-population/)
* The National Institute of Statistics and Economic Studies (link: https://www.insee.fr/fr/statistiques/2021173?geo=COM-69123)
* The Open Data Census (link: http://fr-city.census.okfn.org/place/lyon)
* Foursquare (link: https://foursquare.com)

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
