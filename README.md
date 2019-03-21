The Impact of Bike-Sharing Ridership on Air Quality:  
A Scalable Data Science Framework
---

Research of impacts of CitiBike-Share on Air Quality Index (AQI) in Manhattan, NY.  
Repository of code for research paper for The 3rd IEEE International Conference on Smart City Innovations 2019 (TBA).

## Authors
Paul Intrevado  
Diane Woodbridge  
Nina Hua  
Rebecca (Bex) Reilly  
Victoria Suarez  
Philip Trinh

## [Main Spark Notebook](./Manhattan_Bike-Sharing_AQI_Impact.ipynb)
All code for data extraction, transformation, and loading (ETL) is encompassed here. Notebook was executed on a seperate EC2 instance, mapped to an Amazon Web Services (AWS) Elastic Map Reduce (EMR) cluster through Sparkmagic configuration.

## [Configuration](./Configuration)
Configuration files for replicating Python environment and EMR cluster.

## [Data](./Data)
Includes final data frame that is used for modeling after transformation and links to the full bike-share and AQI data.

## [Timing](./Timing)
These notebooks are to execute and measure various timings for comparison.
