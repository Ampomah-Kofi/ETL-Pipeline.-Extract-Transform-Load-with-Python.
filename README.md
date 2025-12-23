# ETL-Pipeline.-Extract-Transform-Load-with-Python.
This lab implements an end to end ETL pipeline using Python. It extracts data from multiple file formats, transforms the data, and loads the cleaned output into a database for analysis.

## ETL Pipeline. Extract, Transform, Load with Python

This lab implements an end to end ETL pipeline using Python. The pipeline extracts data from multiple file formats, transforms the data into standardized units, and loads the final dataset into a CSV file for further analysis.

This project demonstrates core data engineering skills used in data science workflows.

##Project Overview

The project reads data from CSV, JSON, and XML files, combines them into a single dataset, applies unit conversions, and stores the cleaned output in a target file. Each stage of the ETL process is logged with timestamps.

Extract Phase

The extraction stage performs the following tasks.

 - Reads CSV files using pandas.
 - Reads JSON files using pandas.
 - Parses XML files using ElementTree.
 - Combines all extracted data into a single DataFrame.

Transform Phase

The transformation stage standardizes the data.

Height values are converted from inches to meters.
Weight values are converted from pounds to kilograms.
All numeric values are rounded to two decimal places.

Load Phase

The load stage writes the transformed dataset to a CSV file.
The pipeline also records progress logs with timestamps for each ETL stage.

Technologies Used

Python
Pandas
XML ElementTree
CSV, JSON, and XML file handling
Basic logging with timestamps

Project Structure

etl_pipeline.py. Main ETL script
log_file.txt. Execution logs
transformed_data.csv. Final output file
Input data files. CSV, JSON, XML

How to Run the Project

Place all input files in the same directory as the script.
Run the script using Python.
Review transformed_data.csv and log_file.txt for results.
