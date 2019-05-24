# Purchase-Analytics

I import the csv file to import data.

First, I read order_products.csv file and products.csv files into python using "open". I just remain the used columns and remove the columns I wil not use for the report data file. 

Second, I merge the 2 data set using the "product_id" and convert the new data to list. The new data only have "department_id" and "reordered" elements.

Third, I sort the data using the function with ascending order of "department_id".

Forth, I create dictonary with key-"department_id" and value-length of key and number of first time order.

Fifth, I convert the dictonary to list and write a csv file "report.csv" as the final output.
