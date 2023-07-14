## ETL Pipeline

This repository contains an example of an Extract, Transform, Load (ETL) pipeline developed in Python using Jupyter Notebook. The pipeline processes a CSV file containing currency rates, rounds the figures, and saves the results into a new CSV file.

## Structure

ETL_pipeline.ipynb: Jupyter notebook with all the code for the ETL process.
Root folder containing the input and output data for the ETL process.
Running the code

## To run the ETL pipeline:

- Clone this repository to your local machine.
- Open Jupyter Notebook and navigate to the cloned repository.
- Open the ETL_pipeline.ipynb notebook.
- Run the cells in the notebook to execute the ETL pipeline.
- 
## Pipeline Stages
## Extract
The pipeline starts by extracting data from a CSV file using the pandas library.

## Transform
In the Transform stage, the pipeline performs several operations:
Rounds the market cap to 2 decimal places.

## Load
In the Load stage, the pipeline writes the transformed data back into a new CSV file.

## Logging
The pipeline uses Python's built-in logging library to log messages for each stage of the ETL process. The log messages are written to a file named etl.log in the root directory.
