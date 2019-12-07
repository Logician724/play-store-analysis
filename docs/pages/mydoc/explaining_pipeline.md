---
title: The Pipeline
tags: []
keywords:
summary: "Brief explanation of the pipeline we used"
sidebar: mydoc_sidebar
permalink: explaining_pipeline.html
folder: mydoc
---

## The pipeline flow
![The pipeline flow](images/pipeline.png)

The pipeline consists of multiple stages
1. **Data cleaner** to ensure the quality of the data
2. **Data pre-processor** to change the format of the data to an appropriate one for analysis.
3. **Imputer** to handle missing values
4. **Outlier detector** to handle outlier values to ensure the quality of the analysis.
5. **Feature Engineering** to make new features that we can use to derive more insights and help in predictions
6. **Dataframe Splitter** to allow for custom transformations for different features to fit prediction algorithms.
7. Merging the splitted data to formulate an array with processed features to supply to an ML algorithm to make predictions.