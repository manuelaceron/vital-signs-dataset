# Building a Vital signs dataset

This repository showcases the data preparation phase of a Data Science course mini-project at *Saarland University*. It involves implementing various techniques to process raw data collected from a series of experiments using a sensor patch developed by the *Leibniz Institute of New Materials (INM)*. The data includes real-time measurements of Oxygen saturation (SpO2) and Heart Rate (HR), along with xyz acceleration, recorded during activities such as "resting", “climbing steps”, “walking briskly”, “squats”, “planks”, and “mountain climbing (MC)”.

The process includes processing CSV files from multiple experiments involving a group of five individuals, transforming them into a refined CSV dataset. Specifically, data preparation in the notebook DS_data_group_18.ipynb consists of the following steps:

## Manual preprocessing
1. Creation of independent CSV files containing SpO2 and Heart Rate data for each experiment.
2. Manual removal of erroneous data entries.

## Processing exercise subsets
1. Replacement of default sensor values ("-999") with mean values.
2. Adjustment of data to achieve balanced information across different types of physical exercises.

## Outlier removal
1. Identification of outliers.
2. Removal of outliers using the Standard Deviation Method and DBSCAN.

## Analysis
1. Data analytics on the final dataset to gain insights into its distribution and characteristics.

Overall, this repository demonstrates the comprehensive preparation and analysis of raw sensor data, culminating in a refined dataset suitable for further AI-based modeling.
