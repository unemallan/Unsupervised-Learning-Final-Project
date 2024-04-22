# Unsupervised-Learning-Final-Project
CSCA 5632 Final Project

## Project Title: 
Unsupervised Learning for Customer Segmentation and Churn Prediction in Telecom Industry

## Objective:
Utilize unsupervised learning techniques to segment customers based on their behavior and characteristics, and identify groups with a higher likelihood of churn. This is a continuation of the supervised learnig from the previous class. Here we will explore the use techniques like clustering to identify patterns and segments within the data that might indicate potential churn. 

## Dataset:
taken from Kaggle
https://www.kaggle.com/c/customer-churn-prediction-2020/data

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
