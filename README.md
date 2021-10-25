# Customer-Segmentation--Unsupervised-Kmeans Clustering

## Problem Statement : 
* Let's say we have a product that we want to sell in a mall, but we dont have any idea who to target, what kind of customers we need to give our attention to ..etc?
But, we have some cusomer data that has certain information on their behaviour.
But, what can we analyse from it?

* ANS: Cluster them into groups and then analyse the groups individually to check their behaviour.

* We will use machine learning algorithms to analyse data and and this project will show you how to cluster customers on segments based on 
their behavior using the K-Means algorithm in Python.

## Let's begin:
### Let's take a look at our dataset.

![data head](https://user-images.githubusercontent.com/56465352/138680346-caf02fd6-ac4a-4378-be28-a08d18e10bd4.JPG)

* Some basic statistics of the data

![statsJPG](https://user-images.githubusercontent.com/56465352/138680438-57298344-e0a6-4b29-becb-38a6b792b9e3.JPG)

* Let's see how the Annual income is distributed.

![Uni](https://user-images.githubusercontent.com/56465352/138680545-460b3b1f-f9db-4fe2-811e-a332180d1425.JPG)

* And also how the other variables are distributed too :

![BIG 3 ](https://user-images.githubusercontent.com/56465352/138680560-7d7cd2d6-fb1f-4883-a43d-ed6fbe059622.JPG)

* More Data Visualization with KDE plot

![KDE plot](https://user-images.githubusercontent.com/56465352/138680666-31449b8d-7118-44b3-a08f-3e6374f6bdc1.JPG)
 
* Box Plot to check the data distribution between males and females
 
![Small box plot](https://user-images.githubusercontent.com/56465352/138682259-dacac77d-fe7a-4c14-822a-2e8d51f7eb50.JPG)

* Bi-Variate scatter plots :

* ![bi-variate BIG](https://user-images.githubusercontent.com/56465352/138684130-5e112daa-3cfc-406d-893a-928f1ae73172.JPG)

* ![Bi-variate scatter](https://user-images.githubusercontent.com/56465352/138684058-c31e1ac8-ded7-4066-8cf1-0b21884bba45.JPG)


# Correlation Matrix :

![data_Corr](https://user-images.githubusercontent.com/56465352/138683933-76ae7917-8c50-43e8-aaac-5aeaa0844b8e.JPG)

## K-means Clusering  : 

* Calculating inertia - 

![calculating inertia](https://user-images.githubusercontent.com/56465352/138682372-f214975f-8d86-4520-9c14-a43d20cb2007.JPG)

### Elbow method to find the optimum number of clusters

![elbow method](https://user-images.githubusercontent.com/56465352/138682451-f9c15df0-d56f-4048-9350-2cd1023afab4.JPG)


## Bi-Variate Clusters
![bi-variate](https://user-images.githubusercontent.com/56465352/138684205-7b83d7f3-5348-4900-a564-fcabaa421d7d.JPG)

* Final Data with Cluster points:

![final clusters](https://user-images.githubusercontent.com/56465352/138684269-81b3d2f0-6f99-4c16-8bc0-73999fff5c59.JPG)



## Authors

Dilip Nikhil 

## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details
