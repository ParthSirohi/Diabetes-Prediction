# Diabetes-Prediction
Here I have used Stacking of classifers to predict the whether or not the patient has diabetes. Stacking can be described as an ensemble learning technique where the predictions of multiple classifiers (referred as level-one classifiers) are used as new features to train a meta-classifier. The meta-classifier can be any classifier of your choice. 
I trained a Support Vector Classifier (SVC), Multi-layer Perceptron (MLP) classifier, Nu-Support Vector classifier (NuSVC), and a Random Forest (RF) classifier.
To stack them, I used the StackingCVClassifier from MLXTEND. I then tuned the classifiers individually and then stack them.
