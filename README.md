# Read-from-CSV
### Name: Anbuselvan.S
### Reference No: 23005959
## AIM:
To Write a program to read a csv file.
## ALGORITHM:
### Step 1:
Import pandas module as pd
### Step 2:
Read a csv file
### Step 3:
Print the first five rows and last five rows
### Step 4:
Print the length of the rows and columns
### Step 5:
End the program
## PROGRAM:
```
# Write a program to read a csv file
# Developed by : AARON I
# Reference no : 23002289

from google.colab import drive
drive.mount('/content/drive')

import pandas as pd
df=pd.read_csv('/content/drive/My Drive/cars (1) (7).csv')
print(df.head())
print(df.tail())
print("Rows",len(df.axes[0]))
print("Columns",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/anbuselvan1519/Read-from-CSV/assets/139841744/e68980d1-1ddc-42c6-a269-93cde9d385ae)
![image](https://github.com/anbuselvan1519/Read-from-CSV/assets/139841744/b2fceecd-7065-4a29-98ab-ebc7557a8614)

## RESULT:
Thus the program is written to read a csv file.
