Read-from-CSV
### AIM:
To write the python program to read the csv file content

### ALGORITHM:
Step 1:
Load the CSV into a data frame

Step 2:
Print the number of contents to be displayed using df.head()

Step 3:
The number of rows returned is defined in Pandas option settings

Step 4:
Check your systems maximum column with the pd.options display.max_column statement

Step 5:
Increase the maximum number of rows to display the entire Dataframe

## PROGRAM:
~~~
import pandas as pd

df = pd.read_csv('data.csv')

print(df.head(10))

print(df.tail())

print("No of rows",len(df.axes[0]))

print("No of columns",len(df.axes[1]))
~~~
## OUTPUT:
<img width="917" alt="collab" src="https://user-images.githubusercontent.com/94836154/154624854-476d6692-d9fd-4482-84ee-9d5b632fd4d2.png">


## RESULT:Thus the program is written to read the CSV
