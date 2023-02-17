---
{"dg-publish":true,"permalink":"/data-science/logit-and-normal-distribution-cdf/","tags":["gardenEntry"]}
---


```jupyter
import scipy.stats as st
import numpy as np
import matplotlib.pyplot as plt
import math

def sigmoid(x):
    return 1/(1+math.exp(-1*x))


x = np.arange(-10,10,0.1)
norm_y = st.norm.pdf(x)
sigmoid_y = [sigmoid(a)*(1-sigmoid(a)) for a in x]
plt.figure(figsize=(10,5))
plt.subplot(1,2,1)
plt.plot(x,norm_y,label='norm')
plt.plot(x,sigmoid_y,label='sigmoid')
plt.plot(x,st.logistic.pdf(x),label='sigmoid')
plt.legend()
plt.subplot(1,2,2)
plt.plot(x,st.norm.cdf(x),label='norm')
plt.plot(x,[sigmoid(a) for a in x],label='sigmoid')
plt.plot(x,st.logistic.cdf(x),label='sigmoid')

plt.legend()
plt.show()
```