# cancerPrediction
author: yosep kim


### Cancer Prediction Using Decision Trees and Random Forest

- make a bootstarp sample of the original “Training” Dataset (build in part(b)) with the
size of bootstarp_size = 0.8*(Size of the original dataset). You can use the following
command to generate a random bootstrap dataset (“i" is the variable of the loop, so
the random_state changes in each iteration):
resample(X_train, n_samples = bootstarp_size , random_state=i , replace = True)
- Define and train a new base decision tree classifier on this dataset in each iteration:
Base_DecisionTree = DecisionTreeClassifier(random_state=2).
- Test “this base classifier” on the original “Testing” Dataset build in part(b), and save
the prediction results for all testing samples.
- Perform Voting to make the final decision on each data sample based on the votes of
all 19 classifiers.
Finally, calculate and report the accuracy of your Bagging method.

![Screenshot](blob/Capture.png)
<!-- ![myimage-alt-tag](../img/Capture.png) -->