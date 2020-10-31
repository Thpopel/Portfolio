```python
import pandas as pd
import numpy as np

df = pd.read_csv('vgsales.csv')

df_platform = df[(df['Platform'] == 'Wii') | (df['Platform'] == 'PS3') | (df['Platform'] == 'X360')]

wiiFocus = df_platform[df_platform['Platform'] == 'Wii'].Global_Sales.sum()
ps3Focus = df_platform[df_platform['Platform'] == 'PS3'].Global_Sales.sum()
xbox360Focus = df_platform[df_platform['Platform'] == 'X360'].Global_Sales.sum()

total = wiiFocus + ps3Focus + xbox360Focus

wiiPercent = wiiFocus / total
ps3Percent = ps3Focus / total
xbox360Percent = xbox360Focus / total

print(wiiFocus)
print(ps3Focus)
print(xbox360Focus)

print(wiiPercent)
print(ps3Percent)
print(xbox360Percent)

```

    926.71
    957.84
    979.96
    0.3235143183301856
    0.33438179653762773
    0.34210388513218665



```python

```


```python

```
