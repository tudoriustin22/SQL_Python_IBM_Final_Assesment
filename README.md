# IBM SQL Databases with Python – Final Assessment

This repository contains the final graded assessment notebook for the **IBM SQL Databases with Python for Data Science and Machine Learning** course. The project demonstrates working with real-world datasets using `pandas`, `SQLite`, and `SQL` to perform data analysis.

## Project Summary

The assessment involves:

1. Loading and exploring three datasets related to the city of Chicago.
2. Creating an SQLite database (`FinalDB.db`) and storing the datasets as SQL tables.
3. Writing and executing SQL queries to answer 10 questions.

## Datasets Used

The following datasets were used in this project:

1. **Socioeconomic Indicators in Chicago**  
   [Census Data - Socioeconomic Indicators](https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2)

2. **Chicago Public Schools**  
   [School Progress Report Cards 2011-2012](https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t)

3. **Chicago Crime Data**  
   [Crimes 2001 to present](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2)

**Note:** Pre-processed versions of these datasets were used. You can download them from the links below:

- [ChicagoCensusData.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCensusData.csv)  
- [ChicagoPublicSchools.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoPublicSchools.csv)  
- [ChicagoCrimeData.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCrimeData.csv)

## Tools and Libraries

- Python 3.x
- pandas
- sqlite3
- ipython-sql
- prettytable

## Tasks Overview

The notebook includes the following steps:

1. Install dependencies and import required libraries.
2. Load datasets using `pandas`.
3. Create and populate SQLite tables:
   - `CENSUS_DATA`
   - `CHICAGO_PUBLIC_SCHOOLS_DATA`
   - `CHICAGO_CRIME_DATA`
4. Write and execute SQL queries to solve the following:
   - Total number of crimes
   - Community areas with income below $11,000
   - Crimes involving minors or kidnapping of children
   - Types of crimes reported at schools
   - Average safety scores by school type
   - Top 5 areas with the highest poverty percentage
   - Most crime-prone community area
   - Area with the highest hardship index
   - Community area with the most crimes (via subquery)
