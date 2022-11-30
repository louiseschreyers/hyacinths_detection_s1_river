### hyacinths_detection_s1_river
## Purpose

Run a simple detection tool to estimate water hyacinth coverage using Sentinel-1 SAR satellite imagery. 

## About the data

The detection tool uses the Google Earth Engine API and Sentinel-1 SAR satellite data. The code uses the pre-processing steps from Mullissa et al., 2021, to create an analysis ready Sentinel-1 image collection. A hyacinth mask is then created over a collection of Sentinel-1 scenes. Hyacinth coverage is then computed and a simple graph enables to download the estimates as a .csv file. 

![alt text](https://postimg.cc/dZ0bFV1K/9ba56a5c)

## How to use the Javascript code

The JavaScript code corresponds to the file 'gee_code'. Duplicate the JavaScript code in the Google Earth Engine editor. A Google Earth Engine account is required, as well as uploading the shapefiles of interest. Twelve shapefiles are provided into the resources folder, corresponding to twelve sectors of interest over the Saigon river, Vietnam. These could be replaced by other geometries/shapefiles of interest. 

It is also required to go to the gee_s1_ard public repo (https://github.com/adugnag/gee_s1_ard) and copy the contents of s1_ard.js to your own repository. This is necessary to process the Sentinel-1 SAR imagery collection. 

Mullissa A., Vollrath A., Braun, C., Slagter B., Balling J., Gou Y., Gorelick N.,  Reiche J. (2021). Sentinel-1 SAR Backscatter Analysis Ready Data Preparation in Google Earth Engine. Remote Sensing, 13(10), 1954; https://doi.org/10.3390/rs13101954 
