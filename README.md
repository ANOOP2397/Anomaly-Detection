# Anomaly-Detection
import pandas as pd
data = pd.read_csv('01.csv')
data.head()

import pandas as pd
data = pd.read_csv('01.csv')
data.head()

import pandas as pd
df=pd.read_csv("01.csv",delimiter=";")
df['CPU usage [%]']=df['CPU usage [%]'].str.replace(",",".")
df['CPU usage [%]']=df['CPU usage [%]'].astype(float)

df['Memory usage [%]']=df['Memory usage [%]'].str.replace(",",".")
df['Memory usage [%]']=df['Memory usage [%]'].astype(float)

df.head(5)
