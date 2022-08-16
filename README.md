# Customer-Segmentation
## Introduction
I trained unsupervised machine learning algorithms in this project to segment the customer. In order to increase the likelihood that a customer would purchase a product, customer segmentation helps sellers to develop tailored marketing messages for a certain group of customers. Better client interactions and overall organizational performance are aided by this for the businesses.
## dataset
Credit card data is collected from kaggle dataset.A customer credit card information dataset can be applied to targeted marketing, customer segmentation, and other similar use cases in the marketing sector.
## Attributes information
BALANCE	, BALANCE_FREQUENCY,	PURCHASES, 	ONEOFF_PURCHASES, 	INSTALLMENTS_PURCHASES	, CASH_ADVANCE	, PURCHASES_FREQUENCY,	ONEOFF_PURCHASES_FREQUENCY, 	PURCHASES_INSTALLMENTS_FREQUENCY	, CASH_ADVANCE_FREQUENCY, 	CASH_ADVANCE_TRX	, PURCHASES_TRX	,CREDIT_LIMIT, 	PAYMENTS, 	MINIMUM_PAYMENTS	, PRC_FULL_PAYMENT	, TENURE
## libraries
Used libraries like NumPy, seaborn, pandas, matplotlib,scikit learn etc
## Methods
k- means clustering is used for grouping the customers into different clusters.
Principal component analysis(PCA) is used to reduce the number of variables for visualization in 2D plot
## steps
1.importing libraries
2.importing dataset
3. Finding the missing values and replacing them
4. Checking the duplicate entries
5.Dropping object entries
6.Correlation matrix formation
7.Feature scaling
8.Building the clustering model and calculating the values of the Distortion and Inertia (Elbow Method)
9.Applying k-means
10.applying PCA
11. Visualisation of clusters
## Findings
K-means clustering was used after utilizing the elbow method to divide customers into 7 clusters.
I applied PCA, reduced it to two principle components, then utilized the Seaborn library to better visualize the various clusters.
