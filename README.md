# cancerPrediction


### Cancer Prediction Using Decision Trees and Random Forest
Bagging Accuracy 0.822222222222

AdaBoost: 0.933333333333

AdaBoost accuracy with cross validation: 0.929464285714

Accuracy Random Forest:  0.955555555556

RandomForest accuracy with cross validation: 0.929464285714

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


author: yosep kim

github.com/cowboyuniverse

<!-- ![Screenshot](https://github.com/cowboyuniverse/cancerPrediction/blob/master/blob/Capture.PNG) -->

![Screenshot](Capture.png)
<!-- ![Alt TEXT](blob/Capture.png?raw=true "Title")
![Image description](blob/Capture.png)
![myimage-alt-tag](blob/Capture.png)
![Alt TEXT](Capture.png?raw=true "Title")
![Image description](Capture.png)
![myimage-alt-tag](Capture.png) -->