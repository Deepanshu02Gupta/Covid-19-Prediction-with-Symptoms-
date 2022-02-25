## Covid-19-Prediction-with-Symptoms

Dataset Attributes:
1) Test_date
2) Cough
3) Fever
4) Sore_throat
5) Shortness_of_breath
6) Head_ache
7) Corona_result
8) Age_60_and_above
9) Gender
10)Test_indication

# Importing Libraries:
  a)  Basic libraries 
import pandas as pd 
import numpy as np
  b) Visualisation Libraries
import seaborn as sns
import matplotlib.pyplot as plt
import matplotlib.ticker as ticker
  c) Datetime Library
from datetime import datetime
  d) Sklearn Libraries: For standardize, Encoding, models, PCA, accuracy.
from sklearn.preprocessing import StandardScaler , Normalizer
from sklearn.preprocessing import LabelEncoder, OneHotEncoder
from sklearn.metrics import confusion_matrix,accuracy_score,f1_score
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn import metrics
import warnings
warnings.filterwarnings('ignore')
%matplotlib inline
  e) Scipy libraries: For statistical inferences
from scipy.stats import norm  /* statistics */
from scipy import stats 

# Importing Dataset

# Exploratory Data Analysis
  1) Check for missing values and remove if not significantly large.

  2) Creating Dummy variables and applying One-Hot encoding 

  3) Check for correlation between variables and visualization to get insights from the data.

  4) Appling dimensionality reduction method: PCA and select n components with >80% variance explained.

  5) Splitting dataset into Train/Test.

  6) Run Random Forest classifier.

  7) Check for accuracy.
  
  8) Applying K-Nearest neighbours for binary classfication (Covid positive/negative).

  9) Plotting AUC/ROC curve: It is a graphical plot that illustrates the diagnostic ability of a binary classifier system as its discrimination threshold is varied

  10) Apply _SelectKBest_ module to get the most important features from the dataset.

Final conclusion and insights. 
