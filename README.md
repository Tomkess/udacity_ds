# Airbnb Project Overview
The folder containing the exercises from udacity nanodegree program.

# Just another topic about Airbnb - Demand Prediction for price optimization?

## Requirements:

The project uses well known modules.

import pandas as pd

import glob

import itertools

import zipfile

import numpy as np

import matplotlib.pyplot

import seaborn

import math

from matplotlib.dates import DateFormatter

import plotly.express as px

from sklearn.impute import KNNImputer

from sklearn_pandas import CategoricalImputer

from datetime import datetime, timedelta

from xgboost import plot_importance

## Introduction
Shared economy is currently on the increasing trajectory - new business models, new technologies and big hyhpe surrounded it. Since there is a lot of boom around, there is also a demand for newer insights that might be helpful. In this project I focused on creating something new, i.e something beyond price forecasting.

## Summary
In the concept presented, the analysis aims to create some tool for owners within Airbnb that might be used as an optimization platform for their profit maximization.

- set up demand function as a proxy from total numebr of reviews
- build predictive model that forecasts the demand
- select variables as a inputs to a optimization (depending on the business use case)
- run optimization to select optimal pricing decisions

## Typical Set up
As a owner of the place I want to decide between two availability schemas - the owner sees that making a place available daily costs too much effort for him. Either, owner will make place available during weekends only, or during the first two weeks of a month. For both scenarios, as a owner, I would like to have a possibility to decide about the optimal price that would maximize my profit - based on the forecasted demand.
