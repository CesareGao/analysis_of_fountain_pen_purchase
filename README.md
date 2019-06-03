# Analysis of Fountain Pen Purchase

## Team Member:

- Yan Gao

## Project Motivation:

This time I want to find how to determine the best seller of a certain type of product. So I intend to build a model which could find the exact products according to the requirement of customers and predict some suggestions ones according to the similarity in between.

The dataset I choose is from [The Goulet Pen CO.]( https://www.gouletpens.com/ ) website. There is no formatted data, so I'll build the dataset by web scrapping to get the information I need.

To get a start, I'll only use the fountain pens' data from the website.

## Project Objective:

- Find the best purchase fit according to the customer requirement.
- Build a similarity model between the fountain pens according to the catogorical data and numerical data.
- Make comparation between the certain type of product from different website. (If the project time is enough)

## Libraries/Tools intended to use

- Statistical testing (quantify the categorical data, test the correlation between different attributes)
- feature engineering (train word3vec model to find the similarity between fountain pens according to the feature of fountain pen itself and the customer' review)
- NLP word representation

## Data Collection details:

- Brand/Series: Categorical. Which brand and series this fountain pen belongs to.
- Color: Categorical data. The color of fountain pen.
- Product code: alphabetnumerical data. The unique code for each fountain pen.
- Literature description: text data. The major description of fountain pen.
- Price: numeric data. The price of fountain pen.
- In stock: Boolean data. Whether the fountain pen is in stock or out of stock.
- Diameters: numeric data. The diameter of fountain pen.
- Weight: numeric data. The weight of fountain pen.
- Max Ink Capacity: numeric data. The ink capacity of fountain pen.
- Ease of Use/Ideal For/Quality/Value: each is numeric data.
- Review: text data. Usage review from customer.
- ...(To be collected)

## Work Detail

- Data clean up: 
    * Extract the categorical data information from the name of fountain pen and detail discription.
    * Unified the diameters and weight of different parts of the fountain pen.
    * Extract categorical information from the text data.
    * Properly set the value and type of numeric evaluation data.
- Hypothesis:
    * All the customers review quite objectively.
    * No big mistakes in catogorical data.
- Data Bias Analysis:
    * All the data comes from only one website.
    * There are some product has really fewer customer review.
    * The company has selling preference when choosing fountain pens.

## Predictive Task

By the corresponding data, compute the similarity between different fountain pens by featuring matrix. Try to predict the fountain pen the customers may like according to their preference and make purchase suggestions.

## Tentative Timeline
Steps and Outlines | Roughly Time Estimate
------------------ | ---------------------
Data Collecting | 2 weeks
Data Cleanup | 2 weeks
Statistical Analysis | 1 week
Build Prediction Model | 3 weeks
Test the Model | less than 1 week
Save Result and Make Final Report | during the whole process and the final week

## Project Binder link
[analysis_of fountain pens](https://mybinder.org/v2/gh/CesareGao/analysis_of_fountain_pen_purchase/master?filepath=training_model.ipynb)

## Project Running result (HTML)
TBD
