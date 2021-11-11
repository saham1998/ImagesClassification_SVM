# Images Classification Using SVM



## 
Tools Used
- → Python syntax
- → Pandas library for data frame
- → Support vector Machine(svm) from sklearn (a.k.a scikit-learn) library
- → skimage library for reading the image
- → matplotlib for visualization purpose

Some of the key parameters in SVM are:
→ Gamma : defines how far the influence of single training examples reaches values leads to biased results.
→ C : Controls the cost of miscalculations
Small C — makes the cost of misclassification LOW
Large C — makes the cost of misclassification HIGH
→ Kernel : SVM algorithms use a set of mathematical functions that are defined as the kernel.




## Process
It is one of the ways of machine learning where the model is trained by input data and expected output data.
To create such a model, it is necessary to go through the following phases:
1.Taking input
2. Model construction
3. Model training
4. Model testing
5.Model evaluation




## Model construction:
In this project case, the model is Support vector machine.
The algorithm for model construction looks like this:
1. Create a support vector classifier:
→ svc=svm.SVC()


## Model training: 
The data is split into two categories: training data and testing data. Training data is used to train the model whereas testing data is used to test the trained model.
For splitting the data into training and testing, train_test_split() from sklearn library is used.
Model is trained using training data in this way
→ model.fit(training_data,expected_output)

Mo
## Model testing: 
Now the model is tested using testing data in this way
→ model.predict(testing_data)
