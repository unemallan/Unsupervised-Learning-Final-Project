# Unsupervised-Learning-Final-Project
CSCA 5632 Final Project

## Project Title: 
Predictive Maintance of Milling Machines to prevent certain failure modes.

## Objective:
Implement clustering or sequence mining techniques to analyze time-series sensor data from machines or equipment. This can help in predicting when maintenance is needed to prevent failures. In this notebook we will use Milling machine hueristics such as speed, tempreture, RPM, machine type and operating temperature to predict possibility of a failure mode, There are 5 categries of failure for this project.

* Tool wear failure (TWF):

* Heat dissipation failure (HDF)

* Power failure (PWF):

* Overstrain failure (OSF): 

* Random failures (RNF):

## Dataset:
S. Matzka, "Explainable Artificial Intelligence for Predictive Maintenance Applications," 2020 Third International Conference on Artificial Intelligence for Industries (AI4I), 2020, pp. 69-74:.
taken from Kaggle (https://www.kaggle.com/code/zakikurdya/predictive-maintenance/input)

## Tasks:

#### Data Preprocessing: 
Clean the data, handle missing values, encode categorical variables, and scale numerical features if necessary, similar to the supervised learning approach.
#### Exploratory Data Analysis (EDA): 
Explore the dataset to understand its distribution, identify outliers, and gain insights into customer behavior and characteristics.
#### Feature Engineering: 
Create new features or transform existing ones if needed to better capture patterns in the data.
#### Customer Segmentation: 
Use clustering algorithms like K-means, DBSCAN, or hierarchical clustering to segment customers into distinct groups based on their similarities.
#### Interpretation: 
Analyze the characteristics of each cluster to understand the differences between them. Identify segments that exhibit behaviors associated with churn, such as high monthly charges, low tenure, or low usage of services.
#### Churn Prediction: 
Once clusters are identified, you can assign a churn probability to each cluster based on its characteristics. For example, clusters with higher average monthly charges and shorter tenure might have a higher churn probability.
#### Model Evaluation: 
While there are no ground truth labels for churn in unsupervised learning, you can evaluate the quality of the clusters using metrics like silhouette score, Davies-Bouldin index, or visual inspection of cluster separation.
#### Deployment: 
Deploy the clustering model to segment new customers as they join the service, allowing the company to tailor retention strategies to each segment.

## Deliverables:
* A Jupyter notebook showing an Unsupervised Learning problem description, EDA procedure, analysis (model building and training), result, and discussion/conclusion. 
* A video presentation or demo of your work. The presentation should be a condensed version as if you're doing a short pitch to advertise your work, so please focus on the highlights: 
* A public project GitHub repository with your work (please also include the GitHub repo URL in your notebook/report and slides). 

## Future Work:
* Implementing anomaly detection techniques to identify unusual behavior indicative of potential churn.
