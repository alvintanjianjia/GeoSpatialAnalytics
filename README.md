# GeoSpatialAnalytics

### Data Source
1. GeoFabrik
2. GADM

### Supporting Software
1. QGIS (Boundary Scoping [Not entirely necessary])
2. Tableau (Visualization [Swappable with PowerBI])

### 1. Mobility Analytics Methodology
Methodology is as listed below
1. 1 geohash -> 1 route-part -> 1 route -> 1 count
2. Make sure user is moving based on sequential points detected along sequential route nodes detected.
3. Make sure its on the desired road.
5. Timeseries analysis.
6. kepler.gl

### Route Usage Sample
1. Sample 1 with Geohash Labeling<br/>
![Route Usage Analysis based on POI](/sample_images/route_usage_poi.PNG)
2. Sample 2 Zoomed Out<br/>
![Route Usage Analysis based on POI](/sample_images/route_usage_poi2.PNG)

### Route Calculation Sample (Shortest vs Least Jam Paths)
1. Sample 1 
Red refers to shortest path. Purple refers to least jam path.<br/>
![Route Calculation based on POI](/sample_images/shortest_vs_least_jam.PNG)

1. Sample 2 
Red refers to shortest path. Purple refers to least jam path.<br/>
![Route Calculation based on POI](/sample_images/shortest_vs_least_jam2.PNG)