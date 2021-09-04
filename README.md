# DataFrame
Creating DataFrame 

from pandas import DataFrame
dic1={"Name":["harsh","rahul","anil","priya"],"Age":[28,19,18,10],"Percent":[75,81,89,73]}
df1=DataFrame(dic1)
df1

Name	Age	Percent
0	harsh	28	75
1	rahul	19	81
2	anil	18	89
3	priya	10	73

df1["Age"]

0    28
1    19
2    18
3    10
Name: Age, dtype: int64
