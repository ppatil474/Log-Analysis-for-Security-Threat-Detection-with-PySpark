# Network Data Analysis with PySpark

This project involves analyzing network data using PySpark. The data is processed, cleaned, and used to build a RandomForestClassifier model to predict labels based on various network features.

## Project Structure
- **Data Loading and Initial Exploration**: Load the data and perform initial exploration including schema inspection and summary statistics.
- **Data Cleaning**: Handle null values and filter out rows with zeros in critical columns.
- **Feature Engineering**: Drop unnecessary columns and compute correlations between features.
- **Model Building**: Use Spark MLlib to build and evaluate a RandomForestClassifier model.
- **Visualization**: Plot histograms of the features and visualize the model's predictions versus actual labels.

## Requirements
To run this project, you need to have the following dependencies installed:

- Python 3.8+
- PySpark
- pandas
- matplotlib

## Installation
You can install the required packages using the following command:
```bash
pip install -r requirements.txt
```

## Running the Project
Ensure you have the data file `2021_01_20.csv` in the specified path.
Run the Jupyter notebook to execute the analysis and model building steps.

## Project Files
`DSCI_632_Final_pp673.ipynb`: Jupyter notebook containing the entire analysis and model building process.


## Acknowledgments
This project is part of the Data Science Capstone Project for the DSCI 592 course.