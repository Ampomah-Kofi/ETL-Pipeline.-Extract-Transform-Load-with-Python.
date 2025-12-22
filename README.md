# ETL-Pipeline.-Extract-Transform-Load-with-Python.
This lab implements an end to end ETL pipeline using Python. It extracts data from multiple file formats, transforms the data, and loads the cleaned output into a database for analysis.

Project overview
This project implements a simple ETL pipeline using Python. The pipeline extracts data from multiple file formats, transforms the data into standardized units, and loads the final dataset into a CSV file for further analysis.

This project demonstrates core data engineering skills used in data science workflows.

What the pipeline does
Extract

Reads CSV files using pandas

Reads JSON files using pandas

Parses XML files using ElementTree

Combines all sources into a single DataFrame

Transform

Converts height from inches to meters

Converts weight from pounds to kilograms

Rounds values to two decimal places

Load

Writes the transformed dataset to a CSV file

Logs each ETL stage with timestamps

Technologies used

Python

Pandas

XML ElementTree

CSV, JSON, XML file handling

Basic logging with timestamps

Project structure

etl_pipeline.py. Main ETL script

log_file.txt. Execution logs

transformed_data.csv. Final output file

Input data files. CSV, JSON, XML

How to run the project

Place all CSV, JSON, and XML input files in the same directory as the script

Install dependencies

pip install pandas

Run the script

python etl_pipeline.py

Check outputs

transformed_data.csv for results

log_file.txt for ETL execution logs

Sample output
The final dataset includes the following columns.

name

height in meters

weight in kilograms

Logging
The pipeline logs the following stages with timestamps.

ETL Job Started

Extract phase Started and Ended

Transform phase Started and Ended

Load phase Started and Ended

ETL Job Ended

Skills demonstrated

Multi format data extraction

Data transformation and unit normalization

Data pipeline structuring

Logging and process tracking

Reproducible data workflows

Possible improvements

Add database loading instead of CSV

Add error handling and validation

Add unit tests

Support large datasets
