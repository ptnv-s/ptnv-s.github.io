---
title: Project
layout: page
---
##Abstract
Various countries have different socio-economic and health factors that determine the overall development of the country. Different factors of countries related to income and health help us decide about its growth and development.

##Purpose of Project
To categorize the countries using socio-economic and health factors that determine the overall development of the country. 

##Dataset
For this project, We use data-submission.csv to cluster countries based on different development factors forming clusters of countries.

##Pre-processing
To better understand the data, we plotted a histogram, pair plots, scatter graphs of the data provided, comparing their relationships among themselves to understand various factors which help in determining a countries development.

##Analyzing Linearity in Dataset
Firstly we observe the given dataset given and the variation of various data in it.
We use different techniques like plotting graphs, histography, heatmaps of the scattering matrix to observe relationships among themselves.
Since there is a large amount of data in the dataset, it is common to cause accuracy and cause overfitting of the problem statement.
We use PCA for reducing dimensions while trying to keep meaningful information
To apply PCA, firstly we Scale the data in an appropriate manner
We use MinMaxScaler as recommend for PCA
In the problem, we use PCA to reduce nine components to five components
We did that as we got the highest score by that combination. which says how a well-clustered model is
After that, we use k-means clustering too cluster countries among themselves by taking no of clusters=4
However, by using the knee-joint graph and silveoutee score, we use conclude its best to no_of_clusters=4 
Thus by the graph of 2 quantities in the database, we observe our clustering is working correctlyInference 

##Methodology for Model Training
We utilized the Principal Component analysis to reduce no of the dataset to smaller no and clustering using k-means.
