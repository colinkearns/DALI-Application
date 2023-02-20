
# Dali Data Challenge

## Overview

In this project, I analyzed hypothetical Store Data from "Superstore"

## Data Visualizations

I created multiple histograms, scatterplots, and maps for this project. Notably, the bar plot `Profits of Current and Refined Discounts`, `Gross Profit Margins across States` and `Profit (USD) vs. Discount (Percentage Off) at Superstore` are particulary helpful

## Free Form Creative Challenge

In my Data Analysis, I primarily attempted to find solutions to profit optimization through data science tools. After creating scatterplots comparing different sub-categories, discounts, and states with Profit, I found that visually, discounts have the greatest affect on profit, and state and sub-category also have an affect. 

The first way through which I trianed this was through a multilinear categorical regression of all of the parameters which were not unique to avoid overfitting. 

First, I made a multilinear regression with all 80+ predictors. This regression had an R squared value of 0.318, proving to be fairly encompassing. This proved that many states and sub-categories need to be targeted in order to improve profit.

The significantly significant and positively correllated arguments with profit improvement were copier sales and Sale of goods in Michigan. The negalitely and significantly significant coefficients are, to list some notable ones, bookcase sells, machine sells, and Florida, Texas, and  Ohio sales.

I decided to concatenate
