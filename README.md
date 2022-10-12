# Credit_Risk_Analysis

# Overview 
Credit Risk is a problem in todays economy as good loans outnumber risky loans. Economists, software developers, and data analysts apply various techniques to evaluate mathematical models with unbalanced classes. Using the credit card dataset from a lending services company called LendingClub, the analysis applies oversampling and undersampling of the credit card data. Then, a comaprison of two machine learning models that reduces bias and predicting credit risk. Finally, we make a business proposal whether these machine learning models should be used to predict credit risk. The project was conducted using Jupyter Notebook. 

# Results 
Here are the results for the six models that is applied to predict credit risk including their respective precision and recall scores. 

## Figure One (Naive Random Oversampling)

<img width="1218" alt="Screen Shot 2022-10-11 at 10 30 14 AM" src="https://user-images.githubusercontent.com/104328106/195148375-08d52fb4-984f-4794-a5ce-ed65a5c075e2.png">

#### Balanced Accuracy: 0.648767580808264
#### Precision Score: The score is low for high-risk loans and the score is high for low-risk loans 
#### Recall Score: The ratio for high/low loans is 0.61/0.69



## Figure Two (SMOTE Oversampling)
<img width="1208" alt="Screen Shot 2022-10-11 at 10 31 05 AM" src="https://user-images.githubusercontent.com/104328106/195148542-ba8517aa-c88e-4eaf-b023-773b88295ad6.png">

#### Balanced Accuracy: 0.6159507435206336
#### Precision Score: The score is low for high-risk loans and the score is high for low-risk loans 
#### Recall Score: The ratio for high/low loans is 0.59/0.65




## Figure Three (Undersampling)
<img width="1232" alt="Screen Shot 2022-10-11 at 10 40 18 AM" src="https://user-images.githubusercontent.com/104328106/195150382-cb491cc8-becf-4a64-a16a-07795a07bb44.png">

#### Balanced Accuracy: 0.5270022279431613
#### Precision Score: The score is low for high-risk loans and the score is high for low-risk loans 
#### Recall Score: The ratio for high/low loans is 0.60/0.46





## Figure Four (Combination on Over and Undersampling)
<img width="1164" alt="Screen Shot 2022-10-11 at 10 40 32 AM" src="https://user-images.githubusercontent.com/104328106/195150432-60d78060-5def-4d27-abb5-e063a6bb54dd.png">

#### Balanced Accuracy: 0.6159507435206336
#### Precision Score: The score is low for high-risk loans and the score is high for low-risk loans 
#### Recall Score: The ratio for high/low loans is 0.59/0.65






## Figure Five (Balanced Random Forest Classifier)
<img width="1138" alt="Screen Shot 2022-10-11 at 10 40 53 AM" src="https://user-images.githubusercontent.com/104328106/195150519-3c157e1e-0b40-4621-88f7-1dbdb0e3e742.png">

#### Balanced Accuracy: 0.7877672625306695
#### Precision Score: The score is low for high-risk loans and the score is high for low-risk loans 
#### Recall Score: The ratio for high/low loans is 0.67/0.91





## Figure Six (Easy Ensemble AdaBoost Classifier)
<img width="1191" alt="Screen Shot 2022-10-11 at 10 41 09 AM" src="https://user-images.githubusercontent.com/104328106/195150571-df37c1eb-e40f-432a-9313-388d557d1b8c.png">

#### Balanced Accuracy: 0.925427358175101
#### Precision Score: The score is low for high-risk loans and the score is high for low-risk loans 
#### Recall Score: The ratio for high/low loans is 0.91/0.94




# Summary 
From the results gathered in all six algorithms, the one that generated the highest percent accuracy is the Easy Ensemble AdaBoost Classifier with roughly a 93% accuracy. The other five models were below 80% accuracy. Typically, the algorithm that achieves an accuracy of 90% or higher is the best one to use to predict credit risk. Economists and data analysts have to make sure that the process applied to predict credit or loan risk is percise to make the right predictions. Another thing to observe is the recall scores. AdaBoost Classifier obtained the highest recall score of 0.94. From the results, it is the best option to use to predict credit risk analysis. 
