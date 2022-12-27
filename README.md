# Predicting Breast Cancer in a patient using Machine Learning
![Page1](https://github.com/connectasp/BreastCancerPrediction_Project/blob/abf32cd5694b2fc8e23d4e73bc9bad550a5036c3/Asset/breast-cancer-awareness-month-banner-with-young-woman-pink-ribbon_73378-1069.jpg)

## Abstract
> 1. Breast cancer represents one of the diseases that make a high number of deaths everyyear. 
> It is the most common type of all cancers and the main cause of women's deathsworldwide. 
> Classification and data mining methods are an effective way to classify data.
> Especially in the medical field, where those methods are widely used in diagnosis and analysis to make decisions.
> 2. Machine Learning technique can dramatically improve the level of diagnosis in breast cancer. Research shows that experienced physicians can detect cancer by 79% accuracy, while a 91 %( sometimes up to 97%) accuracy can be achieved using Machine Learning techniques.

## Problem Statement
> Given the details of cell nuclei taken from breast mass, predict whether or not a patient has breast cancer using the Ensembling Techniques. Perform necessary exploratory data analysis before building the model and evaluate the model based on performance metrics other than model accuracy.

## Dataset Information:
> The dataset consists of several predictor variables and one target variable, Diagnosis. The target variable has values 'Benign' and 'Malignant', where 'Benign' means that the cells are not harmful or there is no cancer and 'Malignant' means that the patient has cancer and the cells have a harmful effect

## Variable Description:
![Page2](https://github.com/connectasp/BreastCancerPrediction_Project/blob/dda6d06faf809e1bbc2c2428a830574184a57732/Asset/Screenshot%202022-12-27%20115250.png)

## Directory Structure
> 1. This repository consists the file required to Predicting Breast Cancer in a patient using Machine Learning
> 2. The "main.py" file consists of major code required to develop the applcation. Jupyter is recommended.
> 3. The "cancer.csv" file is a data set of patients.

## Requirements
> 1. Python Scripting
> 2. Jupyter IDE (Recommended)
> 3. Pandas to create Data Frames
> 3. Numpy to work with Array of Data
> 4. Matplotlib and Seaborn for Plotting graph
> 5. SKLearn for Machine learning

## Loading Necessary Libraries
![Page3](https://github.com/connectasp/BreastCancerPrediction_Project/blob/62ba0302c1474119373376cdfae3ab3daa4db1ec/Asset/Screenshot%202022-12-27%20113333.png)

## Loading Dataset and Viewing the Data in Dataframe
![Page](https://github.com/connectasp/BreastCancerPrediction_Project/blob/62ba0302c1474119373376cdfae3ab3daa4db1ec/Asset/Screenshot%202022-12-27%20113353.png)

## Visualize the relationship between our features
![Page](https://github.com/connectasp/BreastCancerPrediction_Project/blob/62ba0302c1474119373376cdfae3ab3daa4db1ec/Asset/download%20(1).png)

### Note
> 1 (Orange) = Benign (No Cancer) - 0 (Blue) = Malignant (Cancer)


## Checking the Percentage of Malignant and Benign in a given Dataset
![Page](https://github.com/connectasp/BreastCancerPrediction_Project/blob/62ba0302c1474119373376cdfae3ab3daa4db1ec/Asset/download%20(2).png)

### Note
> 1 = Benign (No Cancer) - 0 = Malignant (Cancer)

## Checking the Coorelation between the Features
![Page](https://github.com/connectasp/BreastCancerPrediction_Project/blob/62ba0302c1474119373376cdfae3ab3daa4db1ec/Asset/download%20(3).png)

## Support Vector Machine (SVM)
> A Support Vector Machine (SVM) is a binary linear classification whose decision boundary is explicitly constructed to minimize generalization error. It is a very powerful and versatile Machine Learning model, capable of performing linear or nonlinear classification, regression and even outlier detection.
SVM is well suited for classification of complex but small or medium sized datasets.

## Model Training
> 1. “y” = Is the feature we are trying to predict (Output). In this case we are trying to predict if our “target” is cancerous (Malignant) or not (Benign). i.e. we are going to use the “target” feature here.
> 2. “X” = The predictors which are the remaining columns (mean radius, mean texture, mean perimeter, mean area, mean smoothness, etc.)

# In this Project using various Machine Learning Techinique the Accuracy of Model is around 98%

## Conclusion
> This project took us through the journey of explaining what “modeling” means in Data Science, difference between model prediction and inference, introduction to Support Vector Machine (SVM), advantages and disadvantages of SVM, training an SVM model to make accurate breast cancer classifications, improving the performance of an SVM model, and testing model accuracy using Confusion Matrix.

## Developer
+ Ajith Sanjeeva Poojary (M.Tech : Software Engineering)
[Click here to View Linkedin Profile](https://www.linkedin.com/in/connectasp/)


