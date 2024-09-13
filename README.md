# Building Data Pipelines using Airflow

## Overview
This is Proof of Concept for representing a data pipeline as DAG (Directed Acyclic Graph) in Airflow.

## Use Case
Process /etc/password file

## PoC Complexity Level
Medium

## Tech Stack
- Apache Airflow (Open Source)
- Python

## Dataset
/etc/passwd file

## Solution
Extract 3 fields from /etc/passwd file, replace field seperator colon with comma (transformation) and load the resulting output into csv file.
