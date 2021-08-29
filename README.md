# Linear-Multilinear-and-Polynomial-Regression-with-Python
Steps: </br>
1. collection of data: we load the data into a dataset </br>
2. preprocessing: checking if there are any null readings </br>
3. analysing: analysing the data (plot the data graph) </br>
4. training </br>
5. testing </br>


Main library used: </br>
``` Python
# Import cell
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import r2_score
import seaborn as sns
from sklearn.compose import ColumnTransformer
from sklearn.preprocessing import OneHotEncoder
from sklearn.pipeline import Pipeline
import joblib 
import pickle 
from sklearn.preprocessing import PolynomialFeatures
```
numpy </br>
pandas </br>
matplotlib </br>
sklearn </br>
seaborn </br>

