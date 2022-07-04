# KING COUNTY HOUSING PRICE PREDICTION
![](https://github.com/Rachael-Osoro/git_practice/blob/master/Photos/king_county.jpg)

## Navigation
<a href="https://github.com/Rachael-Osoro/Phase_2_project#project-overview">Project Overview</a>

<a href= "https://github.com/Rachael-Osoro/Phase_2_project#business-understanding">Business Understanding</a>

<a href = "https://github.com/Rachael-Osoro/Phase_2_project#findings"> Findings</a>

<a href = "https://github.com/Rachael-Osoro/Phase_2_project#findings"> Recommendations<a/>
  
  <a href = "https://github.com/Rachael-Osoro/Phase_2_project#limitations-of-model"> Conclusions<a/>

## Project Overview
This project was completed using this dataset <a href= "https://github.com/Rachael-Osoro/Phase_2_project/blob/main/kc_house_data.csv">King County Housing Data</a>. The dataset includes homes sold  between May 2014 and May 2015, including house properties such as number bathrooms, zipcode, langitude, latitude. Here is a brief overview of the data set <a href="https://github.com/Rachael-Osoro/Phase_2_project/blob/main/Data_Description.md"> King County Housing Description</a>
The goal of this Analysis is to predict the prices of houses in King County to enable a real estate company make data driven investment in housing as explained below.
## Business Understanding
A real estate company is looking to secure properties in King County Washington. In order to drive up it’s profitability, the company is looking for a model that will predict house prices based on the information provided in <a href= "https://github.com/Rachael-Osoro/Phase_2_project/blob/main/kc_house_data.csv">King County Housing Data</a>. This will help them determine which houses to invest in and adjustments that need to be made to the properties they will acquire in order to attract clientele.
## Findings
The best model for predicting price contains the following independent variables:
Grade, 
Square footage of the house,
Square footage of 15 neighbouring homes.

Model is illustrated below 

![](https://github.com/Rachael-Osoro/git_practice/blob/master/Photos/Model.png)

Distribution of price vs Square foot coverage

![](https://github.com/Rachael-Osoro/git_practice/blob/master/Photos/price_vs_sqft.png)

## Recommendations

Homes with better grades

Homes with appr 2000sqft

Size of homes similar to neighbouring Homes

## Limitations of Model

Multicolinearity.

## Dependencies of this project
Conda
Python
Scipy module
Numpy
Matplotlib

