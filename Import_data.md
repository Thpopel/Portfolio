```python
import pandas as pd
import numpy as np

df = pd.read_csv('vgsales.csv')
print(df.head)

```

    <bound method NDFrame.head of         Rank                                              Name Platform  \
    0          1                                        Wii Sports      Wii   
    1          2                                 Super Mario Bros.      NES   
    2          3                                    Mario Kart Wii      Wii   
    3          4                                 Wii Sports Resort      Wii   
    4          5                          Pokemon Red/Pokemon Blue       GB   
    ...      ...                                               ...      ...   
    16593  16596                Woody Woodpecker in Crazy Castle 5      GBA   
    16594  16597                     Men in Black II: Alien Escape       GC   
    16595  16598  SCORE International Baja 1000: The Official Game      PS2   
    16596  16599                                        Know How 2       DS   
    16597  16600                                  Spirits & Spells      GBA   
    
             Year         Genre   Publisher  NA_Sales  EU_Sales  JP_Sales  \
    0      2006.0        Sports    Nintendo     41.49     29.02      3.77   
    1      1985.0      Platform    Nintendo     29.08      3.58      6.81   
    2      2008.0        Racing    Nintendo     15.85     12.88      3.79   
    3      2009.0        Sports    Nintendo     15.75     11.01      3.28   
    4      1996.0  Role-Playing    Nintendo     11.27      8.89     10.22   
    ...       ...           ...         ...       ...       ...       ...   
    16593  2002.0      Platform       Kemco      0.01      0.00      0.00   
    16594  2003.0       Shooter  Infogrames      0.01      0.00      0.00   
    16595  2008.0        Racing  Activision      0.00      0.00      0.00   
    16596  2010.0        Puzzle    7G//AMES      0.00      0.01      0.00   
    16597  2003.0      Platform     Wanadoo      0.01      0.00      0.00   
    
           Other_Sales  Global_Sales  
    0             8.46         82.74  
    1             0.77         40.24  
    2             3.31         35.82  
    3             2.96         33.00  
    4             1.00         31.37  
    ...            ...           ...  
    16593         0.00          0.01  
    16594         0.00          0.01  
    16595         0.00          0.01  
    16596         0.00          0.01  
    16597         0.00          0.01  
    
    [16598 rows x 11 columns]>



```python

```
