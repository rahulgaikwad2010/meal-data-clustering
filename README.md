# Meal Data Clustering

In the project, we will be working with a unsupervised machine learning technique called clustering. Aim is to cluster meal data based on the amount of carbohydrates in each meal.

# Table Of Contents
-  [Project Structure Overview](#project-structure-overview)
-  [Introduction](#introduction)
-  [Project Goal](#project-goal)
-  [Data Set](#data-set)
-  [Version](#version)
-  [Author](#author)

<br/>

### Project Structure Overview
```
├── Facial Expression Recognition Deep Learning
|  ├── dataset       - this folder contains training & testing data.
|  │    ├──  PrivateTest_data_images.npy
|  |    ├──  PublicTest_data_images.npy
|  |    ├──  Training_data_images.npy (Omitted Because > 25 MB)
|  |    └──  Training_data_labels.npy
|  │
└────── Facial Expression Recognition.ipynb
```

<br/>

### Introduction

In the project, we will be working with a specified dataset of images.  we will then explore the data and try the statistical learning approaches that we have covered in this course to tackle the task associated with the dataset.  The statistical approaches should cover both conventional machine learning (i.e. not deep learning), from the first half of the unit, and deep learning from the second half.  A goal of the project is to explore the approaches we've leant, or perhaps beyond those, in order to build a high-performing system.

### Project Goal

- Extract features from Meal data
- Cluster Meal data based on the amount of carbohydrates in each meal

**Extracting Ground Truth:** 
Derive the max and min value of meal intake amount from the Y column of the Insulin data. Discretize the meal amount in bins of size 20. Consider each row in the meal data matrix that you generated in Assignment 2. According to their meal amount label put them in the respective bins. 
In total you should have   bins.

**Performing clustering:**
Now ignore the mealAmountData. Without using the meal amount data use the features. Use DBSCAN or KMeans. Try these two. 

**Report your accuracy of clustering based on SSE, entropy and purity metrics.**

<br/>

## Version

1.0.0 

<br/>

## Author

* **Rahul Gaikwad** - Initial work and development

<br/>

I welcome your questions. Write to rahul.gaikwad2010@gmail.com

<br/>
