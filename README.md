# Stock-Market-Analysis-Using-Kafka
## Introduction
This project simulates stock market data and uses Kafka to process data in real time.

## Objective
1. Develop a python script to simulate the stock market data.  
2. Create a producer and consumer and send data from the former to the latter.  
3. Send data from consumer to the S3 bucket.  
4. Create a Glue crawler to run over the S3 bucket that produces a table.  
5. Query data using Athena and connect to AWS QuickSight to build a dashboard.  

## Architecture
![Architecture](https://github.com/fernandes-cheryl/Stock-Market-Analysis-Using-Kafka/assets/100081376/4a566ac9-d80d-4498-a31b-d3f42621c809)

## Tech Stack
1. Python  
2. Amazon Web Service(AWS)  
  * S3  
  * Athena  
  * Glue Crawler  
  * EC2  
3. Apache Kafka  

## Dataset Used:
Stock data for Infosys Limited:  
https://finance.yahoo.com/quote/INFY/history?p=INFY
