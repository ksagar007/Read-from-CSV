# Read-from-CSV

## AIM:
write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output.
## PROGRAM:
```
DEVELOPED BY : Athmaj Venugopal
REGISTER NUMBER : 22007603
'''
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))
```
## OUTPUT:
![readcsv](https://user-images.githubusercontent.com/121165786/214787791-83daaa9f-84f6-40f3-86d1-90f6cd8ab10b.png)

## RESULT:
A python program to read data from CSV files has been created successfully.
