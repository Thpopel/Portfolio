```python
import pandas as pd
import numpy as np
from matplotlib import pyplot as plt

df = pd.read_csv('vgsales.csv')

df_platform = df[(df['Platform'] == 'Wii') | (df['Platform'] == 'PS3') | (df['Platform'] == 'X360')]

wiiFocus = df_platform[df_platform['Platform'] == 'Wii'].Global_Sales.sum()
ps3Focus = df_platform[df_platform['Platform'] == 'PS3'].Global_Sales.sum()
xbox360Focus = df_platform[df_platform['Platform'] == 'X360'].Global_Sales.sum()

plt.pie(
   df_platform.groupby('Platform').Global_Sales.sum(),
   labels=df_platform.groupby('Platform').Global_Sales.sum().index, autopct='%.1f%%')
plt.title('Platforms by global sales')

plt.plot


```




    Text(0.5, 1.0, 'Platforms by global sales')






    
![png](Portfolio%20work_files/Portfolio%20work_0_1.png)
    




```python

```


```python

```
