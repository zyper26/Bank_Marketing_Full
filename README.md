# Bank Marketing (with social/economic context)

The binary classification goal is to predict if the client will subscribe a bank term deposit (variable y).

## Dataset

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

[Dataset URL]https://archive.ics.uci.edu/ml/datasets/bank+marketing


## Steps:

1. Importing Libraries
2. Exploratory Data Analysis
3. Missing Value Treatment
4. Split Data Into Train and Test
5. Model Building with hyperparameter tuning and Model Evaluation:<br>
    i. Logistic Regression <br>
    ii. Random Forest Classifier <br>
    iii. Gradient Boosting <br>


### Two notebook files:
 1.  In one notebook I did not take duration as input to the models.
 2.  In another notebook I did take duration as input to the models. [ So that we can use these models once we have contacted a client ]


# Results:

#### AUC ROC plot on model without duration 
![Results Plot without duration](https://github.com/zyper26/Bank_Marketing_Full/blob/master/results_without_duration.png)

<br/> <br/>

#### AUC ROC plot on model with duration
![Results Plot with duration](https://github.com/zyper26/Bank_Marketing_Full/blob/master/results_duration.png)
