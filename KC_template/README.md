# KC template for mapping
The purpose of this project is to provide a template for GIS work in the CleanAirNow Kansas City study area. To this end, we define a CRS, study area, cartographic boundaries (states, counties, cities, etc), and places/objects of interest.

## Coordinate Reference System (CRS)
EPSG:6350 NAD83(2011) / CONUS Albers <br />
Chosen for its popularity and practicality for mapping in the continental US. It is an equal area reference, which has advantages for information science but causes some distortion to direction. If direction accuracy is preferred, a better CRS may be a conical system.

## US states, counties, 
2018 census bureau cartographic state boundaries, shapefile. <br />
Open data download: https://www.census.gov/cgi-bin/geo/shapefiles/index.php

## State and county data, MO and KS
TIGER/Line data from the US Census Bureau, shapefiles. <br />
Open data download:
  
## Greater KC study area
KC_MARC-MSA-2013_boundary.shp - shapefile, polygon geometry <br />
The study area is the Mid-America Regional Council (MARC) KC Metropolitan Statistical Area (MSA) as defined most recently in 2013, the 14 counties in Kansas and Missouri: Cass (MO), Clay (MO), Clinton (MO), Jackson (MO), Johnson (KS), Lafayette (MO), Leavenworth (KS), Miami (KS), Platte (MO), Ray (MO) and Wyandotte (KS). The Missouri-Kansas Combined Statistical Area (CSA) is possibly a better choice as it includes Douglas County (KS), where CANow does frequent work. PDF maps provided by MARC detailing both study areas are available. More MARC information is available at http://www.marc.org/Data-Economy/Metrodataline/Population/Statistical-Area

