Earthquake Data Visualization - Jose Moncada Part#1

Project Overview
This project provides an interactive map to explore global earthquake data. The map visualizes recent earthquakes based on data from the USGS Earthquake GeoJSON Feed. Markers on the map are dynamically sized based on earthquake magnitude, and color-coded to represent depth. Users can click on the markers to view detailed information such as the earthquake's magnitude, depth, and location.

The goal of this project is to provide an interactive and informative tool for exploring global seismic activity.

Features
Interactive Map: Explore earthquake data on a global map, with zoom and pan controls.
Dynamic Markers: Marker size corresponds to earthquake magnitude, and color represents earthquake depth.
Popup Information: Displays detailed information about each earthquake, including:
Magnitude
Depth (km)
Location
Legend: Color-coded depth ranges, displayed on the map for easy reference.

Data Source
The earthquake data is fetched from the USGS GeoJSON feed:
USGS Earthquake Feed

Code Overview
Leaflet.js is used to create and manage the interactive map.
D3.js is used to fetch and parse the GeoJSON data from the USGS feed.
Markers on the map are sized based on earthquake magnitude and colored based on depth.
Popup Windows: Clicking on any marker will display information about the earthquake.
Legend: A legend showing depth ranges and corresponding colors is added to the map.
