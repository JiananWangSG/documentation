# Geospatial Time Series

Several extractors push data to the Clowder Geostreams API, which allows registration of data streams that accumulate
datapoints over time. These streams can then be queried, visualized and downloaded to get time series of various 
measurements across plots and sensors.

TERRA-REF organizes data into three levels:

* Location (e.g. plot, or a stationary sensor)
    * Information stream (a particular instrument's data, or a subset of one instrument's data)
        * Datapoint (a single observation from the information stream at a particular point in time)



### Sensor destinations

Here, the various streams that are used in the pipeline and their contents are listed. The streams are presented as
(location group, stream name, datapoint contents).

* Full Field
    * Environmental Logger
        * {temperature, precipitation}
        
* AZMET Maricopa Weather Station 
    * Weather Station Observations
        * {temperature, precipitation}
    
* UIUC Energy Farm - Location 1
    * Energy Farm Observations
        * {}
        
* UIUC Energy Farm - Location 2
    * Energy Farm Observations
        * {}
        
* UIUC Energy Farm - Location 3
    * Energy Farm Observations
        * {}
        
* UIUC Energy Farm - Location 4
    * Energy Farm Observations
        * {}

* For each plot... (e.g. Range 31 Pass 5; each plot gets a separate stream)
    * SensorName - PlotName
        * {sensor location, FOV, bounding box}
    * canopycover - PlotName
        * {canopy cover height}
