# Curve Fitting With Python

Simply put, curve fitting is the process of finding a curve that best matches a series of observations. 
It mainly consists of two basic steps. Initially, we have to find an appropriate model to describe the 
relationship between a dependent variable, *y*, and an independent variable, *x*. Then, we need to estimate the optimal model parameters that best fit the given set of data points.

Curve fitting is one of the most widely used analysis tools in experimental physics. Machines output data, but they cannot infer any information about the underlying process that generated the data. 
Therefore, the experimentalist needs to find a model that approximates the behaviour of the physical system in question. 

Ιn this tutorial, we will see how to perform curve fitting with Python. Specifically, we will simulate a spectrum consisting of two Lorentzian peaks, fit a model, extract the optimal parameters, 
and plot the best curve. For this purpose, we will use the [LMfit](https://pypi.org/project/lmfit/) package, which ‘*provides simple tools to help us build complex fitting models for non-linear least-squares problems and apply these models to real data*’. 

This notebook is not an extensive tutorial; instead, it should be used as a quick-start guide to curve fitting. 
For more information, please refer to the official documentation and the resources listed in this file.

<p align="center">
  <img src="/Curve Fitting/Fitted_Spectrum.png" width="600" title="hover text">
</p>

## Task

You are an experimental physicist studying the emission properties of a new (and imaginary) material. The emission spectrum consists of two (slightly overlapping) peaks at approximately 402 and 404 nm. 
Your task is to fit the spectrum and extract the peak wavelength and [FWHM](https://en.wikipedia.org/wiki/Full_width_at_half_maximum) of each peak. 
Assume [Lorentzian lineshape](https://en.wikipedia.org/wiki/Cauchy_distribution) for both peaks.

## Resources Used

Python Version: 3.7<br>
Packages: lmfit (0.9.12), numpy (1.19.5), matplotlib (3.3.4), pandas (1.1.5), scipy.stats (1.5.4)<br>
Other Resources:
- [Data Fitting in Python Part II: Gaussian & Lorentzian & Voigt Lineshapes, Deconvoluting Peaks, and Fitting Residuals](http://www.emilygraceripka.com/blog/16), by Emily Ripka (Accessed: December 2020).
- [Curve Fitting With Python](https://machinelearningmastery.com/curve-fitting-with-python/), by Jason Brownlee (Accessed: December 2020).
