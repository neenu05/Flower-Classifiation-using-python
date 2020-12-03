# Flower Classification using Python and Machine Learning

It contains the code to classify the Flowers using Python. 

Run with Python 3.7.9 

## Summary of the project
* Global Feature Descriptors such as Color Histograms, Haralick Textures and Hu Moments are used on University of Oxford's FLOWER17 dataset.
* Classifiers used are Logistic Regression('LR'), Linear Discriminant Analysis('LDA'), K-Nearest Neighbors('KNN'), Decision Trees('CART'), Random Forests('RF'), Gaussian Naive Bayes('NB') and Support Vector Machine('SVM').


## `python organize_flowers17.py` 
                - Downloads Flowers17 Dataset and organizes training set in disk.
## `python global.py` 
                - Extracts global features from training set and stores it in disk.
## `python train_test.py` 
                - Predicts the image class using the trained model. (Test the images)

Tutorial for this project is available at - 
Image Classification using Python and Machine Learning [https://gogul.dev/software/image-classification-python]
https://github.com/Gogul09/image-classification-python
