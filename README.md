# Video_Game_Sales
## Sales Analysis and building model to predict Sales of Video Games


# Import Libraries
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
from sklearn.ensemble import RandomForestRegressor
from scipy import stats
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score

df=pd.read_csv("C:/Users/USER/OneDrive/Documents/vgsales.csv")
df.shape

df.describe()
df=df.dropna()

df.describe()
