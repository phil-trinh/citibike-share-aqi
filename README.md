# citibike-share-aqi
## Impacts of CitiBike Share on Air Quality Index in Manhattan, NY

Repository of code for research paper (TBA)

## Authors
Paul Intrevado  
Diane Woodbridge  
Nina Hua  
Rebecca (Bex) Reilly  
Victoria Suarez  
Philip Trinh

## [Main Spark Notebook](https://github.com/phil-trinh/citibike-share-aqi/blob/master/Manhattan_Bike-Sharing_AQI_Impact.ipynb)
All code for data extraction, transformation, and loading (ETL) is encompassed here. Notebook was executed on a seperate EC2 instance, mapped to an Amazon Web Services (AWS) Elastic Map Reduce (EMR) cluster through Sparkmagic configuration.

## [Configuration](https://github.com/phil-trinh/citibike-share-aqi/tree/master/Configuration)
Configuration files for replicating Python environment and EMR cluster.

## [Data](https://github.com/phil-trinh/citibike-share-aqi/tree/master/Data)
Includes final data frame that is used for modeling after transformation and links to the full bike-share and AQI data.

## [Timing](./Timing)
These notebooks are to execute and measure various timings for comparison.
