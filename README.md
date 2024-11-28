This Model aims to classify the sample cases of insurance cross-selling related to vehicle insurance and predict whether it will be successful or not. The dataset is taken from the Kaggle Competition:
Binary Classification of Insurance Cross Selling linked below:
  https://www.kaggle.com/competitions/playground-series-s4e7/data

It analyses the various features and the relationships between them and uses various models to classify the samples.

### Data Analysis

- The distributions of various columns are plotted and it is found that the data is imbalanced with a large proportion of positive responses.
- The categorical data is encoded and a correlation map is plotted between all the features.
- There is a strong positive correlation between age of the customer and age of the vehicle.
- There is a strong negative correlation between vehicle damage and previously insured, as well as between policy sales channel and customer age.

## Classificiation

1. **Logistic Regression** :
   - Accuracy:  0.8778
   - ROC_AUC_Score:  0.5089
   - Sensitivity: 0.9961
   - Specificity: 0.0217
   - F1 Score: 0.9338
  
2. **Decision Tree Classifier** :
   - Accuracy:  0.878
   - ROC_AUC_Score:  0.5
   - Sensitivity: 1.0
   - Specificity: 0
   - F1 Score: 0.467
