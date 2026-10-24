# MiniProject  
## Data Analysis_Excel_PowerBi

#### 1. Data Cleaning 
*  Capitalized each word of the dataset's headers using Proper function.
*  Loaded data to power query editor to transform.
*  Capitalized each word on Gender column.
*  Replaced values in gender column F as Female and M as Male.
*  Removed Empty rows from column "Age".
*  "Years_Of_Experience" field's 0 value rows are replaced by null. Added a custom column to replace the null values with IF condition where if the "Age" is above 30, the null is replaced by the column median and if the age is below 30 the null values are replaced by 5.
*  ReplaceD empty rows with null in column "Hourly_Rate" column and extracted last 3 last characters to remove "USD" text from some of the row values, later the Trim function was used to remove the leading white spaces.
*  Replaced null values with average of the column in "Hourly_Rate" field.
*  Rating column's rows with 0 is replaced by null and later the null values are replaced with average of the column.
*  "Is_Active" field standardized by replacing 1,Y,Yes,True as Active and 0,No,N,False as Inactive and null rows as Unknown.
*  Client_Satisfaction field is dealt by custom column with If condition to convert whole number to decimal/integer number and replaced 0 as "Unrated".
