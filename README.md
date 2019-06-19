# Identify-Customer-Segments
Project Overview
In this project, we work with real-life data provided to us by our Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. We will use unsupervised learning techniques to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. 

## Step 0: The Data
The files available for the project are:

+ Udacity_AZDIAS_Subset.csv: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
+ Udacity_CUSTOMERS_Subset.csv: Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
+ Data_Dictionary.md: Information file about the features in the provided datasets.
+ AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographic data.

## Step 1: Preprocessing
few key points:

+ How are missing or unknown values encoded in the data? Are there certain features (columns) that should be removed from the analysis because of missing data? Are there certain data points (rows) that should be treated separately from the rest?
+ Consider the level of measurement for each feature in the dataset (e.g. categorical, ordinal, numeric). What assumptions must be made in order to use each feature in the final analysis? Are there features that need to be re-encoded before they can be used? Are there additional features that can be dropped at this stage?

## Step 2: Feature Transformation
In this stage of the project, we will attend to the following points:

+ The first technique that we should perform on the data is feature scaling. 
+ Then apply principal component analysis (PCA) to find the vectors of maximal variability. How much variability in the data does each principal component capture? 

## Step 3: Clustering
Finally, we will apply clustering techniques to identify groups in the general demographic data. We will then apply the same clustering model to the customers dataset to see how market segments differ between the general population and the mail-order sales company. We will tackle the following points in this stage:

Use the k-means method to cluster the demographic data into groups. 
