# SECOM-Detecting-Defected-Items

Anamoly Detection for Detecting Defected Manufactured Semi-Conductors, as in this case  of Classification, the Defected Chips would be very less in comparison to perfect Chips so we have apply either Over-Sampling or Under-Sampling.

# Abstract

 Semiconductor manufacturing is one of the most technologically and highly complicated manufacturing processes. Traditional machine learning algorithms such as uni-variate and multivariate analyses have long been deployed as a tool for creating predictive model to detect faults. In the past decade major collaborative research projects have been undertaken between fab industries and academia in the areas of predictive modeling.
 
 In this study we propose machine learning techniques to automatically generate an accurate predictive model to predict equipment faults during the wafer fabrication process of the semiconductor industries. Aim at constructing a decision model to help detecting as quickly as possible any equipment faults in order to maintain high process yields in manufacturing.
     
# Data Sources & Goal
 The SECOM (Semiconductor Manufacturing) dataset, consists of manufacturing operation data and the semiconductor quality data. It contains 1567 observations taken from a wafer fabrication production line. Each observation is a vector of 590 sensor measurements plus a label of pass/fail test.
 
 Also, there are only 104 fail cases which are labeled as positive (encoded as 1), whereas much larger amount of examples pass the test and are labeled as negative (encoded as -1). This is a 1:14 proportion. In this work not only a feature selection method for extracting the post discriminative sensors is proposed, but also boosting and data generation techniques are devised to deal with highly imbalance between the pass and fail cases. 
 
 
# Source:
UCI SECOM DataSet
