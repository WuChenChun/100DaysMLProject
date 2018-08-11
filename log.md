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
* Reducing Loss : Instead of getting a formula to predict an exact solution, ML using iterative approach by evaluating Loss to train model and find solution.
* Learning Rate (step size) : a scalar gradient descent algorithm will multiply by to determine next step.
* Gradient of function : the vector of partial derivatives with respect to all of the independent variables.
* Batch : the total number of examples you use to calculate the gradient in a single iteration.
* Stochastic Gradient Descent(SGD) : Only a single example (a batch size of 1) per iteration.
* mini-batch SGD : A compromise between full-batch iteration and SGD. A mini-batch is typically between 10 and 1,000 examples
```
<p align ="center">
<img src="https://latex.codecogs.com/svg.latex?f(x,y)%20=%20e^{2y}\sin(x)" />
<br>
<img src="https://latex.codecogs.com/svg.latex?\nabla%20f(x,y)%20=%20\left(\frac{\partial%20f}{\partial%20x}(x,y),%20\frac{\partial%20f}{\partial%20y}(x,y)\right)%20=%20(e^{2y}\cos(x),%202e^{2y}\sin(x))" />
</p>
