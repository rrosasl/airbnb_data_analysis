# Analyzing Airbnb Boston data - What moves prices?

# Overview
Hello world! Have you ever stayed in an airbnb? What factors are associated with the prices?
If you go to Boston, what neighborhoods are more expensive?  If yo're curious about this, this is your repo.

Look at my medium [post](https://medium.com/@rrosasl/why-are-you-paying-so-much-for-that-boston-airbnb-a-look-at-the-data-7714b56aa72e)

# Motivation
Working with large datasets is a crucial part of any aspiring data scientist's journet. I'm doing this project within the context of my Udacity Data Science Nanodegree using data from Kaggle. 

# Data Sources
We found this data gold mine from Kaggle [link](https://www.kaggle.com/airbnb/boston) 

From their own description: 
The following Airbnb activity is included in this Boston dataset: * Listings, including full descriptions and average review score * Reviews, including unique id for each reviewer and detailed comments * Calendar, including listing id and the price and availability for that day

# Installations
I used Python 3.0
some of the libraries I used:

```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn import preprocessing as p
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score, mean_squared_error
```

# Files
- Jupyter Notebook: Boston Airbnb_DSND_rosas.ipynb
- listings.csv
- reviews.csv
- calendar.csv

# Questions and Process
> How do price vary in the different neighborhoods? 

> What elements are correleated with price?

> What's the impact on price of for example, # guests to accomodate, number of ratings, rating, etc?


# Acknowledgements

Thanks Udacity and Stackoverflow :)
