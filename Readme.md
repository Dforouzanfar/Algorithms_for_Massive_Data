# Market Basket Analysis Using Apriori and PySpark
## Project Overview
Using the Apriori algorithm and PySpark, this project conducts a Market Basket Analysis on a large dataset scraped from LinkedIn in 2024.

## Project Objectives
This project aims to analyze skill requirements dataset to identify common skills and skill combinations and generate association rules.

## Dataset
The dataset consists of 1.3 million job listings with two main columns:
* Link: A URL to each job listing.
* Skills: A comma-separated list of skills required for each job.

To balance computational efficiency and meaningful results, a sample of the dataset was used.

## Results
Frequent Singletons: 81 frequently appearing individual skills, with "communication" as the most common.
Frequent Pairs: 67 pairs of skills, with "teamwork and communication" as the most frequent combination.
Frequent Triples: 25 triples, with "teamwork, communication, and customer service" as the most common group.

## To run this project, you’ll need:
Python 3.7+
PySpark for distributed data processing
Kaggle API to download the dataset
