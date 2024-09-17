# HDFS
In this project we are interested in using Hive for Intrusion detection using a simple 2-feature
decision tree algorithm based on network traffic features.
1. Download the Network traces in this link and load the into HDFS . Carefully explore it and
understand each file of the dataset. Use directories if necessary.
https://cloudstor.aarnet.edu.au/plus/index.php/s/2DhnLGDdEECo4ys
2. Build an appropriate schema for ingesting the Network traces (separate training from test
data), include partitioning of the data.
3. Write HQL queries to confirm the various statistics of the dataset
4. Write the HQL queries for computing the Gini impurity for each feature. Split the data
according to the best (least impurity) feature.
5. Redo the work for each split and work out the next best feature to use to split the data further.
Save your 2-feature decision tree model.
6. for each of the test traces apply your detection, mark the prediction and produce the confusion
matrix.
Deliverables: 1. Report containing (i) HDFS file/directory structure, (ii) the schema, (iii) the
queries for building the decision tree model, and (iv) the Results of the Intrusion detection in the
form of a confusion matrix.
