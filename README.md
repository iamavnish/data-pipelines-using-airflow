# Building Data Pipelines using Airflow

## Overview
This is Proof of Concept for representing a data pipeline as DAG (Directed Acyclic Graph) in Airflow.

## Use Case
Extract 3 fields from /etc/passwd file, replace field seperator, colon with comma and load the resulting output into csv file.

## PoC Complexity Level
Medium

## Tech Stack
- Apache Airflow (Open Source)
- Python

## Dataset
/etc/passwd file

## Solution
Create a DAG (my_first_dag.py) that defines a pipeline of tasks such as extract, transform, load and check using Python Opertor. Extract task extracts 3 fields from /etc/passwd and writes the output to extracted-data.txt. Transform task replaces colon with comma from extracted-data.txt and writes the output to transformed.txt. Load task reads from transformed.txt and writes to data_for_analytics.csv. Check task prints the contents of data_for_analytics.csv to standard output.

## DAG
![AirflowUI](https://github.com/user-attachments/assets/dc13b74b-0c14-4c83-ad6d-275acefec624)

