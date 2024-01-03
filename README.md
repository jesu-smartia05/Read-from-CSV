# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output.
## PROGRAM:
```
Developed by: JESU SMARTIA A
Register Number: 212223110016

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:

![Screenshot 2024-01-03 135723](https://github.com/jesu-smartia05/Read-from-CSV/assets/148514819/6946725a-d15c-480d-9122-b8a47441d8bf)

## RESULT:
Thus a python program is written to read the contents of a CSV file
