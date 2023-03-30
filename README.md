# Ex03-Univariate-Analysis

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

DEVELOPED BY : SHARANGINI T K

REG NO : 212222230143
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
# Output:

# Dataset:
![image](https://user-images.githubusercontent.com/113497104/228862536-1a0ec10d-9073-4f23-b195-6089b7863eb1.png)

# Head:
![image](https://user-images.githubusercontent.com/113497104/228862741-569e31f3-8099-4651-bd47-649da64ea89e.png)

# Info:
![image](https://user-images.githubusercontent.com/113497104/228862903-e4b36fbb-96d5-4204-9749-8c962d69d7a7.png)

# Describe:
![image](https://user-images.githubusercontent.com/113497104/228863087-5bdf205a-2e22-406c-8eca-8b9deaeeddd1.png)

# Isnull:
![image](https://user-images.githubusercontent.com/113497104/228863209-4d6210bc-3596-4ae8-96a5-1ff0f8a18d53.png)

# Dtypes:
![image](https://user-images.githubusercontent.com/113497104/228863350-7539b7ce-f3c4-4a22-a70f-0edc1e142dc5.png)

# Valuecount:
![image](https://user-images.githubusercontent.com/113497104/228863491-ead7e47e-9444-4d5a-8cf7-0d157824bc8e.png)

# Boxplot:
![image](https://user-images.githubusercontent.com/113497104/228863603-164ffe73-e1a1-42de-86f9-553c669dd69c.png)

# Countplot:
![image](https://user-images.githubusercontent.com/113497104/228863701-d2167ce9-7f24-47b4-a506-15d0c7587453.png)

# Distribution plot:
![image](https://user-images.githubusercontent.com/113497104/228863801-7c29258c-ec86-4dcf-8b11-72209c3ded03.png)

# Histogram plot:
![image](https://user-images.githubusercontent.com/113497104/228863916-bf66c71e-48ab-4f3a-88f9-f18752e0460b.png)

# Result:
Thus we have read the given data and performed the univariate analysis with different types of plots.

