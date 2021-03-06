# Mathematics Expression Calculator Based on Speech Recognition

## Abstract

   We use machine learning algorithms to create a mathematics expression audio calculator. By concentrating our research on speech recognition, we hope to create an audio calculator that can do some basic math calculations including addition, subtraction, multiplication and division among integers 0 to 9. In this project, we examine several classification algorithms to predict the spoken digits from the Free Spoken Digit Dataset (FSDD) \cite{dataset} and the spoken operators from the dataset created by ourselves. Before training machine learning models, we extract and concatenate Mel Frequency Cepstral Coefficients (MFCCs) and Log Filterbank Energies from the raw audio data. The models we use include Logistic Regression, Random Forest, and Radial Basis Function (RBF) Kernel Support Vector Machine (SVM). We also apply Adaptive Boosting (AdaBoost) to Logistic Regression model in order to increase the prediction accuracy. Since all of our models have their own strengths and weaknesses, we decide to use plurality vote by assigning weights of 2 to Random Forest and RBF Kernel SVM and a weight of 1 to Logistic Regression with AdaBoost. Although most of our models achieve a test accuracy higher than 90\%, there are problems of overfitting since the training accuracy of all the models are 100\%.

## Installation

   All source codes and demonstrations are in file Audio Calculator.ipynb. Python 3.7 is required to run the script. All required libraries are imported in the first cell of Audio Calculator.ipynb.
