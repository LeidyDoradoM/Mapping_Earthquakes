# Mapping Earthquakes

This week project is related with visualization of Earthquake data. We use `JavaScript` and `GeoJSON` data to create an interactive world map. `GeoJSON` data is the standard industrial format for geographical features and non-spatial attributes that is found in most of the applications that have mapping features like rides, delivering, location services, etc.

## Overview

In this module we have explored geographical features such as: **Points** -Latitude and Longitude coordinates, **Linestrings** -coordinates for the boundaries of streets, travel routes and tectonic plates and **Polygons** -coordinates for the boundaries of zip codes, counties, countries, etc. Also non-spatial features that is data without consideration of geographical information but that is packaged in a hierarchical structure of a `GeoJSON` file such as **Magnitude of Eartquakes**.  

## Results

In this project we use `JavaScript` as main programming language, and the `D3` and `Leaflet` libraries for retrieving `GeoJSON` earthquake and tectonic plate data provided by **U.S Geological Survey** website. This data is used to populate a world map base provided by `Mapbox API`.

### Tectonic Plate Data:

Below it is an overview of the world map base:
```js 
   Streets: mapbox/streets-v11
```
 with information about Eartquakes and Tectonic Plates displayed at the same time as over layers:

![tectonic](https://github.com/LeidyDoradoM/Mapping_Earthquakes/blob/Earthquake_Challenge/Earthquake_Challenge/Deliverable1.png?raw=true)

The website also allows the user to choose another map base: 
```js 
Satellite: mapbox/satellite-streets-v11
```
These options for map base and their over layers are shown in the upper right corner. This control legend also gives the user the ability to switch between the base layers and switch overlays on/off.

### Major Earthquake Data:

In this case, a new information about **Major Earthquakes** is displayed as overlay on the world map base layer. Below it is the base map layer with the available overlays to switch on/off:
 
![mQuake](https://github.com/LeidyDoradoM/Mapping_Earthquakes/blob/Earthquake_Challenge/Earthquake_Challenge/Deliverable2.png?raw=true)

### Additional Map:

Finally, an extra map base layer is added to the information already displayed in this app. The third base layer is:
```js
Dark: mapbox/dark-v10
```
The base layer is shown below:

![dark](https://github.com/LeidyDoradoM/Mapping_Earthquakes/blob/Earthquake_Challenge/Earthquake_Challenge/Deliverable3.png?raw=true)
