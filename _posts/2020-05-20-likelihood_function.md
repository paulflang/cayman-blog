---
layout: post
title: "Likelihood function"
---
The likelihood function is a function of parameters **&theta;** at fixed data **X**. It tells you what is the probability density of the data, given the parameters: P(**X**\|**&theta;**).  
If you integrate the likelihood function over all parameters, you do not necessarily get 1. Hence, the likelihood function is not a probability density function.

Bayesian statistics assumes that a prior probability distribution of the parameters P(**&theta;**) exists. By multiplying this prior probability density function with a likelihood function (and a normalising constant 1/P(**X**)) we get a probability density function of **&theta;**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![](https://latex.codecogs.com/gif.latex?P%28%5Ctheta%7CX%29%20%3D%20P%28X%7C%5Ctheta%29%20*%20%5Cfrac%7BP%28%5Ctheta%29%7D%7BP%28X%29%7D)

that integrates over the parameters **&theta;** to 1.
