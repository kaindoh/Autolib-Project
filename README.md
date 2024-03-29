# Autolib-Project

# Problem statement

To work as a Data Scientist for the Autolib electric car-sharing service company to investigate a claim about the blue cars from the Autolib dataset on either weekday or weekend.

# Creating Hypothesis

H0:The BlueCar Are Most Active On Friday More Than Monday 

H1:The BlueCar Are Not Most Active On Friday More Than Monday

# Importing libaries and Loading the datasets

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from scipy import stats
from statsmodels.stats import weightstats
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import confusion_matrix,accuracy_score
from sklearn.naive_bayes import GaussianNB

# Data Understanding

it has 'Postal code', 'date', 'n_daily_data_points', 'dayOfWeek', 'day_type','BlueCars_taken_sum', 'BlueCars_returned_sum', 'Utilib_taken_sum',
'Utilib_returned_sum', 'Utilib_14_taken_sum', 'Utilib_14_returned_sum',
'Slots_freed_sum', 'Slots_taken_sum' columns

It has 4645 rows
     
# Data Cleaning

Checking for:
  Duplicates
  Missing values
  
Making the column names uniform 

filtering the data to weekday only 

getting labels for days of the week

Checking for outliers

# Data Visualization 
Checking for varibles that correlate uasing scatter plot and heatmap

checking for the frequency of variables using bar graph pie chart and histogram

# Use of sampling techniques
 
 simple random sampling 
 
 stratified random sampling
 
 # Probabilities
 
  using poisson to find probabilities of an event
  
  using bayesian to find conditional probabilities
  
 # Testing The significance of a test
 
 Tested normality using qqlot and histograms
 
 using z_test to check for significance of the hypothesis
 
 # Challenging the solution
 
 Testing hypothesis using utilib  and utilib 14 
 
 # Conclusion
 
From the above analysis we conclude that usage of bluecars is more on Friday more than Monday
 
  

     
