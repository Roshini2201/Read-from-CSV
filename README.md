# Read-from-CSV

## AIM:
To write a python program for reading content from a csv file
## ALGORITHM:

### Step 1:
Import pandas as pd
### Step 2:
Read the csv file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output

## PROGRAM:
```
#developed by : ROSHINI S
#Register number : 212223240142

import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail(5))
print("Number of rows: ",len(df.axes[0]))
print("Number of columns: ",len(df.axes[1]))
```
## OUTPUT:  

![Screenshot 2024-05-10 203651](https://github.com/Roshini2201/Read-from-CSV/assets/154105318/650761bf-7b7a-4c08-bdb7-03480dfc0c7c)

## RESULT:
Thus a python program is written to read the contents of a csv file.
