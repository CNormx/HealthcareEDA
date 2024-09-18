# Synthea Healthcare EDA using SQL
In this project I used the programming language SQL to complete an exploratory data analysis of hospital patients created by Synthea. [Synthea](https://synthetichealth.github.io/synthea/) is an open-source, synthetic patient generator that models the medical history of synthetic patients.
Performing the analyzation will allow me to discover patterns, spot anomalies, find outliers, answer questions & assumptions, test hypotheses, and find interesting relationships between the variables.

## File Descriptions

I downloaded individual CSV files from Synthea to obtain the Patients, Immunizations, and Encounters tables. I then created the Synthea Healthcare dataset in BigQuery and imported the tables into it. 
The data files below can be found in `synthea_sample_data.zip`. <br>
- `Traffic_Crashes_Resulting_in_Injury_20240819.csv` contains all crashes resulting in an injury.

- `patients.csv` contains all patients of the hospital

- `immunizations.csv` contains all and various immunizations records of patients
- 
- `encounters.csv` contains the number of visitations and the time length each patients has had

Code file:
- `docs/Healthcare Exploratory Data Project using SQL.md` contains all the SQL queries for data exploration and full exploratory analysis. 

## Interesting Findings:

