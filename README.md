# Data-Analysis-Template
This repository contains code snippets from my Data Sciencework

## 1. Installing Package 

pip install pandas
pip install xlrd # Excel file 

%matplotlib inline - Keeping charts inline in notebook

## 2. Analysis Commands

df.shape :- rows and columns
df.describe() :- descriptive stats of table
df.column_name.unique() :- It gives unique values

Array to List:
1. .tolist()
2. list(column)

Length of array/list:
1. len(array)
2. array.nunique()

Value_counts()
1. Applicable on: object/character
2. Returns unique values and frequency of categories
3. Can be done by: groupby

Groupby:

df[[column_names]].groupby(by = ['group_by_column','second_grp_colmn']).sum()/mean()/count()

loc format:

1. df.loc[rows,columns]
2. df.loc[:,:] :- all rows and all columns
3. df.loc[row level condition,[column list]] :- row level condition: <, >, == conditions of columns
