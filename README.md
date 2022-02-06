# Mapping_Earthquakes

Visualizing Earthquake Data using GeoJSON data

### Overview of Project: Explain the purpose of this analysis.

We vreated earthquake map with two different maps and the earthquake overlay. Now,we would like to see the earthquake data in relation to the tectonic plates’ location on the earth, all the earthquakes with a magnitude greater than 4.5 on the map, and the data on a third map.

1. Add Tectonic Plate Data
2. Add Major Earthquake Data
3. Add an Additional Map

### Results:

We add tectonic plate data using d3.json(), add the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data. we can see the results in the following picture.

![This is an image](https://github.com/samiramghd/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/image/del1.PNG)

Then we add major earthquake data to the map using d3.json(), also add color and set the radius of the circle markers based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON(). we can see the results in the following picture.

![This is an image](https://github.com/samiramghd/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/image/del2.PNG)

Finally we add a third map style to your earthquake map. Using the options from the Mapbox styles , add a third map style as a tile layer object to the **challenge_logic.js** file and then add the map variable to the base layer object. we can see the results in the following picture.

![This is an image](https://github.com/samiramghd/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/image/del3.PNG)
