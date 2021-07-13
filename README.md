## Recommend Clothing Size by Modelling Customer's Feedback 

Product size recommendation and fit prediction are critical in order to improve customers’ shopping experiences and
to reduce product return rates.

However, modeling customers’ fit feedback is challenging due to its subtle semantics,
arising from the subjective evaluation of products and imbalanced label distribution
(most of the feedbacks is "Fit"). 

### Problem Statement

As a data scientist, our aim is to predict customer satisfaction.

This dataset contains information regarding clothes.
Each observation is a different fitting size with various features.

### Features Description

Feature          -     	Description
 
bra_size 	       -     integer value.

category 	       -     In which category clothes belong.

cup_size 	       -     size of the cloth.

height           -	   Height of the customer.

hips 	           -     Size of the hips.

item_id 	       -      Id number.

length 	         -     Length of the cloth.

quality          -	   Rating given by customer.

size 	           -     size of the cloth.

userId 	         -      userID.

fit (Target) 	   -     Target variable (fit/large/small).

### Evaluation metrics

For this particular dataset, we are using accuracy_score as the evaluation metric.

### Outcomes

After completing this project, I have a better understanding of exploratory data analysis, data preprocessing, how to build a classifier model.
In this project, I have applied the following concepts:

    EDA
    Data preprocessing
    Decision tree classifier
    Grid search CV

