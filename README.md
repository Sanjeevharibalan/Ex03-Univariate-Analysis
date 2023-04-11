# Ex03-Univariate-Analysis

# AIM:
   
   To Perform  Univariate Analysis on the given data
           
# ALGORITHM:
 
    1. Read the given data 
    2.Get information from the data 
    3.Perform the Univariate Analysis
    4.Save the clean data to file
    
# PROGRAM:

import pandas as pd

import numpy as np

import seaborn as sns

import matplotlib as plt

df = pd.read_csv("/content/SuperStore.csv")

df.info()



df.dtypes



df['Sales'].value_counts()

df.describe()



BOX PLOT:

PROGRAM :

sns.boxplot(x="Postal Code", data=df)



COUNT PLOT:

PROGRAM :

sns.countplot(x="Postal Code", data=df)



DIST PLOT:

PROGRAM :

sns.distplot(df["Postal Code"])



HIST PLOT:

PROGRAM :

sns.histplot(x="Postal Code", data=df)



SKEW

PROGRAM :

df.skew()

sns.histplot(x="Postal Code", data = df)

sns.displot(x="Postal Code", data = df)



KURTOSIS

PROGRAM:

df.kurtosis()

sns.boxplot(x="Postal Code", data = df)



# OUTPUT

![image](https://user-images.githubusercontent.com/86832944/192602420-54da5415-eca9-4ba6-89d4-58c83f4a621e.png)
![image](https://user-images.githubusercontent.com/86832944/192602987-e6f6e7d2-0539-4d09-b033-751f09d230b6.png)
![image](https://user-images.githubusercontent.com/86832944/192603363-10aeaf52-b7dc-4be3-80ac-f23e47235f8f.png)
![image](https://user-images.githubusercontent.com/86832944/192603693-6866557e-2f0c-47c0-96ae-4d36775cebed.png)
![image](https://user-images.githubusercontent.com/86832944/192603994-9ada659f-6b28-45d0-a511-a879cc36bf15.png)
![image](https://user-images.githubusercontent.com/86832944/192604219-e1aa8344-e46d-40df-90d9-ee025bf72377.png)
![image](https://user-images.githubusercontent.com/86832944/192604528-fa3c8548-780f-4ac0-a485-97e9770972f8.png)
![image](https://user-images.githubusercontent.com/86832944/192604942-37667f12-bc2d-4fd1-96d3-ac439038259d.png)
![image](https://user-images.githubusercontent.com/86832944/192605217-aec87406-f2c8-4957-9dee-077951aa6716.png)
![image](https://user-images.githubusercontent.com/86832944/192605564-cd777d74-3f66-46fe-b4be-8e09ed534076.png)

# RESULT:
     
     Thus, Univariate Analysis is performed on given data and saved successfully.


