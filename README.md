
![](https://www.cynopsis.com/wp-content/uploads/2016/11/nyc-skyline.jpg)

# The Battle of the Neighborhoods



## Table of Contents
1. [Introduction/Business Problem](https://github.com/Raylo95/Capstone#1-introductionbusiness-problem)
   * [Description](https://github.com/Raylo95/Capstone#description)
    
2. [Data](https://github.com/Raylo95/Capstone#2-data)
    * [Foursquare Location Data](https://github.com/Raylo95/Capstone#foursquare-location-data)
    * [Crime Data](https://github.com/Raylo95/Capstone#crime-data)
    * [GIS Data](https://github.com/Raylo95/Capstone#gis-data)
    * [NYU Spatial Data Repository](https://github.com/Raylo95/Capstone/blob/master/README.md#nyu-spatial-data-repository)
    
3. [Methodology](https://github.com/Raylo95/Capstone/blob/master/README.md#3-methodology)
    * [EDA](https://github.com/Raylo95/Capstone/blob/master/README.md#eda)
     
    * [Machine Learning](https://github.com/Raylo95/Capstone/blob/master/README.md#machine-learning)
    
4.[Results](https://github.com/Raylo95/Capstone/blob/master/README.md#4-results)



  
     
    


---
<!-- toc -->

## 1. Introduction/Business Problem

  ### _Description:_

A restaurant owner wants to relocate their business to New York City and they want to know what would be the best area for them to relocate to. The first reason they want to move their business is they want a better opportunity to expand their business and not having to worry about having a lot of competition like the previous area. The second reason for relocating is due to the robberies and burglaries the restaurant was experiencing in the previous area. It's only natural they are worried about potential robberies and burglaries happening to the restaurant if they move to New York City. Which leads to the question that needs to be solved; and that is what borough and neighborhood would be best for the store owner to relocate?

---

## 2. Data

   ### _Foursquare Location Data:_
* Foursquare is a technology platform that has a massive location dataset
* Will be using the dataset to find the different venues in each neighborhoods
* Using the data to find the borough and neighborhood with the least amount of competition

 ### _Crime Data:_
 * The crime data was obtained from NYC Open Data which the data was provided by the New York City Police Department
 * The data size is 108,058 rows and 35 columns
 * Will be using the datset to find the borough and neighborhood safest for the restaurant owner
 * A link to the data set can be found [here](https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Current-Year-To-Date-/5uac-w243)
 ### _GIS Data:_
 * GIS data used to get the boundaries of each borough 
 * Used to create choropleth map for EDA
 * GIS data obtained from [here](https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm) 
 
 ### _NYU Spatial Data Repository:_
 * Used to get the longitude and latitude of the neighborhoods
 * The longitude and latitude of the neighborhoods will be used to get the venues
 * Can find the json file [here](https://geo.nyu.edu/catalog/nyu_2451_34572)

## 3. Methodology

  ### EDA
  * Neighborhood and Venue Distribution
  * Crime Distribution
  * Crime Rate
 
![](/Users/ramonlopez/Desktop/CAP/Cap Graphs/Crime Graphs/Type V Total.png)

    
  ### Machine Learning
  * DBSCAN Clustering 
    
  

## 4. Results
  * Results of the borough that is safest and has the least amount of competition can be found in the notebook **EDA Venues**
  * Results of the optimal neighborhoods can found in the notebook **Clustering Restaurant Crimes and Venues**

