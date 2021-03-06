# Genetic Algorithm implementations in Python
Implementation of Genetic algorithms for applications:
- Optimizing continuous functions
- Feature selection for Machine learning problems
- Hypertuning Machine learning algorithms
## Optimizing the Eggholder function
The Eggholder function is given by: 
  
      
&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp;![f(x, y)=-(y+47) \cdot \sin \sqrt{\left|\frac{x}{2}+(y+47)\right|}-x \cdot \sin \sqrt{|x-(y+47)|}](https://render.githubusercontent.com/render/math?math=f(x%2C%20y)%3D-(y%2B47)%20%5Ccdot%20%5Csin%20%5Csqrt%7B%5Cleft%7C%5Cfrac%7Bx%7D%7B2%7D%2B(y%2B47)%5Cright%7C%7D-x%20%5Ccdot%20%5Csin%20%5Csqrt%7B%7Cx-(y%2B47)%7C%7D)
![Eggholder Function](Images/Egg.png)
</br>
Optimization results:
<p align="center">
  <img width="600" height="400" src="Images/Opti_graph.png">
</p>


## Feature Selection for Machine Learning
We work with the Friedman 1 dataset provided by Scikit-learn: [Friedman1 Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_friedman1.html)
</br>
Feature Selection results:  
</br>
<p align="center">
  <img width="600" height="400" src="Images/ML_Plot.png">
</p>
