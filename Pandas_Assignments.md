# PandasAssignment

Q1. How do you load a CSV file into a Pandas DataFrame?
To load data into Pandas DataFrame from a CSV file, use pandas.read_csv() function.

Q2. How do you check the data type of a column in a Pandas DataFrame?
To check the data type in pandas DataFrame we can use the “dtype” attribute

Q3. How do you select rows from a Pandas DataFrame based on a condition?
You can select rows from pandas dataframe based on condition using the loc [] attribute

Q4. How do you rename columns in a Pandas DataFrame?
One way of renaming the columns in a Pandas dataframe is by using the rename() function

Q5. How do you drop columns in a Pandas DataFrame?
Drop or delete column in pandas by column name using drop() function

Q6. How do you find the unique values in a column of a Pandas DataFrame?
Pandas Dataframe.nunique () method The Pandas Dataframe.nunique () method returns a numpy array of a number of elements in the dataframe that are unique

Q7. How do you find the number of missing values in each column of a Pandas DataFrame?
To get the count of missing values in each column of a dataframe, you can use the pandas isnull () and sum () functions together. The following is the syntax: # count of missing values in each column df.isnull().sum() 

Q8. How do you fill missing values in a Pandas DataFrame with a specific value?
Use the fillna () Method The fillna () function iterates through your dataset and fills all empty rows with a specified value. This could be the mean, median, modal, or any other value

Q9. How do you concatenate two Pandas DataFrames?
A concatenation of two or more data frames can be done using pandas.concat () method. concat () in pandas works by combining Data Frames across rows or columns. We can concat two or more data frames either along rows (axis=0) or along columns (axis=1)

Q10. How do you merge two Pandas DataFrames on a specific column?
We can merge two Pandas DataFrames on certain columns using the merge function by simply specifying the certain columns for merge

Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?
This is done using the groupby () method given in pandas

Q12. How do you pivot a Pandas DataFrame?
Index: Which column should be used to identify and order your rows vertically
Columns: Which column should be used to create the new columns in our reshaped DataFrame. Each unique value in the column stated here will create a column in our new DataFrame.
Values: Which column (s) should be used to fill the values in the cells of our DataFrame

Q13. How do you change the data type of a column in a Pandas DataFrame?
Using DataFrame.astype () method. We can pass any Python, Numpy or Pandas datatype to change all columns of a dataframe to that type, or we can pass a dictionary having column names as keys and datatype as values to change type of selected columns

Q14. How do you sort a Pandas DataFrame by a specific column?
To sort the rows of a DataFrame by a column, use pandas. DataFrame. sort_values () method with the argument by = column_name. 

Q15. How do you create a copy of a Pandas DataFrame?
Use the pandas dataframe copy () function to create a dataframe’s copy

Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?
 1,Use the operators &, |, ~ instead of and, or, not respectively Pandas provides operators & (for and ), | (for or ), and ~ (for not) to apply logical operations on series and to chain multiple conditions together when filtering a pandas dataframe. ...
2) Use parenthesis () to group multiple conditions

Q17. How do you calculate the mean of a column in a Pandas DataFrame?
To calculate the mean of whole columns in the DataFrame, use pandas.Series.mean ()

Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?
To find the standard deviation of a series or a column in a DataFrame in pandas, the easiest way is to use the pandas std()function

Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?
We can use the .corr() method to get the correlation between two columns in Pandas
Q20. How do you select specific columns in a DataFrame using their labels?
You can select multiple columns by labels by passing the column labels as a list to the dataframe object

Q21. How do you select specific rows in a DataFrame using their indexes?
If you’d like to select rows based on integer indexing, you can use the .iloc function.

If you’d like to select rows based on label indexing, you can use the .loc function

Q22. How do you sort a DataFrame by a specific column?
To sort the rows of a DataFrame by a column, use pandas. DataFrame. sort_values () method with the argument by = column_name

Q23. How do you create a new column in a DataFrame based on the values of another column?
To create a new column based on other columns, either:

use column-arithmetics for fastest performance.

use NumPy's where(~) method for creating binary columns

use the apply(~) method, which is the slowest but offers the most flexibility

use the Series' replace(~) method for mapping new values from existing columns.

Q24. How do you remove duplicates from a DataFrame?
df.drop_duplicates() -use the function to remove duplicate

Q25. What is the difference between .loc and .iloc in Pandas?
The main difference between pandas loc [] vs iloc [] is loc gets DataFrame rows & columns by labels/names and iloc [] gets by integer Index/position.