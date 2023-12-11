# Customer-segmentation-using-KMeans-clustering
# Buisness case
Companies want to understand their customers more deeply by clustering customers based on similar interests and needs. So that the marketing team can market the target customers according to their preferences and increase their sales eventually.
# Problem statement
* Segment the customers based on RFM so that the companies can target customers effectively

* R (Recency) - No. of days since last purchase.
* F (Frequency) - No. of transactions.
* M (Monetary) - Total revenue contributed.
#  Data preprocessing and feature engineering
* Handled missing values
* Created new columns Amount, Recency, Frequency
# EDA
* Performed EDA with Recency and Frequency
* Using boxplot found outliers in features
# Outliers treatment
* Handled outliers using IQR method
# Scaling
* Scaled the data using standard scaler
# Model building
* Used Kmeans model
* By elbow method found optimal k value
# Visualized the clusterd labels and found valuable insights
