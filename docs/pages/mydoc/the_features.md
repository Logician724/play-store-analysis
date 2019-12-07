---
title: Dataset Features
tags: []
keywords:
summary: "An exploration of the features of the dataset and the description of each one"
sidebar: mydoc_sidebar
permalink: the_features.html
folder: mydoc
---
## Main Dataset Features

 * `App`: the app name.
 * `Category`: a categorical label, which describes which broad category the app belongs to.
 * `Rating`: a continuous variable with a range from 0.0 to 5.0, which describes the average rating the app has received from the users. 
 * `Reviews`: a continuous variable describing the number of reviews that the app received. 
 * `Size`: the size of the app. The suffix M is used for megabytes, while the suffix K is used for kilobytes.
 * `Installs`: a categorical label that describes the number of installs. 
 * `Type`: a label that indicates whether the app is free or paid. 
 * `Price`: the price value for the paid apps. 
 * `Content Rating`: a categorical rating that indicates the age group for which the app is suitable.
 * `Genre`: a semicolon-separated list of genres to which the app belongs.
 * `Last Update`: the date the app was last updated.
 * `Current Version`: the current version of the app as specified by the developers.
 * `Android Version`: the Android operating system the app is compatible with.

## Reviews Dataset Features
* `App`: the app name.
* `Translated_Review`: the review text in English.
* `Sentiment`: the sentiment of the review, which can be positive, neutral, or negative.
* `Sentiment_Polarity`: the sentiment in numerical form, ranging from -1.00 to 1.00.
* `Sentiment_Subjectivity`: a measure of the expression of opinions, evaluations, feelings, and speculations. 