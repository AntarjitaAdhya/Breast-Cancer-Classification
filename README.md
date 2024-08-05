
## Breast Cancer Classification Using Neural Network

This project aims to classify breast cancer as either malignant or benign using a Neural Network (NN). It's done with the utilization of the Breast Cancer Wisconsin (Diagnostic) Data Set.





## About The Project

Breast cancer is one of the most common cancers among women worldwide. Early and accurate diagnosis is crucial for effective treatment and patient survival. This project uses a neural network to classify breast cancer tumors as malignant or benign based on various features extracted from digitized images of a fine needle aspirate (FNA) of a breast mass.


## Dataset Description

The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Data Set, which is a widely recognized dataset for evaluating machine learning models. It is included in the sklearn.datasets module of the scikit-learn library. This dataset contains 569 instances, each described by 30 features.

Target classes: Malignant (0), Benign (1)



## Documentation

[Project Report](https://github.com/AntarjitaAdhya/Breast-Cancer-Classification/blob/main/Project_Report.pdf)




## Process To Set Up and Run

Set Up Environment: Install dependencies with pip "install numpy pandas matplotlib scikit-learn tensorflow".


Load and Prepare Data: Use sklearn.datasets.load_breast_cancer to load the dataset. Split and standardize the data.

Build and Train Model:
Define and compile a neural network using TensorFlow/Keras. Train the model on the prepared data.

Evaluate and Plot Results:
Evaluate the model on test data and visualize training/validation accuracy and loss.



