# Bike-Share Configuration

## Notebook Execution Environment
The included bikeshare.yml file is the Anaconda environment used for executing the main Spark Notebook. If replicating, remember to setup configurations for jupyter notebook access and Sparkmagic configuration to an AWS EMR cluster.

## EMR Python 3 Configuration
Upload **EMR_python3.json** file to AWS Simple Storage Service (S3) bucket and specify as a configuration step during EMR cluster creation. This will enable the cluster to run Python 3 by default along with configuring Spark on the cluster to allocate full resources.