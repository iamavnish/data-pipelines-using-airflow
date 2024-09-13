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
Extract 3 fields from /etc/passwd file, replace field seperator colon with comma (transformation) and load the resulting output into csv file.

## DAG
![AirflowUI](https://github.com/user-attachments/assets/dc13b74b-0c14-4c83-ad6d-275acefec624)

