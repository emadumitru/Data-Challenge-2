# Data Challenge 2 - Group 17

### Requirments
Before running the code, the csv 'all-regions.csv' needs to be placed in the same folder as the notebook.

### The data
The csv provided contains the aggregated data of street csvs for all areas staring in December 2010 and ending in October 2021.
The function called 'add_new_month' is defined in the code and can be used to add a new street csv for a month of crime for 1 region.
In The 'Loading data' part of the code, the second cell needs to be uncommented and the path to the new csv needs to be added. 

### The models
There are 3 models defined. 
'forecasting_area_crime' takes a list of areas as argument and forcasts the amount of monthly crime for each of them for the last 10% of data.
'forecasting_crime_uk' takes as argument a list containing 'Small UK' and/or 'Full UK' and forecasts the monthly crime for all of UK
'forecasting_percentage_type' takes a list of areas and forecasts the distribution of types of crime for each month of the last 10% of data for each area. 

### Forecasting
In the 'Running the forecasting' section of the code the models run for all areas except for the 7 mentioned to contain errors.
The error areas are 'British Transport Police', 'Cheshire Constabulary', 'Greater Manchester Police', 'Northumbria Police', 'Police Service of Northern Ireland', 'Thames Valley Police' and 'West Midlands Police'.

### Plots and results
Both the plots and the results used in the presentation and report can be found inthe last 2 sections of the code.
