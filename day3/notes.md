# AI Fellowship Day2
----
## Topic :- Pandas

# Notes
_______
## Pandas Data-structures
* Series
* Dataframes
* panel
______


### 1. Series
* series is used to create labeled data just like dict in pandas it  can take lists, arrays (numpy) and turn them into series data types
* __ser[label]__ returns the data stored under that label
* __ser1+ ser2__  adds the position of the label in both series

### 2. Dataframes
* Dataframe is the table with labeled columns and rows and automatically generated index columns
* __pd.DataFrame(data,column=col_label_list,index=row_label_list,dtype=datatype)__ can be used to manually create a DataFrame in pandas
* a missing data in the dataframe is denoted by N/A
    #### Sql syntax
    * sql specific commands like drop can be used with the dataframes
    * 