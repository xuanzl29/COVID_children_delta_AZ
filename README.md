# Dangerness of COVID Delta variant in children (Arizona State)

# Overview:

This project answer the question: if Delta variant is more or less dangerous to children using the Arizona dataset provided by CDC.
After understanding the data collecting process, some data cleaning was done, and then some data visulization was conducted to help better 
understanding the dataset. The hospitalization vs non-hospitalization counts for all the other variants previous to Delta variant and those for Delta variant are analyzet using Chi test to answer the question.

This project is original a groupwork project at Seattle University for course DATA5100. 
This repository contains only my portion of the work. Any contributions by other team member related to this repository are credited below.

# Data source:
The original data is provided and kept renewing by CDC: https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data-with-Ge/n8mc-b4w4/data.

AZFullDataset.csv is the csv file of the full dataset download from the link above in November 2020.

FullAZCDCData_0_17Only_Updated.csv is the csv file from only 0-17 age group. The lastest one can be downloaded by filtering for this age group from the website in November 2020. The on used in the project can be found in this repository.

# Considerations:
1. Danger is defined as hospitolization.
2. Missing hospitalization is treated as no hospitalization.
3. Observations from August 2021 to October 2021 are treated as Delta variants data since that was the time that Delta variants were at least 98% among all COVID patients.
4. Observations from August 2020 to October 2020 are treated as non-Delta variants (that exist previous to Delta). Same months are chosen comparing to the Delta group to control the weather and flu season as factors that could effect COVID.
5. Vaccinations cannot be factored out since the related information isn't provided by the dataset. 

# Technology and Packages:
Python 3

Jupyter Notebook: For code development and results presentation.

Google Colab: For teamwork activities and sharing.

pandas: Python package for data analysis.
numpy: Python package for using arrays.
matplotlib.pyplot: Python package for data visulization.
seaborn:Python package for data visulization.
scipy.stats: Python package for computing.
datetime: Python package for transferring object type to datetime.


# Resources and Credits:

Data source: https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data-with-Ge/n8mc-b4w4/data.

Table making: https://stackoverflow.com/questions/26678467/export-a-pandas-dataframe-as-a-table-image.

My team member, Shabnam (Kathryn) Pilisuk, helped to find the dataset.

My team member, Liya Lapierre, dedicated to find the right statistical method to use as well as the commands to do that.
