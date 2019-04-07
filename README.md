# mnist_tutorial
A tutorial for mnist hand writen digit classification using sklearn, pytorch and keras.

# Code structure
* [`numpy_matplotlib_sklearn.ipynb`](numpy_matplotlib_sklearn.ipynb): for numpy, matplotlib and sklearn.
* [`pytorch.ipynb`](pytorch.ipynb): for pytorch.
* [`keras.ipynb`](keras.ipynb): for keras.
* Reference solution: (not published yet)
    * [`numpy_matplotlib_sklearn_solution.ipynb`](numpy_matplotlib_sklearn_solution.ipynb)
    * [`pytorch_solution.ipynb`](pytorch_solution.ipynb)
    * [`keras_solution.ipynb`](keras_solution.ipynb)

# Requirements
Code tested on following environments, other version should also work:
* linux system (ubuntu 16.04) 
* python 3.6.3
* numpy 1.13.3
* matplotlib 2.1.0
* sklearn 0.19.1
* pytorch 0.4.1
* keras 2.1.2
* tensorflow

# For students from SJTU
Please read [HEAR](EE369.md).

# For Homework readme
I finished [`numpy_matplotlib_sklearn_solution.ipynb`] and [`pytorch_solution.ipynb`]    
Because I failed to fetch mnist data with sklear API, I use tensorflow API to load mnist data.    
- In sklearn part,   
  LogisticRegression got test score: 92.57%  
  BernoulliNB got test score: 84.13%  
  LinearSVC got test score: 91.80%  
  SVC  got test score:  94.46%   (It is too slow.......)
  
And in pytorch part, I designed a simple convolution neural network based on Vgg Net.  
It achieved **99.38%**  score on test set.  
Cheers!  
Convolution neural network is very powerful, just one epoch, it achieved remarkable precision.


