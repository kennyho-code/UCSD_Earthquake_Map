# UCSD_Earthquake_Map

This project was designed by the University of California, San Diego Cousera Intermediate Programming Team.
This was from the Object-Oriented Java course. It was the first of a 5 course Java Programming: Object-Oriented Design of Data Structures Specialization.

The Program was built from:
Unfolding Maps
Processing
data from earthquake.usgs.gov


The project was separated into 5 modules:

Module 1: Display a map equal to the size and adjacent to the original map.


Module 3: Display markers for recent earthquakes by using data from earthquake.usgs.gov. The markers are color coded depending on the magnitude. 

module 4: Uses the abstract class EarthquakeMarker that is inherited by LandQuakeMarker and OceanQuakeMarker. The method draw() is used to call the drawEarthquake() methods present in LandQuakeMarker and OceanQuakeMarker which have different code to draw different size/shape/and color. CityMarker also added to label major cities on the globe. 

module 5: Primarily updates the program with using the eventhandlers mouseClicked() and mouseMoved(). If an EarthQuakeMarker is clicked, all the markers except the CityMarkers nearby are removed. If a city is clicked, all markers besides the closet EarthquakeMarkers are removed. CityMarker and EarthquakeMarker now extends from CommonMarker which contains the draw() method depending 

module 6: The comparableTo interface is used on the EarthquakeMarker which compares the "this" earthquake magnitude from all the other earthquakemagnitudes. The method sortAndPrint sorts the earthquakes by magnitudes in descending order.

Final: Made a custom GUI that shows the Top 5 Earthquakes sorted by Magnitude.  

