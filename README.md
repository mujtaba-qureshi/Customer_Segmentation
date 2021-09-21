# Customer_Segmentation
# Unsupervised Learning (Clustering)
Creating Customer Segmentation Using Unsupervised Learning (Clustering)

## Project Introduction
This project is based on real-life data provided to Udacity by their Bertelsmann partners AZ Direct and Arvato Finance Solution. 
The data here concerns a company that performs mail-order sales in Germany. 
The **objective** of the project is to:

_identify facets of the population that are most likely to be purchasers of the company's products for a mailout campaign_ 

#### Machine Learning Algorithm Used
The (_unsupervised_) **KMeans clustering** was used to create clusters/segments in the population dataset. 
For the purpose of speeding up the code, sklearn's MiniBatchKMeans was used instead of KMeans.

#### Future imporvement recommendations
1. Attempt _clustering_ using the following algos and compare performance with KMeans
* DBSCAN
* Gaussian Mixture

2. For dimentionality reduction, use **Random Projection** instead of PCA

## Library Requirements

This project uses Python 3 and is completed through the Jupyter Notebooks IDE.
The following libraries are used in this project:

* NumPy
* pandas
* Sklearn / scikit-learn
* Matplotlib (for data visualization)
* Seaborn (for data visualization)

## Walkthrough summary

The project is divided into three parts
1. Assessment and cleaning of the data in order to convert the data into a usable form
2. Feature Transformation i.e. scaling, dimentionality reduction (PCA)
3. Application unsupervised learning techniques on the PCA-trasnformed components to 
* organize the general population into clusters
* use those clusters to see which of them comprise the main user base for the company. 

## Datasets used in this project:

The following datasets are used in this exercise:
* `Udacity_AZDIAS_Subset.csv`: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
* `Udacity_CUSTOMERS_Subset.csv`: Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
* `Data_Dictionary.md`: Information file about the features in the provided datasets.
* `AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographic data.

However, it must be noted that **these datasets are a property of _Arvato Bartlesmann_, and have, therefore, been removed from this repository.** 

The project, consquently, is only for viewing purposes
