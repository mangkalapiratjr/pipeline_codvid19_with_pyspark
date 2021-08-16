# Import (AWS S3) , Cleansing and Transform Covid19 cases data using PySpark

Steps

Import Covid19 dataset from AWS S3 (using datasource from data.go.th)
Drop uninterested columns
Handle with missing values
Create a new column to group age by range
Find the wrong or inconsistent Province name in the dataset and correct them
Save output as parquet file
Send notification to users that data is ready using AWS SNS
