# Predicting-Heart-Disease-using-K-Nearest-Neighbours
## Up to 90% accuracy with just 5 features using KNN algorithm and Principal Component Analysis (PCA) for feature engineering
We are tasked with using a dataset to accurately predict the likelihood of a new patient having heart disease in the future.
The [dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) includes relevant information for each patient, such as their personal information and some medical data, including whether or not they have had heart disease before.
With PCA we have reduced the number of features by almost **70% (from 15 features down to 5 features)**.
Then a **`KNeighborsClassifier`** was trained with a test accuracy of **89%!!**. An improvement in both accuracy and computational speed!!

## Cummulative Accuracy Profile (CAP) Curve
The model's **CAP** curve shows we are having **`85.86%`**. This falls in the range `80% - 90%`which is labelled as **"Very Good Model"**! This means the model is able of processing **50%** of cases with an accuracy of **`85.86%`** compared to manual or random pick with an accuracy of **`50%`**. The added advantage is that the model would be **fast (avoid backlog / waiting in long queue), less human resources and less expensive** (few people on salary!).  


**The dataset contained less than 1000 observations. The model's accuracy could be improved using more observations, further hyperparameter optimization and feature engineering.** 
