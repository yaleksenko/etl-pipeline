## ETL Pipeline

This repository contains an example of an Extract, Transform, Load (ETL) pipeline developed in Python using Jupyter Notebook. The pipeline processes two JSON files containing market capitazation data and a CSV file containing currency exchange rates. It performs transformations, including conversion to GBP using the exchange rate and rounding the figures, and then saves the results into a new JSON file.

## Structure

- `etl_pipeline.ipynb`: Jupyter notebook with all the code for the ETL process.
- Root folder containing the input and output data for the ETL process.

## Running the code

To run the ETL pipeline:

1. Clone this repository to your local machine.
2. Open Jupyter Notebook and navigate to the cloned repository.
3. Open the `etl_pipeline.ipynb` notebook.
4. Run the cells in the notebook to execute the ETL pipeline.

## Pipeline Stages

### Extract

The pipeline starts by extracting data from two JSON files and a CSV file using the pandas library.

### Transform

In the Transform stage, the pipeline performs several operations:

- Converts market cap data from various currencies to GBP using the exchange rate from the CSV file.
- Rounds the converted market cap to 2 decimal places.
- Change the column name 

### Load

In the Load stage, the pipeline writes the transformed data back into a new JSON file.

## Logging

The pipeline uses Python's built-in logging library to log messages for each stage of the ETL process. The log messages are written to a file named `etl.log` in the root directory.

