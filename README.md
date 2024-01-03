# Read-from-CSV

## AIM:
to write a python program for reading a content from a csv file

## ALGORITHM:
### Step 1:
import pandas as pd
### Step 2:
Read the csv file using read_ csv method
### Step 3:
Use head and tail method to get required content from the file
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
print the output

## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by:  SAI GURU CHANDRAN
#Register Number: 23014037

import pandas as pd
df = pd.read_csv('sri.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![WhatsApp Image 2024-01-02 at 23 14 37_7bd58ab8](https://github.com/Saiguruchandran/Read-from-CSV/assets/144870946/f40422aa-e180-4027-99e8-d6019c212d3a)

## RESULT:
Thus the program is written to copy the contents from one file to another file
