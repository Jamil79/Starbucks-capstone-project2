# Starbucks-capstone-project2
Data are related to an advertisement done by Starbucks on a mobile app. Data is simulated. Offers are sent each few days on the mobile app. It is advertisement for a drink. Advertisemrnt can be Bogo, buy 1 get 1 free or Discount a discount on purchase.

Not all users receive the same offer, the challenge to solve.

libraries used:

import pandas as pd

import numpy as np

import math

import json

from datetime import datetime

from time import time

import matplotlib.pyplot as plt

from sklearn.ensemble import AdaBoostClassifier

from sklearn.metrics import accuracy_score,f1_score

from sklearn.model_selection import train_test_split,GridSearchCV

from sklearn.neighbors import KNeighborsClassifier

from sklearn.tree import DecisionTreeClassifier

This project is done as the capstone project for the Data Science nano-degree with Udacity.

Conclusion:

The best targeted bracket of respondants for the advertisement are people above 60 years, prefered Female and with income exceeding 60000 USD. The Discount advertisement succeded better than the Bogo advertisement and we have a model that can predict if advertisements succeeded with a completion according to all the demographic and economics inputs of the provided datasets.

A blog was created related to this project that explain the details here:
https://5f7845c463937.site123.me/

License I hereby put at the disposal of everyone the use of this program for free.
