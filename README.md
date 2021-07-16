# Cleansing and Transform Covid19 cases data using PySpark

Steps
1. Import Covid19 dataset (csv file from data.go.th)
2. Drop uninterested columns
3. Handle with missing values
4. Create a new column to group age by range
5. Find the wrong or inconsistent Province name in the dataset and correct them
6. Save output as parquet file
