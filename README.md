# Machine Learning non-supervisé

## Project Description

### Using KMeans for Uber Trips

The objective of this project is to become familiar with the **KMeans** model in today's world.</br>
Imagine that you are **Uber** and want to give recommendations as to where the drivers should be to maximize their chances of finding a ride.

I used an unsupervised machine learning model to create this recommendation algorithm. **(Kmeans & DBSCAN)**</br>

Here is my work plan:
1. Data mining
2. Find the optimum number of clusters
3. Display these clusters on a map
4. Taking into account the periods of the day
5. Observation of the differences between KMeans and DBSCAN
</br>

Here an example of Uber activity in New-York, at lunch (12pm - 2pm):
<p align="center">
  <img src="https://raw.githubusercontent.com/ZoziLaMalice/Uber_Pickups/master/png_geopandas/New-York_at_lunch.png">
</p>

This cross-analysis is very instructive to understand Uber activity within the week in New-York:
<p align="center">
  <img src="https://raw.githubusercontent.com/ZoziLaMalice/Uber_Pickups/master/png_geopandas/cross-analysis.png">
</p>

And finally, an exemple of Wednesday clustering, plot using Bokeh : 
<p align="center">
  <img src="https://raw.githubusercontent.com/ZoziLaMalice/Uber_Pickups/master/png_geopandas/wednesday-cluster.png">
</p>
</br>

* Dataset: [uber-trip-data](https://github.com/fivethirtyeight/uber-tlc-foil-response/tree/master/uber-trip-data)
