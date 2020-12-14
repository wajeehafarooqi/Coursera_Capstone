# Coursera_Capstone
this is the assignment of Applied data science Capstone
'Capstone_project.ipynb' is the python file of first week assignment.
# Applied Data Science Capstone
## Peer Graded Assignment-- Capstone project--The battle of NeighbourHood
Now that you have been equipped with the skills and the tools to use location data to explore a geographical location, over the course of two weeks, you will have the opportunity to be as creative as you want and come up with an idea to leverage the Foursquare location data to explore or compare neighborhoods or cities of your choice or to come up with a problem that you can use the Foursquare location data to solve.
# 1)Introduction/Business Problem
The idea of this study is to help people planning to open a new restaurant in Haute-Savoie. it is the provience of France. This region has developed metropolitans. In order to chose the right location by providing data about the income and population of each neighborhood as well as the competitors already present on the same regions.
# Downloading and Preparing Data
To provide the stakeholders the necessary information I'll be combining Haute-savoie data that contains Population, Average income per Neighborhood with Haute-savoie's Neighborhoods shapefile and Foursquare API to collect competitors on the same neighborhoods.
Haute-savoie population data is available in this site      https://www.insee.fr/fr/statistiques/3689656#consulter
Each commune or neighbourhood revenue(income) of Haute-savoie are avalilable on this site https://www.impots.gouv.fr/portail/statistiques
The data is preprocessed by taking population column and code of all commune in Haute-savoie 2016. The income column is taking from impot.fr website . I merge these columns in one table and i used that table in my project. From geopy.geocoders i retrieve latitude and longitude of all commune amd append in my dataframe.
