# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
NAME: LISIANA T
REG NO :212222240053
```
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import os
for dirname, _, filenames in os.walk('../input/world-population'):
    for filename in filenames:
        print(os.path.join(dirname, filename))

pop = pd.read_csv('/content/World Population.csv')

data.head(10)

pop.dtypes

pop.head(3)

pop.tail(3)

pop['Population'].mean()

+df["Percentage"] = df["Percentage"].str.rstrip('%').astype(float)

x=data['Rank']
y=data['Percentage']
plt.xlabel('rank')
plt.ylabel('percentage')
plt.plot(x,y)


```
# OUTPUT:


![image](https://github.com/user-attachments/assets/33e5fb5f-541f-4f10-917e-e1fb0a25370a)




# RESULT:
Thus we have created the python code for plotting the time series of given data.
