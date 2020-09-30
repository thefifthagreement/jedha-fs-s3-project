# Classification project 

## _Dealing with imbalanced dataset_

> Jedha Data Science Bootcamp - Fullstack - week 3
<br>
> _Session dsmft-paris-08_

Since the notebook uses the `plotly` library which is not supported by Github, you can follow this **[nbviewer](https://nbviewer.jupyter.org/github/thefifthagreement/jedha-fs-s3-project/blob/master/conversion_rate.ipynb)** link to view it.

# Conversion Rate Challenge

## Main goal

Optimizing the customers conversion rate is one of the most important task of a data scientist.

To achieve this goal, I aim to build a model to predict the conversion rate of the customers of a web site and make some recommandations to the marketing team in order to increase the incomes.

## Description of the challenge

We got data about the website users of an _anonymous_ company. The project consists in:

1. Buiding a model to predict the conversion rate (will the user buy or not ?

2. Making some recommendations to the Product & Markting team in order to increase this rate

## Imbalanced dataset

Since the target classes are imbalanced, we can use some of available technics to adress the problem:

* oversampling: duplicate examples of the minority class or generate synthetic examples using the `imbalance_learn` library
* downsampling: reduce the number of examples of the majority class
* mixing downsampling and oversampling to benefit from both
* class weigths: calculate the weigths of the classes and incorporate them to the cost function for the model training