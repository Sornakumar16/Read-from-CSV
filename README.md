# Read-from-CSV

## AIM:

## ALGORITHM:
## Step 1:
Load the CSV into a DataFrame.

## Step 2:
Print the number of contents to be displayed using df.head().

## Step 3:
The number of rows returned is defined in Pandas option settings.

## Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

## Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
~~~
To write a python program for reading content from a CSV file.
Developed by: SORNA KUMAR S
Register Number: 21222123230210
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
~~~

## OUTPUT:
![image](https://github.com/Sornakumar16/Read-from-CSV/assets/138849327/68f9ad02-134f-4837-a2a6-1ebc3fcdd038)
![image](https://github.com/Sornakumar16/Read-from-CSV/assets/138849327/8a1a0e50-618c-4af6-bb1e-e55e2f61836f)


## RESULT:
