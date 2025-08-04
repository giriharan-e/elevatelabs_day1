# elevatelabs_day1
day1_task : data cleaning raw dataset using Python(pandas)
the data set is Raw/uncleaned to practice data cleaning & preparation
steps: 
1. checked the data using df.info() which gives over view of the columns,null values count,data type
2. cheked for duplicates and removed them
3. cheked null values using df.isnull().sum()
4. replaced the null values in total column using quantity and price columns
5. droped null values in the date column
6. changed the datatype of date column from string to datetime
7. country column had different entries , normalised it
8. finally changed the entries into lower case using .str.lower 
