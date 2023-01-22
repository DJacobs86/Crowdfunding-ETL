# Crowdfunding-ETL
Module 8
# Extract, Transform, Load... ETL!
Performing ETL skills on a large dataset. I used Puthon to extract and trandform and SQL was used to load and query.
# Overview
Independent Funding is a crowdfunding platform for funding independent projects or ventures, and they have been growing! Since it's gorwth it now needs to move all their accessible data from one large Excel file onto a PostgreSQL database. Now the analytics team will be able to perform analysis and create reports for company stakeholders as well as individuals who donate to projects.

# Summary 
Using Python, Pandas, Jupyter Notebook, and PostgreSQL the following tasks were completed:

- Extracted and transformed the data from the large Excel file into four separate CSV files

- Created a PostgreSQL database and tables by using an ERD

- Loaded the CSV files into the database

- Ran SQL queries to generate reports for stakeholders

## Images
Python was usedto clean up a csv file in order to organize the dataframe/ csvfile
### Dirty / Before
![ETL before image](/Images/data_before.png)
Then I hit with some Orbit Gum
### Cleaned Up / After
![ETL after image](/Images/data_after.png)

### I Love IT When A Plan Comes Together
Every tasks needs a good plan, and that's just what I did. I planned the connections between the csv files before loading the data into SQL :
![DB mapping image](/Images/crowdfunding_db_relationships.png)

It was finished all up with a few queries : 
![Crowdfunding query](/Images/crowdfunding_query.png)

