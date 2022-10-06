# Ecuadorian Grocery Sales

  
Favorita is one of the largest grocery chains in Ecuador. Taking their time series data, I explored the data to gain insights on how products are purchased, and how external factors like oil prices and holidays effect sales. Visualization is important in data analysis as it is easily shows non-technical viewers trends in the data.

# Data Structure

Datetime | zone_load_MW | tmpf | hour | month | dayofweek  
-------- | -------------| ---- | ---- | ----- | --------
2004-10-02 00:00:00 | 13147.0 | 69.08 | 0 | 10 | 2 


# Goals

## To Do
- Split dataset to test/train
- Build model
- Validate model

## Completed 
- Check null/missing values in load profile.
- Merge load data to temperature data using datetime as key.
- Drop null values created from merge
