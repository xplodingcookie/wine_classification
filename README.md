## README

Author: Dong Li

This program is designed to implement a K-NN model to classify the quality of wines from their chemical properties. It also generates pairplots between the chemical properties alcohol, fixedAcidity, residualSugar and density for non-normalised data, min-max normalised data and standardised data.

#### File strucutre needed to run code and use of each file
In directory have:  
- winequality-train.csv  
- winequality-test.csv  
- knn_results folder  
- pairwise_plots folder  

winequality-train.csv is the training dataset   
winequality-test.csv is the testing dataset   
knn_results folder will store all the csv's of the 1-NN classfications generated in this project   
pairwise_plots will store all of the pairwise plots generated in this project   

#### How to run this project
1) Ensure you have Jupyter Notebook installed
2) Press Run All at the top of the Jupyter Notebook
3) The program will run through all of the code and the accuracies of the 1-NN classfications and pairplots will be printed and shown
4) The csv's of the 1-NN classifcations will be stored in the knn_results folder
5) The png's of the pairplots will be sotred in the pairwise_plots folder