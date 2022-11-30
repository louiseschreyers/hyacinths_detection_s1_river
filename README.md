### hyacinths_detection_s1_river
## Purpose

Run a simple detection tool to estimate water hyacinth coverage using Sentinel-1 SAR satellite imagery. 

## About the data

The detection tool uses the Google Earth Engine API and Sentinel-1 SAR satellite data. The code uses the pre-processing steps from Mullissa et al., 2021, to create an analysis ready Sentinel-1 image collection. A hyacinth mask is then creted over a collection of Sentinel-1 scenes. Hyacinth coverage is then computed and a simple graph enables to download the estimates as a .csv file. 
 
## How to use the Javascript code

The JavaScript code corresponds to the file ''. Duplicate the JavaScript code in the Google Earth Engine editor. A Google Earth Engine account is required, as well as uploading the shapefiles of interest. Twelve shapefiles are provided into the resources folder, corresponding to twelve sectors of interest over the Saigon river, Vietnam. These could be replaced by other geometries/shapefiles of interest. 
