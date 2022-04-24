# Credit Risk Analysis


## <b>Overview of the analysis:</b>

The purpose of the analysis was to predict credit card risk using data from Lending Club by running the data through different machine learning models.  To be able to make a good recommendation, I used many different machine learning models by oversampling, undersampling and combining the two approaches.  In addition, I used two additional models to reduce bias to predict credit risk.  After reviewing all the models and looking at the accuracy, precision, reclass and the F1 score I was able to make a recommendation on the best model.

## <b>Results</b>

Outcome of each model:
 - Random Oversampling
   - The RandomOversampler model was accurate 63.67% of the time. The model had a very low precision score of 1% for high risk credit risk and was able to correctly identify 62% of high credit risk.  Following is the imbalanced classification report.

![](/Resources/Naive.png)

 - SMOTE Oversampling
   - The SMOTE model was accurate 63.03% of the time. The model had a very low precision score of 1% for high risk credit risk and was able to correctly identify 62% of high credit risk.  Following is the imbalanced classification report.

![](/Resources/SMOTE.png)

 - Undersampling
   - The model using Cluster Centroids was accurate 51.03% of the time. The model had a very low precision score of 1% for high risk credit risk and was able to correctly identify 59% of high credit risk.  Following is the imbalanced classification report.

![](/Resources/Undersampling.png)

 - SMOTEENN
   - The model using SMOTEENN was accurate 63.75% of the time. The model had a very low precision score of 1% for high risk credit risk and was able to correctly identify 70% of high credit risk.  Following is the imbalanced classification report.

![](/Resources/combination.png)

 - Balanced Random Forest 
   - The model using the balanced random forest classifier was accurate 78.78% of the time. The model had a precision score of 4% for high risk credit risk and was able to correctly identify 67% of high credit risk.  Following is the imbalanced classification report.

![](/Resources/Balanced RandomForest.png)

 - Easy Ensemble Classifer
   - The model using the easy ensemble classifier was accurate 92.54% of the time. The model had a precision score of 7% for high risk credit risk and was able to correctly identify 91% of high credit risk.  Following is the imbalanced classification report.

![](/Resources/Adaboost.png)
