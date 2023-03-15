# Linear Regression Assignment
## Bike Sharing Analysis

## Table of Contents
* [Problem Statement](#problem-statement)
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Problem Statement:

This is an academic excercise as part of my Upgrad MSc in Machine Learning & AI

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state
A bicycle BoomBikes want to understand the factors on which the demand for these shared bikes depends.

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The client (BoomBikes) would like to know:
    - Which variables are significant in predicting the demand for shared bikes.
    - How well those variables describe the bike demands
- The company intents to use the information provided to create a business plan for future years
- The aims are:
    - To be prepared when consumers return after the Covid restrictions lift
    - To stand out in the bike sharing market
    - To increase profits
- A csv dataset has been provided containing records for each day from 01/01/2018 to 31/12/2019

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- A linear model was created that could explain 84% of the variance of the total number of rentals each day using the observed features provided.
- The following 3 features have the largest impact on the volume of rentals each day:
    - Temperature  (0.5715)
    - Year (0.2448)
    - Humidity (-0.2166)
- The dataset provided appears to have data quality issues in date and day related fields.
- The final model appears to be succeptable to increased errors caused by outliers in the data despite efforts being taken to remove the outliers. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Python - version 3.10.8
- Pandas - version 1.5.2
- Matplotlib - version 3.6.3
- Seaborn - version 0.12.2
- SciPY - version 1.10.1
- Statsmodels - version 0.13.5

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This work was conducted using the following resources:
- [1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.
- https://www.geeksforgeeks.org/qqplot-quantile-quantile-plot-in-python/
- https://www.statology.org/multiple-linear-regression-assumptions/
- https://www.statology.org/durbin-watson-test/
- Anscombe’s quartet — seaborn 0.12.2 documentation (pydata.org)
- Upgrad MSc Machine Learning & AI lecture notes and videos



## Contact
Created by [@KaneAI] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->