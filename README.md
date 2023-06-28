# Capstoneprj-Part2

This repository contains a job search pipeline implemented using Apache Airflow. 
The pipeline retrieves job search data from an API, processes and filters the data, and loads it into a Redshift database *** This was inconclusive as i could not load my schema on redshift
The pipeline consists of four tasks: saving JSON data to a file, uploading raw data to S3, processing the data, and loading it into the data warehouse*** incoclusive.
The tasks are orchestrated using an Airflow DAG named "Job_search_dag". 
The pipeline runs daily and requires AWS credentials, a configured Redshift database, and the necessary Python libraries. The code can be customized to fit specific requirements.
