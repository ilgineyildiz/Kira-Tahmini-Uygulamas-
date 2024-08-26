### This dataset is taken from Kaggle.
### This project is made with Python
### Before you start you should install these requirements on your environment:
- numpy
- pandas
- scikit-learn(sklearn)

## Aim of this project:
This project aims to guess the rents of the houses in USA using regression and machine learning algorithms.

### Preproccesing
- Fit_transform
- MinMaxScaler
- Label Encoding

### Algorithms used
- RandomForestClassifier
- KNeighborsClassifier

## Results
### Random Forest 
                     precision    recall  f1-score   support

               0       0.81      0.83      0.82       405
               1       0.83      0.81      0.82       423
    accuracy                               0.82       828
    macro avg          0.82      0.82      0.82       828
    weighted avg       0.82      0.82      0.82       828


### KNeighbors
                    precision    recall  f1-score   support

             0         0.80      0.85      0.82       405
             1         0.85      0.79      0.82       423
    accuracy                               0.82       828
    macro avg          0.82      0.82      0.82       828
    weighted avg       0.82      0.82      0.82       828
