# Python-Fundamentals
## Pandas
    pip install pandas 
    import pandas as pd
    print(pd.__version__)
### FEATURES:
- Pandas were initially developed by Wes McKinney in 2008; Chang She, joined as the second major contributor to the library in 2012
- Fast and efficient for manipulating and analysing data.
- Data from different file objects can be loaded.
- Easy handling of missing data (represented as NaN) 
- Data manipulation (column insert/delete, dataset merging and joining, reshaping and pivoting of data sets etc. can be performed)
## Numpy
### INSTALLATION:    
    pip install numpy
    import numpy as np
    print(np.__version__)
 
### FEATURES:
- NumPy stands for Numerical Python 
- NumPy can be used to perform a wide variety of mathematical operations on arrays. 
- It also has functions for working in domain of linear algebra.
- NumPy arrays facilitate advanced mathematical and other types of operations on large numbers of data. 
- NumPy was created in 2005 by Travis Oliphant. 
- It is an open source project and we can use it freely. 
- NumPy is written in C and so has a faster computational speed. 

### DIFF. PANDAS & NUMPY:
- When we have to work on Tabular data, we prefer the pandas module and when we have to work on Numerical data, we prefer the numpy module. 
- The powerful tools of pandas are Data frame and Series whereas the powerful tool of numpy is Arrays. 
- Pandas consume more memory. Numpy is memory efficient. 
- Pandas has a better performance when number of rows is 500K or more.Numpy has a better performance when number of rows is 50K or less. 
- Indexing of the pandas series is very slow as compared to numpy arrays. Indexing of numpy Arrays is very fast. 
- Pandas offers two dimensional table object called DataFrame. Numpy is capable of providing multi-dimensional arrays.
## SciPy
    pip install scipy
    import scipy as sp
    print(sp.__version__)
### FEATURES:    
- SciPy is a scientific computation library that uses NumPy underneath.
- SciPy stands for Scientific Python.
- It provides more utility functions for optimisation, stats and signal processing.
- SciPy was created by NumPy's creator Travis Olliphant.
- SciPy is written in Python and so has a slower execution speed compared to numpy but vast functionality

## scikit-learn
    pip install scikit-learn
    import scikit-learn as sklearn
    print(sklearn.__version__)
    
 ### FEATURES:
 - scikit-learn is a Python module for machine learning built on top of SciPy
 - sklearn library contains a lot of efficient tools for ML and statistical modeling including classification, regression, clustering and dimensionality reduction
## Matplotlib
    pip install matplotlib
    import matplotlib.pyplot as plt
    print(plt.__version__)
### FEATURES:
- Matplotlib for creating static, animated, and interactive visualizations in Python
    
    from matplotlib import pyplot as plt # importing matplotlib module 
  
    x = [5, 2, 9, 4, 7] # x-axis values
    
    y = [10, 5, 8, 4, 2] # y-axis values
  
    plt.bar(x,y) # bar plot
    
    plt.show() # show plot
    
    
## Machine learning
### Linear Regression in Python with Scikit-Learn

![](images/ML types.png)


    
    
