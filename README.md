# Data_wranglling
The code contains a function called "data_wranglling_info" which will generate basic details:
1. No of variables or features.
2. Datatype of all the variables.
3. Number of Nan in each variable and its bargraph plot.
4. Any empty column.

Code to use the fucntion.

import pandas as pd

import matplotlib.pyplot as plt

import numpy as np

data = pd.read_csv(r"Path of dataset file")

data_wranglling_info(data)

