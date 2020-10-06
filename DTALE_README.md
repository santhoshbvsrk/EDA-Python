#DTALE
This is a webclient for Pandas which minimizes the usage of describe function which is for statistical calculations of dataframe, info for finding data types of fields, p
andas profiling for finding missing data and outliers, visualization of data.

 describe ---> this works as df.describe() function of pandas
 heatmap ---> this works as sns.heatmap(df.corr(),annot=True)
 Graphs ---> Here, we have options to create different graphs by selecting columns of data frame, you can also copy the code of the graph created by clicking on copy-code.
  Custom Filter --> This is used for creating filters like dropping NaN values, showing NaN values, filtering data based on date or string values, etc.,
Build Colum --> Using this we can build a new column by fetching data from multiple other columns as per the need 
Similarly, you can click on each and every field and see the missing data for a specific field, outliers for a specific field, outlier values, data type, it'll help us by highlighting columns in which there is missing data, columns which have the same data type, columns which have outliers along with outlier values, etc.,

This will be a replacement for pandas profiling and remembering the code for drawing graphs of any kind in Pandas.
