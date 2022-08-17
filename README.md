# Movies-ETL

## Project Overview

The purpose of this project was to create an automated pipeline that executes the following:

1. Takes in new data from various sources.
2. Performs the necessary transformations by removing duplicates, addressing null values, standardizing mixed data types, and filtering to capture the pertinent data.
3. Merge DataFrames and load into SQL tables.


## Resources
* Languages: Python with multiple libraries, SQL
* Platforms: Jupyter Notebook, via Anaconda and PostgreSQL via pgAdmin
* Data Sources: .json and .csv files

## Summary of Results

This project went as expected. Although the files were large, the ETL process allowed the large datasets to be dissected in various ways and I was successful in parsing out important information. The .json file from Wikipedia was the most challenging to transform because data was pulled from a website that has numerous authors/contributors and it appears that it's lacking strict standardization of the data. I found the other files to be more cohesive in their values and succinct in their construction. Overall, this process proved to be effective in filtering the data down to what was most valuable, and the code can easily be repurposed for future projects that are similar in nature.
