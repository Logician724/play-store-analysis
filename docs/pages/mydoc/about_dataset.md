---
title: About the dataset
tags: [Overview]
keywords:
summary: "Basic info about the source, shape, and features of the dataset"
sidebar: mydoc_sidebar
permalink: about_dataset.html
folder: mydoc
---
The [dataset](https://www.kaggle.com/lava18/google-play-store-apps) used in this project comprises more than 10,000 entries of Google Play Store apps. These apps belong to different categories and have varying popularities. The dataset is available on Kaggle in CSV format. According to the source that provided the data, the dataset was collected through web-scrapping. The Google Play Store was queried to gather the entries.


The data is divided over two files. The first file `googleplaystore.csv` is the main dataset, which contains more than 10,000 rows and 13 features. The second file `googleplaystore_user_reviews.csv` contains a collection of reviews along with sentiment analysis data. After examinging the files, we realized that the apps in the first and second file do not correspond to one another. Many apps have no reviews associated with them. Therefore, we decided to focus our work and analysis on the main dataset.