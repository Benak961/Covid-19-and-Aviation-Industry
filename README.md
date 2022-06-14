# Impact of Covid-19 on the Aviation Industry

## Introduction
Aviation provides the only rapid worldwide transportation network, which makes it essential for global business. It generates economic growth, creates jobs, and facilitates international trade and tourism. The air transport industry supports a total of 65.5 million jobs globally. It provides 10.2 million direct jobs.

This project aims to analyse the impact of Covid-19 on the aviation industry. It also provided a great opportunity to develop skills and experience in a range of tools such as Apache Airflow, Apache Spark, Tableau and some of the AWS cloud services.

## Architecture
<p align="left">
    <img src="https://github.com/siddharth271101/Covid-19-and-Aviation-Industry/blob/main/assets/images/Architecture.png">
</p>

## Airflow Data Pipeline
<p align="left">
    <img src="https://github.com/siddharth271101/Covid-19-and-Aviation-Industry/blob/main/assets/images/Airflow_graph_view.png">
</p>

At a high-level, the airflow orchestrates the following tasks:

1. Upload the data and scripts from local machine to S3 bucket
2. Provision an EMR cluster
3. Submit a spark job to EMR cluster that executes the ETL workflow
4. Wait for the spark submission to complete
5. Terminate the EMR cluster


## Data sources

## Dashboard 

https://user-images.githubusercontent.com/91481367/173515514-9e4b0ac3-f24a-4c4a-bd77-de5c1fb574b0.mp4


<p align="left">
    <img src="https://github.com/Benak961/Covid-19-and-Aviation-Industry/blob/main/assets/images/screencapture-prod-apnortheast-a-online-tableau-2022-06-11-21_41_17.png">
    <img src="https://github.com/Benak961/Covid-19-and-Aviation-Industry/blob/main/assets/images/screencapture-prod-apnortheast-a-online-tableau-2022-06-11-21_39_59.png">
    <img src="https://github.com/Benak961/Covid-19-and-Aviation-Industry/blob/main/assets/images/screencapture-prod-apnortheast-a-online-tableau-2022-06-11-21_49_06.png">
    <img src="https://github.com/Benak961/Covid-19-and-Aviation-Industry/blob/main/assets/images/screencapture-prod-apnortheast-a-online-tableau-2022-06-11-21_43_00.png">
    
    
    
</p>



## Setup

## References
