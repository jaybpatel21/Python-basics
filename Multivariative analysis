import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

df=sns.load_dataset('mpg')

x=df['acceleration']
y=df['horsepower']
ori=df['origin']
sns.scatterplot(x=x,y=y,hue=ori,style=ori, markers=['o','*','s'],size=ori,sizes=[50,100,150])
plt.title('acceleration vs horsepower')
plt.grid(True)
plt.legend(title='origin')
plt.show()
