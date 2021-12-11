# K-Nearest Neighbors Classtering 
k-Nearest Neighbors (KNN), a supervised machine learning algorithm, can be used for either regression or classification tasks. In project, we will use KNN to do a classfication. 
KNN is a non-parametric algorithm which means that assumptions about the underlying distributions of the data is not needed.


In KNN, K is the number of nearest neighbors. K is generally an odd number if the number of classes is 2. 

KNN follows the steps listed below:
1. Calculate distance
2. Find closest neighbors
3. Vote for labels. 
<td> <img src="https://res.cloudinary.com/dyd911kmh/image/upload/f_auto,q_auto:best/v1531424125/KNN_final1_ibdm8a.png" width="800"/> </td>

## How can we determine the k? 
* Small number of k: the noise will have a higher influence on the result. 
                     low bias but high variance
* Large number of k: make it computationally expensive. 
                     lower variance but higher bias (smoother decision boundary)
Generally, data scientistes choose odd number if the number of class is even. 



<td> <img src="https://res.cloudinary.com/dyd911kmh/image/upload/f_auto,q_auto:best/v1531424125/KNN_final_a1mrv9.png" width="400"/> </td>

# Reference 
Avinash Navlani. Tutorials. KNN Classification using Scikit-learn. August 2nd,2018. https://www.datacamp.com/community/tutorials/k-nearest-neighbor-classification-scikit-learn
