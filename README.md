# Credit_Risk_Analysis

## Overview of the analysis: 

The purpose of this analysis is to build and evaluate different machine leanring models and apply them to solve the credit card risk. Then we need to compare the balanced accuracy scores and the precision and recall scores of all six machine learning models, and make a recommendation on the model to use.  

The machine learning algorithms used in this analysis were:

* RandomOverSampler Model
* SMOTE Model
* ClusterCentroids Model
* SMOTEENN Model
* BalancedRandomForestCalssifier Model
* EasyEnsembleCalssifier Model


## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. 

### RandomOverSampler Model

![Naive Random Oversampling](https://user-images.githubusercontent.com/102264298/181600609-259c0e8b-758c-4472-9ee5-7f927ff81212.png)

* Balanced accuracy score is 0.645.
* Precision for low-risk loans is 1.00 and for high-risk is 0.01.
* Recall score for low-risk loans is 0.62 and for high-risk is 0.66.

### SMOTE Model

![SMOTE](https://user-images.githubusercontent.com/102264298/181600633-b46aabfc-45a2-4d22-8fa6-2c5df916f999.png)

* Balanced accuracy score is 0.645
* Precision for low-risk loans is 1.00 and for high-risk is 0.01. 
* Recall score for low-risk loans is 0.57 and for high-risk is 0.72.

### ClusterCentroids Model

![ClusterCentroids](https://user-images.githubusercontent.com/102264298/181600652-9139f760-199c-4ecc-b5a1-a6b6bc41da87.png)

* Balanced accuracy score is 0.544
* Precision for low-risk loans is 1.00 and for high-risk is 0.01. 
* Recall score for low-risk loans is 0.40 and for high-risk is 0.69.

### SMOTEENN Model

![SMOTEENN](https://user-images.githubusercontent.com/102264298/181600677-331074ec-f03d-4d01-830d-8ad170f94158.png)

* Balanced accuracy score is 0.575
* Precision for low-risk loans is 1.00 and for high-risk is 0.01. 
* Recall score for low-risk loans is 0.57 and for high-risk is 0.72.

### BalancedRandomForestCalssifier Model

![BalancedRandomForestClassifier](https://user-images.githubusercontent.com/102264298/181600690-4bff78f3-02aa-41f3-ab94-b69923b25ca3.png)

* Balanced accuracy score is 0.873
* Precision for low-risk loans is 1.00 and for high-risk is 0.03. 
* Recall score for low-risk loans is 0.87 and for high-risk is 0.70.

### EasyEnsembleCalssifier Model

![EasyEnsembleClassifier](https://user-images.githubusercontent.com/102264298/181600699-106fe918-b559-4963-bf66-1ea37b58a2b0.png)

* Balanced accuracy score is 0.942
* Precision for low-risk loans is 1.00 and for high-risk is 0.09. 
* Recall score for low-risk loans is 0.94 and for high-risk is 0.92.


## Summary: 

In conclusion, the EasyEnsembleCalssifier Model is the ideal model to use, because it has the highest accuracy score of 0.942 and the highest recall score which is 0.94 for low-risk loans and 0.92 for high-risk. It is recommended to use the EasyEnsembleCalssifier Model to perform the challenge of credit card risk. It is not recommended to use the ClusterCentroids Model due to its lowest accuracy score and recall scores. 
