```python
import pandas as pd
import numpy as np

df = pd.read_csv('vgsales.csv')

df_platform = df[(df['Platform'] == 'Wii') | (df['Platform'] == 'PS3') | (df['Platform'] == 'X360')]

print(df_platform)

```

            Rank                                               Name Platform  \
    0          1                                         Wii Sports      Wii   
    2          3                                     Mario Kart Wii      Wii   
    3          4                                  Wii Sports Resort      Wii   
    7          8                                           Wii Play      Wii   
    8          9                          New Super Mario Bros. Wii      Wii   
    ...      ...                                                ...      ...   
    16552  16555           Mahou Sensei Negima!? Neo-Pactio Fight!!      Wii   
    16553  16556                                     Bound By Flame     X360   
    16573  16576                                Mini Desktop Racing      Wii   
    16574  16577  Yattaman Wii: BikkuriDokkiri Machine de Mou Ra...      Wii   
    16581  16584                                          Fit & Fun      Wii   
    
             Year         Genre              Publisher  NA_Sales  EU_Sales  \
    0      2006.0        Sports               Nintendo     41.49     29.02   
    2      2008.0        Racing               Nintendo     15.85     12.88   
    3      2009.0        Sports               Nintendo     15.75     11.01   
    7      2006.0          Misc               Nintendo     14.03      9.20   
    8      2009.0      Platform               Nintendo     14.59      7.06   
    ...       ...           ...                    ...       ...       ...   
    16552  2007.0      Fighting  Marvelous Interactive      0.00      0.00   
    16553  2014.0  Role-Playing                    NaN      0.00      0.01   
    16573  2007.0        Racing         Popcorn Arcade      0.01      0.00   
    16574  2008.0        Racing            Takara Tomy      0.00      0.00   
    16581  2011.0        Sports                Unknown      0.00      0.01   
    
           JP_Sales  Other_Sales  Global_Sales  
    0          3.77         8.46         82.74  
    2          3.79         3.31         35.82  
    3          3.28         2.96         33.00  
    7          2.93         2.85         29.02  
    8          4.70         2.26         28.62  
    ...         ...          ...           ...  
    16552      0.01         0.00          0.01  
    16553      0.00         0.00          0.01  
    16573      0.00         0.00          0.01  
    16574      0.01         0.00          0.01  
    16581      0.00         0.00          0.01  
    
    [3919 rows x 11 columns]



```python

```
