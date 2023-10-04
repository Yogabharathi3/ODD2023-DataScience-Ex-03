# ODD2023-DataScience
# Ex-03 Univariate Analysis
# Aim:
To read the given data and perform the univariate analysis with different types of plots.

# Explanation:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Algorithm:
# Step1:
Read the given data.

# Step2:
Get the information about the data.

# Step3:
Remove the null values from the data.

# Step4:
Mention the datatypes from the data.

# Step5:
Count the values from the data.

# Step6:
Do plots like boxplots,countplot,distribution plot,histogram plot.

# Program:
DEVELOPED BY : YOGABHARATHI S

REGISTER NO : 212222230179
```
import pandas as pd
import numpy as np
import seaborn as sns

df=pd.read_csv('superstore.csv')
df

df.head()
df.info()
df.describe()
df.isnull().sum()

df.dtypes

df['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=df)
sns.countplot(x='Postal Code',data=df)
sns.distplot(df["Postal Code"])
sns.histplot(x='Postal Code',data=df)
```
# OUTPUT:
# Dataset:
![image](https://github.com/Yogabharathi3/ODD2023-DataScience-Ex-03/assets/118899387/dab07356-02d3-482c-925d-f71090f0c8e5)

# Head:
![image](https://github.com/Yogabharathi3/ODD2023-DataScience-Ex-03/assets/118899387/c4bb4ae5-4e51-4b9a-a5f0-b3014cb648ec)

# Info:
![image](https://github.com/Yogabharathi3/ODD2023-DataScience-Ex-03/assets/118899387/6199aaf4-0268-4535-b4c4-3a6ef42b9141)

# Describe:
![image](https://github.com/Yogabharathi3/ODD2023-DataScience-Ex-03/assets/118899387/ae5c0f59-20eb-4944-af48-1dd2e95b9072)

# Isnull:
![image](https://github.com/Yogabharathi3/ODD2023-DataScience-Ex-03/assets/118899387/a5a98935-3097-4af6-8003-ac9d510c8fc2)

# dtypes:
![image](https://github.com/Yogabharathi3/ODD2023-DataScience-Ex-03/assets/118899387/49c3e822-cc10-4006-9bf1-67b01ac6456f)

# Valuecount:
![image](https://github.com/Yogabharathi3/ODD2023-DataScience-Ex-03/assets/118899387/04e3240c-4cad-4560-81f5-da78765ee284)

# Boxplot:
![image](https://github.com/Yogabharathi3/ODD2023-DataScience-Ex-03/assets/118899387/44f74bb3-d204-4f6a-8cb8-66405adad5a1)

# Countplot:
![image](https://github.com/Yogabharathi3/ODD2023-DataScience-Ex-03/assets/118899387/fd880d66-572b-4ee2-9076-f87314fb9b16)

# Distribution plot:
![image](https://github.com/Yogabharathi3/ODD2023-DataScience-Ex-03/assets/118899387/2b383bc1-a9cd-4daf-90ba-94123fbe416b)

# Histogram plot:
![image](https://github.com/Yogabharathi3/ODD2023-DataScience-Ex-03/assets/118899387/07e83a45-f8f1-4378-a4a0-f2c37a44d935)

# Result:
Thus we have read the given data and performed the univariate analysis with different types of plots.
