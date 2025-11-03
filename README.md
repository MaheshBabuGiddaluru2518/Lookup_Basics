# Lookup_Basics

# VLOOKUP 
It is an abbreviation for vertical lookup. It is a powerful function in Microsoft excel used to 
search for value in the first column of a table or range and then return a value in the same 
for specified column. It is one of the most used functions for data lookup and retrieval 
tasks in excel.
=vlookup (lookup_value, table_array, col_index_num, [range_lookup]) 

# Data Retrieval  
• Can be done within a sheet 
• Between different sheets 
• Between different workbook

# Possible errors that can occur 
1. #REF: - if function’s col_index_num is larger than the number of column in 
table_array. 
2. #Value: - if functions col_index_num is less than 1. Vlookup function will return a 
#value! Error 
3. #N/A: - if input false for range_lookup parameter and no exact match can be found. 
Vlookup function returns #N/A error.

For EXACT MATCH (False) vlookup value must exactly exist in the first column of the table. 
For APPROXIMATE MATCH(TRUE) the first column must be sorted in ascending order, and 
formula will return the closest match less than or equal to the lookup value

...................................................................................................................................................
# HLOOKUP (Horizontal Lookup) 
It stands for Horizontal lookup and can be used to retrieve information from a table by 
searching a row for the matching data and outputting from the corresponding column. 
= Hookup (lookup_value, table_array, row_index_num, [range_value])


...................................................................................................................................................
# INDEX-MATCH 
Unlikely vlookup and hlookup, which are limited to vertical and horizontal searches 
respectively. Index-match provides the flexibility to perform both the vertical and 
horizontal lookup. 
=INDEX () returns the value of a cell in a table based on the column and row number. 
=Match () returns the position of a cell in a row or column.
