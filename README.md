# Big-Data-Analysis-Engineer-Practical-Exam

## 사분위수 IQR
 ```sql
Q1 = df[컬럼명].quantile(.25)
Q3 = df[컬럼명].quantile(.75)
IQR = Q3 - Q1
```
## 소수점 구하기
 ```sql
import numpy as np
df[df[컬럼명] - np.floor(df[컬럼명]) != 0]
```
