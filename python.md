# Python notes

## Tools
Jupyter is a very fancy and handy tool for python programing. Jupyter notebook enables coding and result output in the browser.

## Libraries

+ Matplotlib
+ Pillow
+ Numpy
+ Scipy
+ Pandas
+ Scikit-learn
+ Scikit-image


## Tricks
```
import os
clear = lambda : os.system("cls") # for Windows, or
clear = lambda : os.system("clear") # for Unix-like
clear() # This clear the terminal
```

## Numpy
To calculate derivative of a function y = f(x), using the np.diff function on y and x, then divide the two difference, i.e. y' = dy/dx. 
Notice: each time a diff is made, the data number decreses 1. This is important if using the x and y' to plot, which needs the same shape of the two variables.