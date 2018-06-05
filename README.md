# Moldova Mapping Projects
This repository tracks the various mapping projects throughout Moldova that are managed by [Kaart](https://github.com/KaartGroup/Moldova/blob/master/KAART.md "Kaart").

## Projects

### [Road Network Improvement Project](https://github.com/KaartGroup/Moldova/projects/1 "Project 1")
Using algorithmic estimations and user feedback we have created the following outline to improve the map data of Turke y.

We will sift through the data to identify areas where missing roads don’t exist. (See sources below)

Some areas where we intend to improve and enhance the data are as follows:

 - Resolving open notes where possible
 - Fixing any connectivity issue with roads
 - Adding missing road geometry
 - Fixing alignment issues
 - Checking road hierarchy based on OSM guidelines
 - Adding useful attributes to roads (surface types, turn restrictions, names, etc.)
 - Fixing any other issues we may encounter

#### Data Sources
 - Public imagery: Bing, MapBox, Digital Globe, ESRI World View
 - Public traces: OSM GPS traces, Strava
 - Street-level imagery: Mapillary, OpenStreetCam, Pic4Carto
 - GIS imagery analysis by Kaart
 
#### Methods & Tools
##### Error Detection
The [OSM Wiki](http://wiki.openstreetmap.org/wiki/OSM_Tasking_Manager/Validating_data) and [LearnOSM](http://learnosm.org/en/coordination/review/) validation standards as well as the task guideline will need to be used as a guide to review work for any errors. 
##### Validation
Errors and warnings will be reviewed by the contributor using the [JOSM validation tool](http://wiki.openstreetmap.org/wiki/JOSM/Validator). The contributor will run this validation and fix any errors or warnings prior to any changes being uploaded.

#### Contributors
The project is open to OpenStreetMap contributors of any experience level.