# Synthea Healthcare EDA using SQL
In this project I used the programming language SQL to complete an exploratory data analysis of hospital patients created by Synthea. [Synthea](https://synthetichealth.github.io/synthea/) is an open-source, synthetic patient generator that models the medical history of synthetic patients.
The analysis will allow me to collect the total percentage of patients who received and did not receive influenza vaccine in 2021. This percentage is further observed by age, race, gender, and location. This helps assess immunization goals, evaluate hospital performance, guide public health messaging and immunization campaigns, research and predict resource needs, and more.

## File Descriptions

I downloaded individual CSV files from Synthea to obtain the Patients, Immunizations, and Encounters tables. I then created the Synthea Healthcare dataset in BigQuery and imported the tables into it. 
The data files below can be found in `synthea_sample_data.zip`. <br>

- `patients.csv` contains all patients of the hospital

- `immunizations.csv` contains all and various immunizations records of patients

- `encounters.csv` contains the number of visitations and the time length each patients has had

Code file:
- `Healthcare Exploratory Data Project using SQL.md` contains all the SQL queries for data exploration and full exploratory analysis. 

## Summary:
Through exploring the datasets and reading what values they held I was able to create queries that will result in visual charts to produce easily accessible data. This project allowed me to utilize SQL and learn how different statements such as CTE’s, CASE, SUBSTR, and LEFT JOIN can lead to successful and insightful data analyzing. Finding the variables that are required for statistics is key to delivering what stakeholders and a general audience can see within data.

[The Full EDA](https://synthetichealth.github.io/synthea/)
