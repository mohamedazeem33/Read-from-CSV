# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_CSV method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output.

## PROGRAM:
```python
# program for reading content from a CSV file
#Developed by : MOHAMED AZEEM N
#reference : 22007405

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns: len(df.axes[1]))
```
## OUTPUT:


![python exp 6](https://user-images.githubusercontent.com/121040764/214801266-20ac4239-1ce7-45a4-b0fe-0168f27ba0da.jpg)


## RESULT:
thus the python program is written to read the contents of a CSV file.
