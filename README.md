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

## IDE:
Jupyter Notebook

## Dataset Used:
Stock data for Infosys Limited:  
https://finance.yahoo.com/quote/INFY/history?p=INFY

## Process:
1. Create an EC2 instance and connect to it.
2. Follow commands on [command.txt](https://github.com/fernandes-cheryl/Stock-Market-Analysis-Using-Kafka/blob/main/commands.txt) to install Apache Kafka on the EC2 instance.
3. Simulate stock market data by sampling one DataFrame at a time.
4. Use producer to send data to the topic and onto the consumer.
5. Send data from consumer to S3 bucket.
6. Configure AWS CLI to send local data from the machine to S3.
7. Use Glue crawler to create a catalog over the S3 bucket.
8. Use AWS Athena to query over the data.


