## Huawei project 2016

description: The data is of users' using 4G to watch videos from the basestation side. This means that we only have some statistical data
from the basestation. Not detailed data of each user. We want to use these data to predict 3 main indexes which are avg download speed, avg
stall time before start playing and stalls during video playing. The project is seperated into 3 sub-projects: data cleaning, feature 
selection and predicting. I am in charge of the 3rd part and lead a team of 3.

data: classified. Accuracy defined as: |y_pre-y_true|/y_true <= 0.2

techniques: use data distribution for cleaning(only on training, log distribtion, box-cox); use GBDT and RF for basic prediction; use stacking
for further learning.

language: R

basic contribution: aforementioned parts; increase the prediction accuracy from 75 to 92.

