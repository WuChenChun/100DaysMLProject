# 100 Days Machine Learning Log

## Day 1 - Aug/09/2018
- Today's Progress : Set up Github and refresh how to use github.
- Thought : Need to find some interested project to start it!
- Link of Resource : <a href="https://education.github.com/git-cheat-sheet-education.pdf">Github cheat sheet</a>

## Day 2 - Aug/10/2018
- Today's Progress : Start Google Crash Course, embedded Latex in the github.
- Thought : Regression vs Classification, MSE
- Link of Resource : <a href="https://developers.google.com/machine-learning/crash-course/">Google Crash Course</a>
- Summary :
```
* Regression : A Regression model predict continuous value, e.g. house price
* Classification : A Classification model predict discrete values, e.g. spam or not spam emails
* Mean Square Error(MSE) : Average of squared loss indicated the model prediction performance
```
<p align ="center">
<img src="https://latex.codecogs.com/svg.latex?MSE%20=\frac{1}{N}%20\sum_{(x,y)\in%20D}%20(y%20-%20prediction(x))^2" />
</p>

## Day 3 - Aug/11/2018
- Today's Progress : Google Crash Course
- Link of Resource : <a href="https://developers.google.com/machine-learning/crash-course/reducing-loss/video-lecture">Reducing Loss</a>
- Summary :
```
* Reducing Loss : ML using iterative approach by evaluating Loss to train model and find solution.
* Learning Rate (step size) : a scalar gradient descent algorithm will multiply by to determine next step.
* Gradient of function : the vector of partial derivatives with respect to all of the independent variables.
* Batch : the total number of examples you use to calculate the gradient in a single iteration.
* Stochastic Gradient Descent(SGD) : Only a single example (a batch size of 1) per iteration.
* mini-batch SGD : A compromise between full-batch iteration and SGD typically between 10 and 1,000 examples
```
<p align ="center">
<img src="https://latex.codecogs.com/svg.latex?f(x,y)%20=%20e^{2y}\sin(x)" />
<br>
<img src="https://latex.codecogs.com/svg.latex?\nabla%20f(x,y)%20=%20\left(\frac{\partial%20f}{\partial%20x}(x,y),%20\frac{\partial%20f}{\partial%20y}(x,y)\right)%20=%20(e^{2y}\cos(x),%202e^{2y}\sin(x))" />
</p>

## Day 4 - Aug/13/2018
- Today's Progress : Google Crash Course
- Link of Resource : <a href="https://developers.google.com/machine-learning/crash-course/first-steps-with-tensorflow/programming-exercises">First Step with TF</a>
- Link of Work :
  * <a href="Work/intro_to_pandas.ipynb"> Quick Introduction to pandas.</a>
  * <a href="Work/first_steps_with_tensor_flow.ipynb"> First Steps with TensorFlow.</a>
  * <a href="Work/synthetic_features_and_outliers.ipynb"> Synthetic Features and Outliers.</a>

## Day 5 - Aug/15/2018
- Today's Progress : Google Crash Course
- Link of Resource : <a  href="https://developers.google.com/machine-learning/crash-course/generalization/peril-of-overfitting">Generalization</a>
- Summary:
```
* Overfitting is due to training a model that more complex than necessary
* The less complex the model is, the more likely a good empirical result rather than fitting peculiarities of the sample
* Separate the dataset into train set and test set.
```

## Day 6 - Aug/16/2018
- Today's Progress : Google Crash Course
- Link of Resource : <a  href="https://developers.google.com/machine-learning/crash-course/training-and-test-sets/splitting-data">Training and Test sets</a>
- Summary:
```
* training sets : a subset of data to train model (80%)
* test sets : a subset of data to test and evaluate model (20%)
```
- Link of Work :
  * <a href="Work/tensorflow_programming_concepts.ipynb">Tensorflow Programming Conectps. </a>
  * <a href="Work/creating_and_manipulating_tensors.ipynb"> Creating and manipulating tensors. </a>


## Day 7 - Aug/17/2018
- Today's Progress : Google Crash Course
- Link of Resource : <a  href="https://developers.google.com/machine-learning/crash-course/validation/another-partition">Validation</a>
- Link of Work :
  * <a href="Work/validation.ipynb"> Validation. </a>

## Day 8 - Aug/19/2018
- Today's Progress : Google Crash course
- Link of Resource : <a href="https://developers.google.com/machine-learning/crash-course/representation/feature-engineering"> Representation - Feature Engineering </a>
- Summary:
```
* One-Hot encoding : transforming the text data into numerical data with each column has 0/1 representing the feature.
* Sparse Representation : It only store nonzero value to prevent inefficient store, computation for one-hot encoding.
* Quality of Good Feature
  (1) A good feature usually appear more than 5 times so that model can make prediction with it.
  (2) A good feature should have an obvious and clear meanings.
  (3) Don't mix "magic" value with actual data (e.g. using -1 to represent None where actual is between 0 to 1)
  (4) The definition of the feature shouldn't change over time.
* Cleaning data
  (1) Scaling Feature value, e.g. standarize example (from 100 to 900 -> 0 to 1)
  (2) Scaling with Z score : scalableValue = (value - mean)/stddev, most of value will be between -3 to 3
  (3) Binning value : some feature like latitude doesn't have linear relationship with house price -> use bin value.
```
