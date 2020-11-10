# Analysis and Forecasting of Sales in Retail Trade for the USA
This is a Time-series analysis project done in R.
## Original dataset link and info
The dataset has been downloaded from https://www.census.gov/econ/currentdata/datasets/index. The dataset is Monthly Retail Trade and Food Services(filename: MRTS-mf.zip).
The file contains data from many categories, eg. retail trade, motor vehicles and parts dealers, furniture and home furnishing stores, electronics and appliances stores etc. For each category there are also sub-categories, eg. for retail trade and food services, there are auto, gas, auto and gas, for furniture and home furnishing stores, there are furniture stores, home furnishing stores etc.
I have done the analysis on the category retail trade. So the data relating to retail trade have been extracted using MS-Excel.2007 The steps are: 
1.	Open MRTS-mf
2.	Select 447th row, and any column—per_idx, cat_idx, dt_idx, et_idx, geo_idx, is_adj, val
3.	Data>Filter>Select cat_idx=5, dt_idx=1, is_adj=0
4.	Copy the rows and paste these in a new excel sheet and save it.
The analysis has been done on the new dataset.
## New dataset info
The dataset contains Sales data for retail trade from Jan 1992 to May 2020.
## What has been done
Decomposing the data into its components, ie. Trend, Seasonal component, Irregular component.
Predicting sales values for future months and years and comparison.
