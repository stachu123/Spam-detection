Simple Spamdetection model trained and tested on spamassasin dataset.

Importing and transforming data for model reused mostly from https://github.com/ageron/handson-ml2/blob/master/03_classification.ipynb, 
modified with BeatifulSoup module to transform HTMl to plain text.

Model was an excercise in "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow. Concepts, Tools, and Techniques to Build Intelligent Systems" book written by Geron Aurelien.
I've used Grid search to choose best model for the data from Logistic Regression, SVM, Random Forest and XGBoost.
then i've tried Randomized search CV on Random Forest to try to improve Precision and Recall of predictions.

