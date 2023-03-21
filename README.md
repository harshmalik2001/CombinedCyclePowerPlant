Combined Cycle Power Plant Energy Prediction using Regression Techniques
This repository contains code and data to predict the net hourly electrical energy output of a Combined Cycle Power Plant (CCPP) using regression techniques in machine learning. The CCPP dataset is obtained from the UCI Machine Learning Repository [1].

Dataset
The dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011). It consists of 4 independent variables (AT, V, AP, RH) and 1 dependent variable (PE). The variables represent the following:

AT (Ambient Temperature) in Celsius
V (Exhaust Vacuum) in cm Hg
AP (Ambient Pressure) in millibar
RH (Relative Humidity) in %
PE (Net Hourly Electrical Energy Output) in MW
The dataset is split into a training set (80%) and a test set (20%) for evaluating the performance of the regression models.

Requirements
Python 3.7 or later
scikit-learn
numpy
pandas
matplotlib
