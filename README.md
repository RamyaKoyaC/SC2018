# SC2018
Super Computing 2018 was one amazing experience and here's something I really loved doing there! 
### Introduction of Practical Approaches to Data Analysis for HPC with Spark 
This tutorial was presented by The University of Tennessee, Knoxville

* Started with how to sue the Jupyter Notebook 
* They gave access to the Cluster at Oak Ridge National Laboratory 
* Explained how to run code in cells 
* Introduction to MarkDown
* Hands-on with Spark by running on the cluster
* Carried out k-means clustering 
* Worked on DBSCAN
* Spark is used to define distributed datasets and implement any kind of operations
* The main purpose was to clean, transform, analyse large datasets with Spark on cluster using Cloud
* Concepts related to RDD (resilient distributed systems) 

The two main concepts in Spark 
## Transformations
## Actions
#### ReduceByKey is a special case where elements are distributed that have same keys. 

First we create distributed datasets 
Second, we apply actions on this distributed datasets

### Worked on NHANES Dietary dataset
This depicts the 48-hour diet plan of an American. This dataset will be updated on monthly basis and is high-dimensional 

Problems addressed: 
#### How to deal with missing data?
#### How to perform K-means, DBSCAN using Spark? 

Note: Spark is fast because it uses the cache memory
