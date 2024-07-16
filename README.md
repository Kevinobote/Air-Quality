# Air Quality Index (AQI) Analysis Project

## Introduction

This project involves analyzing Air Quality Index (AQI) data collected from the United States and Mexico, specifically focusing on the three states with the most observations (California, Texas, and Pennsylvania) and other states. The AQI is a measure used to report daily air quality, indicating how polluted the air currently is or how polluted it is forecast to become. This analysis is conducted using Python's pandas library for data manipulation and analysis.

## Project Structure

The project contains the following main components:

- **epa_ca_tx_pa.csv**: A CSV file containing AQI data for the three states with the most observations: California, Texas, and Pennsylvania.
- **epa_others.csv**: A CSV file containing AQI data for other states and territories.
- **Air_Quality_Dataframes_pandas_classwork.ipynb**: A Jupyter notebook that performs the data analysis using pandas.
- **README.md**: This document, providing an overview of the project and instructions on how to set it up and run the analysis.

## Dataset Description

### epa_ca_tx_pa.csv

This dataset contains AQI data for California, Texas, and Pennsylvania. Each row represents an observation and includes the following columns:

- `statename`: The name of the state.
- `countyname`: The name of the county.
- `aqi`: The Air Quality Index value.

### epa_others.csv

This dataset contains AQI data for other states and territories. The structure is the same as the `epa_ca_tx_pa.csv` dataset, with the following columns:

- `statename`: The name of the state.
- `countyname`: The name of the county.
- `aqi`: The Air Quality Index value.

## Analysis Tasks

The analysis includes the following tasks:

1. **Read Data**: Load the data from the CSV files into pandas DataFrames.
2. **Summary Information**: Obtain high-level summary information about the datasets, including the number of rows and columns, column names, data types, and memory usage.
3. **Summary Statistics**: Examine summary statistics of the numeric columns.
4. **Data Exploration**: Explore the data using iloc indexing, sorting, and Boolean masking.
5. **GroupBy and Aggregation**: Group data by state and calculate the mean AQI for each state.
6. **Complex Boolean Masking**: Filter data to identify observations with AQI values of 51 or higher for specific states.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- pandas library
- Jupyter Notebook

You can install the required libraries using pip:

```sh
pip install pandas jupyter
```

### Setup

1. Clone the repository to your local machine:

```sh
[git clone https://github.com/Kevinobote/Air-Quality.git]
cd Air-Quality
```

2. Ensure the CSV files (`epa_ca_tx_pa.csv` and `epa_others.csv`) are in the project directory.

### Running the Analysis

1. Start Jupyter Notebook:

```sh
jupyter notebook
```

2. Open the `Air_Quality_Dataframes_pandas_classwork.ipynb` notebook in your browser.
3. Run the cells in the notebook to perform the analysis.

The notebook will perform the following steps:

1. Read the data from `epa_ca_tx_pa.csv` and `epa_others.csv`.
2. Display summary information and statistics for the datasets.
3. Perform data exploration tasks, including sorting and filtering.
4. Calculate mean AQI values by state.
5. Filter the data for specific conditions (e.g., AQI values of 51 or higher in Washington).

## Conclusion

This project provides a comprehensive analysis of AQI data using pandas. By following the steps outlined in this README, you can reproduce the analysis and explore the data further.


## Acknowledgments

- [AirNow.gov](https://www.airnow.gov/aqi/aqi-basics/) for providing information on AQI basics.
- The U.S. Environmental Protection Agency (EPA) for the AQI data.
