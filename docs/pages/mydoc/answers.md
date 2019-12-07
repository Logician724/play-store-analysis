---
title: Seeking Answers
tags: []
keywords: main, dataset, data, cleaning
summary: "Demonstrating answers to questions that we raised while exploring the dataset"
sidebar: mydoc_sidebar
permalink: answers.html
folder: mydoc
---

# Overview
After analysis, we raised a few questions and here with try to answer them. In the following, we enumerate those questions along with some visualization that provide a justification for our answer.

## Categories with lowest and greatest average installs

This question can also be rephrased as: What are the categories with the biggest and smallest market segments? Results can be used to identify saturated market segments and niches. 


![Category Installs Bar Chart](images/category_install_bar.png)


We find that the category with most installls is `communication` while the category with the least installs is `medical`.

## Categories with highest and lowest average rating

![Category Ratings Bar Chart](images/category_rating_bar.png)

We note that all the categories have similar ratings on average, but it seems that people liked apps in the `dating` category the least, and `events` category has the highest average rating.


## Relationship between category and size

![Relationship between category and size](images/category_size_bar.png)

We can from the above, that category `Gaming` has the highest number of installs, and from further analysis we found a statistical significant relationship between an application's category with its size.

## Do more installs mean more reviews?


After using a chi2 test on the data we find that there is a statistically significant relationship between the number of installs and the number of reviews in an application.

## Relationship between category and installs

Afte using a chi2 test on the data we find there there is a statistically significant relatioship between the number of install and the category of the application.

## Are there more free or paid apps in the dataset? 

Which type of app is more popular? free or paid?

![Type Installs bar chart](images/type_installs_bar.png)

We can see that free apps are more popular than paid app.

## Is there a relationship between number of Reviews and Rating?

![Reviews Ratings scatter plot](images/reviews_rating_scatter.png)

From the plot, it seems that apps with very few reviews tend to receive random ratings (based on idividual opinions). As the number of reviews increases, the rating of the apps tends to converge at a value near 4.5.

**After testing we find that there is a weak correlation between reviews and ratings**

## Can we predict the rating of an app from the other properties of the app?
![Numerical scatter matrix](images/numerical_scatter_matrix.png)


![Numerical heatmap](images/numerical_heatmap.png)

We conclude that there are no strong correlations. None of the numerical attributes are strong predictors of Rating. This question will be further through the analysis.

## What is the most common genre among the apps?
From analysis we find the most common genre to be `Tools` while the least common genre for an app is `Music`.

## Can the sentiment analysis dataset be useful for the prediction of app ratings? 

**Can we engineer new per-app features out of it?**

We engineered features based on the the sentiment polarity and subjectivity per app. We also noticed that the correlation between the engineered features and the ratings is higher than the correlations between rating and values in the original dataset. 

![Sentiment rating scatter plot](images/sentiment_scatter.png)

As shown by the plot, it seems that apps tend to have a higher rating as the polarity increases. However, the data doesn't seem to show that a rating of an app would drop below 2.5 out of 5. This matches with the fact that rating of the apps in the dataset is skewed. It also indicates that the subset in the Reviews dataset consists of apps with relatively good ratings. 