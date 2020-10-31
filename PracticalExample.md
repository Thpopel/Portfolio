```python
import pandas as pd

#Rating Dalhousie neuroscience courses out of 10
compare_course_ratings = {'overall_Rating': [10,7,6,5], 'overall_Fun': [10, 5, 5, 2], 'overall_Atmosphere': [10, 5, 4, 1]}
df = pd.DataFrame(compare_course_ratings)

df.index = ['NESC3505','NESC9999','NESC8888','NESC7777']

print (df.iloc[0:3])
```

              overall_Rating  overall_Fun  overall_Atmosphere
    NESC3505              10           10                  10
    NESC9999               7            5                   5
    NESC8888               6            5                   4



```python

```
