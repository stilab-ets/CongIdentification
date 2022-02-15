# CongIdentification


This is the Github assets folder for the paper entitled "What Constitute a Configuration System? An Empirical Study on OpenStack Projects". This paper investigates the configuration file types that constitute the configuration system of OpenStack. We conduct our study on OpenStack as it is one of the most deployed cloud platform for infrastructure management. To identify the different configuration files, we leverage two machine learning models. The first model predicts configuration from non-configuration files. The second model predicts the different types of the configuration files. To perform our experiment, we compare between five classifiers (SVC, RF, LR, KNN, and GB).

In this repository, we provide: 

1) In the datasets folder: the datasets for training the [``Config-NonConfig model``](https://github.com/stilab-ets/CongIdentification/blob/main/Datasets/Model1-ConfigNonconfig.csv) and the [``ConfigTypes model``](https://github.com/stilab-ets/CongIdentification/blob/main/Datasets/Model2-ConfigTypes.csv). 
2) In the scripts folder: the scripts for building the [``Config-NonConfig model``](https://github.com/stilab-ets/CongIdentification/blob/main/Scripts/Model1-ConfigNonconfig.py) and the [``ConfigTypes model``](https://github.com/stilab-ets/CongIdentification/blob/main/Scripts/Model2-ConfigTypes.py).   
3) In the classifiers-results folder: the comparison results between the five classifiers for the [``Config-NonConfig model``](https://github.com/stilab-ets/CongIdentification/blob/main/Classifiers-Results/Model1-ConfigNonconfig.csv) and the [``ConfigTypes model``](https://github.com/stilab-ets/CongIdentification/blob/main/Classifiers-Results/Model2-ConfigTypes.csv). 

