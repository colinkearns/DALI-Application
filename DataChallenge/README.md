
# Dali Data Challenge

## Overview

In this project, I analyzed hypothetical Store Data from "Superstore"

## Data Visualizations

I created multiple histograms, scatterplots, and maps for this project. Notably, the bar plot `Profits of Current and Refined Discounts`, `Gross Profit Margins across States` and `Profit (USD) vs. Discount (Percentage Off) at Superstore` are particulary helpful

## Free Form Creative Challenge

In my Data Analysis, I primarily attempted to find solutions to profit optimization through data science tools. After creating scatterplots comparing different sub-categories, discounts, and states with Profit, I found that visually, discounts have the greatest affect on profit, and state and sub-category also have an affect. 

The first way through which I trianed this was through a multilinear categorical regression of all of the parameters which were not unique to avoid overfitting. 

First, I made a multilinear regression with all 80+ predictors. This regression had an R squared value of 0.318, proving to be fairly encompassing. This proved that many states and sub-categories need to be targeted in order to improve profit.

The significantly significant and positively correllated arguments with profit improvement were copier sales and Sale of goods in Michigan. The negative trend-associated and statistically significant coefficients are, to list some notable ones, bookcase sells, machine sells, and Florida, Texas, and  Ohio sales.

I decided to shorten the list of regression coefficients after this due to the much higher p-values of shipping method, 

This new model just encompassing profit, sales, and sub-category had an r-squared value of 33%, indicating fairly good representation. Overall, I found that discount was the main hamper to the Superstore's 
Discount, with a P-value of 0 and coefficient of an average -268 dollars less for a discount of 1. This seems extreme, but when we consider that a 40% discound yields a modeled 107 dollar decrease in profit per individual sale, this can become somewhat extreme.

The above claim can be seen in the Profit given Various Discount Specifications bar chart, where decreasing the discounts given over 20% can increase profits significantly for appliances, binders, bookcases, chairs, phones, and tables.

Further, the model demonstrated that the sale of Tables, Machines, Supplies, Storache, Chairs, and Bookcases demonstrated a statistically significant decrease in profit. On the other hand, Binders, and especially Copiers, demonstrate an increase in Profit. 

I think that the store should consider some of these Statistical evaluations in implementing their pricing and Branding strategy. I also believe that they should consider the given maps in considering their area branding strategies, given that many States such as Texas and Ohio show statistically significant profit drops.
