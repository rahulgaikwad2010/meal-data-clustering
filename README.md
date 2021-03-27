# Meal Data Clustering

<br/>

# Table Of Contents
-  [Project Structure Overview](#project-structure-overview)
-  [Introduction](#introduction)
-  [Project Goal](#project-goal)
-  [Version](#version)
-  [Author](#author)

<br/>

### Project Structure Overview
```
├── Meal Data Clustering
|  ├── data       - this folder contains training & testing data.
|  │    ├──  CGMData.csv
|  │    ├──  Result.csv
|  |    └──  InsulinData.csv
|  │
└────── Meal Data Clustering.ipynb
```

<br/>

### Introduction

In the project, we will be working with a unsupervised machine learning technique called clustering. Aim is to cluster meal data based on the amount of carbohydrates in each meal.

### Project Goal

- Extract features from Meal data
- Cluster Meal data based on the amount of carbohydrates in each meal

**Extracting Ground Truth:** 

Derive the max and min value of meal intake amount from the Y column of the Insulin data. Discretize the meal amount in bins of size 20. 
According to their meal amount label put them in the respective bins. In total you should have `n = (max-min)/20`  bins.

**Performing clustering:**

Now ignore the mealAmountData. Without using the meal amount data use the features. 
Use `DBSCAN or KMeans`. Try these two. 

Report your accuracy of clustering based on:
- SSE
- Entropy
- Purity metrics

<br/>

## Version

1.0.0 

<br/>

## Author

* **Rahul Gaikwad** - Initial work and development

<br/>

I welcome your questions. Write to rahul.gaikwad2010@gmail.com

<br/>
