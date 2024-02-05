import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

df=pd.read_csv('auto-mpg.csv')

df.head()

df.groupby('origin').cylinders.value_counts()

origin_cyl = (
    df
    .groupby('origin')
    .cylinders
    .value_counts()
    .unstack()
    .fillna(0)
)

sns.heatmap(origin_cyl, cmap="RdBu", annot=True);
#sns.heatmap(df.corr())
