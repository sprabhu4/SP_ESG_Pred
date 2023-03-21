## ESG Score Prediction Project 

<b> Notebooks : </b>

1. data_gathering : In this notebook, we combine firm data and return data. Finally, we create a merged dataset at year level
2. data_processing : In this notebook, we add absolute ratios as features, identify outliers, impute null data points using KNN Imputer. Finally, we create two versions of dataset for model training : 
            1. with outliers 
            2. without outliers
3. model_training : In this notebook, we run Random forest regressor for different datasets and picking different set of features

<b> Datasets : </b>

1. raw : this folder contains raw datasets  
2. processed : this folder contains all intermediate datasets created under data_processing and data_gathering notebook
3. model_training_files : this folder contains datasets used for model training
