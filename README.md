# Uber Data Analytics | Modern Data Engineering GCP Project

## Overview
The Uber Data Analytics project involved analyzing Uber trip records using Google Cloud Platform (GCP) services, Python, and the Mage Data Pipeline Tool. The dataset included information on pick-up/drop-off details, fares, payment types, and passenger counts. Through data transformations and loading into BigQuery, dimension tables were created, and a fact table was generated. Looker Studio was utilized for data visualization, enabling the creation of interactive dashboards and reports to gain insights from the analysis. 

## Architecture 
<img src="architecture.jpg">

## Technology Used
- Programming Language - Python

Google Cloud Platform
1. Google Storage: Google Storage was used to store the Uber data CSV file. It provides a scalable and reliable storage solution for data files, allowing easy access and retrieval during the data analytics process.
2. Compute Instance: A Compute Instance in Google Cloud Platform was utilized to execute the data analytics tasks and run the Python code. It provides a virtual machine environment with configurable resources, enabling efficient processing of large datasets and running complex computations.
3. BigQuery: BigQuery was used as the data warehouse for storing and querying the Uber trip records dataset. It offers a serverless and highly scalable solution for analyzing large datasets with fast SQL queries. BigQuery simplifies data management and provides advanced analytics capabilities.
4. Looker Studio: Looker Studio was utilized for data visualization and exploration. It enables the creation of interactive dashboards, reports, and visualizations based on the analyzed Uber data. Looker Studio helps to present data insights in a user-friendly and visually appealing manner, facilitating data-driven decision-making.
5. Modern Data Pipeine Tool - https://www.mage.ai/

## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

Here is the dataset used in the video - https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
<img src="data_model.jpeg">
