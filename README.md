# vital-signs-dataset

A series of csv files from several experiments of a group of 5 person is processed and converted into a final csv dataset ready to use in further AI-based modelling.

This repository  shows Data preparation phase of **Data Science** course mini-project at **Saarland University**. 

Real time, raw data of Oxygen saturation (SpO2) and Heart Rate are taken from the sensor + patch developed by the **Leibniz Institute of New Materials (INM)**.

Heart Rate and SpO2 values are measured while performing certain physiological activities such as “climbing steps”, “walking briskly”, “squats”, “planks” and “mountain climbing (MC)”.

Data Preparation consists on three steps:

1. Manual preprocessing:
   - Construction of independent csv file containing SpO2 and Heart Rate for each experiment.
   - Manual cleaning of junk data.
2. Processing exercise subsets:
   - Replacement of default sensor values “-999” by a mean value.
   - Shrink data in order to have balanced information for each type of physical exercise.
3. Removing outliers:
   - Outlier identification.
   - Outlier removal: Standard Deviation Method.
   - Outlier removal: DBSCAN.
