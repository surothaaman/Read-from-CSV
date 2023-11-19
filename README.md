# Read-from-CSV

## AIM:
To write a python program for reading the csv file content

## ALGORITHM:
Step 1:
load the csv into dataframe.

Step 2:
print the number of contents to be displayed using df.head().

Step 3:
The number of rows returned is defined in pandas option settings.

Step 4:
Check your system's maximum coloumn with the pd.options.max_coloumn statement.

Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
'''
Developed by: SUROTHAAMAN R
Register Number: 212222103003
'''
import pandas as pd
df = pd.read_csv("data.csv")
print(df.head(10))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/surothaaman/Read-from-CSV/assets/133313653/29efc8b2-e2b7-402e-a78d-baecfc585e00)

## RESULT:
Thus the program is written to read the csv file
