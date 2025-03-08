# Uber-Data-Analytics-Brskdnz
## Introduction
Data pipeline (ETL) concepts are used with mageAI tools in this project that includes understanding of logical and physical data modelling matters (star schema),converting of JSON, CSV, parquet data formats using python programming language, and also using with linux connecting compute instance with mageAI.
## Architecture
![architecture2](https://github.com/user-attachments/assets/2d302dc2-1c15-4281-92ee-d6038d428b85)
## Infrastucture and Program
Programming Language - Python
Google Cloud Platform

  1.Google Storage
  2.Compute Instance
  3.BigQuery
  4.Looker Studio
Modern Data Pipeine Tool - https://www.mage.ai/
Contibute to this open source project - https://github.com/mage-ai/mage-ai
## Steps of Projects
  1.Data Ingestion (Raw Data Storage):
Raw data is stored in Google Cloud Storage (GCS) in CSV or JSON formats. The raw data could come from various external sources (e.g., logs, APIs, etc.).

  2.ETL with Mage AI:
Mage AI is used to automate the ETL process in the Compute Engine . It extracts data from the raw storage, applies transformation logic, and loads it into Google BigQuery for further analysis.

  3.Data Analysis (BigQuery):
Processed data is stored in Google BigQuery, where it is organized into tables. Users can run SQL queries to aggregate, filter, and analyze the data for insights.

  4.Data Visualization (Looker):
Dashboards and reports are created using Looker to visualize the data and present business insights in a clear, interactive format.
## Dataset
LC Trip Record Data Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. Here is the dataset used in the video - https://github.com/brskdnz/Uber-Data-Analytics-Brskdnz/blob/main/Dataset/uber_data.csv
More info about dataset can be found here:
  1.Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
  2.Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf
## Data Model
![Ekran görüntüsü 2025-03-08 161343](https://github.com/user-attachments/assets/dcf91fdd-d6f8-4151-8b32-ba96ade55507)
  
