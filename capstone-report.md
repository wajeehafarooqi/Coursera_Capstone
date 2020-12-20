<h1 align=center><font size = 7>Resturants in Haute-Savoie</font></h1>


<h1 align=center><font size = 4>Report presented by: Wajeeha Farooqi</font></h1>


# Introduction

Our study is on one of province of France,Haute-Savoie. haute-saoie is a region in the Alps of eastern France. There are many ski resorts in the Mont Blanc mountain range include popular Chamonix, with access to a large area of ski and snowboard runs. there are many resturants , and historical places . this area has very importance for its tourisim. One of best site for opening resturant here because of geolocation of this area.
The idea of this study is to help people planning to open a new restaurant in Haute-Savoie. In order to chose the right location by providing data about the income and population of each neighborhood as well as the competitors already present on the same regions. 


# Data Acquisition & Cleaning


To provide the stakeholders the necessary information I'll be combining Haute-savoie data that contains Population, Average income per Neighborhood with Haute-savoie's Neighborhoods shapefile and Foursquare API to collect competitors on the same neighborhoods. Haute-savoie population data is available in this site https://www.insee.fr/fr/statistiques/3689656#consulter Each commune or neighbourhood revenue(income) of Haute-savoie are avalilable on this site https://www.impots.gouv.fr/portail/statistiques The data is preprocessed by taking population column and code of all commune in Haute-savoie 2016. The income column is taking from impot.fr website . I merge these columns in one table and i used that table in my project. From geopy.geocoders i retrieve latitude and longitude of all commune amd append in my dataframe. 
we use package likes:
* pandas
* Numpy
* Json
* GEOpy
* Matplotlib
* Sklearn
* Folium
* Requests

![image.png](attachment:image.png)


### GEOLOCATION-Latitude-Longitude

![image.png](attachment:image.png)

# Methodology:


We create the data flow to get the data by using API, then extract the returants information. we take food category value from FourSquare app. extracting all information about resturants we use machine learning algorithm 'CLUSTER' to find where one can open resturant accoring to population and income of particular commune.

![image.png](attachment:image.png)

We use k-mean clustering. we explore the cluster information we can get the initial results
* French Resturant
* rest Resturant 
    like asian resturants are very popular in this region
    
    
   ![image.png](attachment:image.png)

The number of french resturants are more than 2500 in this region. Resturants shows the asian resturants which are more than 1000. It is very important information for the stake holder.


# Results
we find out the resturants in particular commune against their income. we explore each cluster againt the income of commune. if we check all index against the commune code we find all commune close too geneva border have high income.here we show you two cluster data.


![image.png](attachment:image.png)

![image.png](attachment:image.png)

# Findings:

Commune near the geneva border have high income salaries.Geo-location of all communes like annemasse ,meussey etc are the best location to open French , or asian food resturants


![image.png](attachment:image.png)



