# Read-from-CSV

## AIM:

## ALGORITHM:
```
Step 1:
Import pandas as pd.

Step 2:
Read the CSV file using read_csv method.

Step 3:
Use head and tail method to get the required contents from the file.

Step 4:
Use len() method to get the number of rows and columns.

Step 5:
Print the output.
```

## PROGRAM
```
Developed by: Suji.G
Register Number: 22008563

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![b11](https://user-images.githubusercontent.com/119559822/214855317-9de70756-6759-4f06-86e0-0bcd28f36694.png)
![b2](https://user-images.githubusercontent.com/119559822/214855346-ca39e600-03ce-455e-b2be-ad8cf6751f75.png)


## RESULT:
