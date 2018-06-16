# MammographicMassClassification

## Objective 

This project deals with classifying Mammographic masses as benign or malignant using different Machine Learning algorithms including
SVM, Logistic Regression, Decision Trees, Naive Bayes, Artificial Neural Network and many more. ROC curves are plotted for each to 
identify the best classification algorithm for the problem.

## Problem

Mammography is the most effective method for breast cancer screening available today. However, the low positive predictive value of breast
biopsy resulting from mammogram interpretation leads to approximately 70% unnecessary biopsies with benign outcomes. To reduce the high
number of unnecessary breast biopsies, several computer-aided diagnosis (CAD) systems have been proposed in the last years.These systems
help physicians in their decision to perform a breast biopsy on a suspicious lesion seen in a mammogram or to perform a short term follow-up
examination instead.

## Dataset

"Mammographic masses" public dataset from the UCI repository has been used.
(source: https://archive.ics.uci.edu/ml/datasets/Mammographic+Mass)
This data set can be used to predict the severity (benign or malignant)
of a mammographic mass lesion from BI-RADS attributes and the patient's age.

Number of Attributes: 6 (1 goal field: severity, 1 non-predictive: BI-RADS, 4 predictive attributes)

Attribute Information:
   1. BI-RADS assessment: 1 to 5 (ordinal)  
   2. Age: patient's age in years (integer)
   3. Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal)
   4. Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)
   5. Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal)
   6. Severity: benign=0 or malignant=1 (binominal)

The file mammographic_masses.data.txt contains the attributes information and mammographic_masses.names.txt gives the description of the attributes.

## Dependencies

1. Python
2. Tensorflow
3. Keras
4. Pandas
5. Numpy
6. Sklearn
7. Matplotlib
8. IDE supporting Ipython Notebook (I used Enthought Canopy)

## Running Script

The ipyn includes different machine learning algorithms implemented for the above problem. **ANNs perform the best in classifying the 
mammographic masses as benign or malignant with an AUC of 0.87 +/- 0.01**. The results can be further improved by tuning hidden layers, number of neurons etc.
Download the ipyn and run each cell to get the outputs. Do remember to change the path of the file where you have copied the dataset.

## Future Work

Develop different architecture for Neural Network which can further improve the accuracy.

