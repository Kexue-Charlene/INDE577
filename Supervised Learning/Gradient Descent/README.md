# Gradient Descent
Gradient Descent is an optimization algorithm, which is an algorithm that can be used for optimizing our cost function, in order to make our data model more accurate and less error prone. In machine learning, we use gradient descent to update the parameters of our model. Parameters refer to coefficients in Linear Regression and weights in neural networks.


Gradient descent is a optimization algorithm for finding a local :minimum of a differentiable function. The extreme right side of graph is the cost function that we are using it to apply gradient descent in order to minimize it

<td> <img src="https://miro.medium.com/max/700/1*Mvsa_fuVlG6U2yVm6BvMNA.png" width="500"/> </td>

Let's assume we are standing at the top of the hill and we want to get to the foohill as soon as possible. However, we don't want to take risk by taking the unknown tracks in the hill at first, so we get to the foothill from the visible path. The foothill here is called global optimization factor (minimiz cost function). For each step we take was marked by "X" in the hill. The paths we always change repersent changing cost function, so that we can get down of the hill and reach out the minimiaztion cost function successfully.

<td> <img src="https://miro.medium.com/max/700/1*f9a162GhpMbiTVTAua_lLQ.png" width="500"/> </td>

For the purpose of illustration we will use  𝐽(𝑤), function that we want to minimize, as a function of one variable.
Gradient Descent starts at an initial parameter and begins to take values in the steepest downhill direction. Function 𝐽(𝑤,𝑏) is convex, so no matter where we initialize, we should get to the same point or roughly the same point.
After a single step, it ends up a little bit down and closer to a global otpimum because it is trying to take a step downhill in the direction of steepest descent or quickly down low as possible.

The learning rate 𝛼 controls how big step we take on each iteration of Gradient Descent.

Derivative, slope of a function at the point, is basically the update of the change you want to make to the parameters 𝑤. 

If  the derivative is positive,  𝑤 gets updated as 𝑤  minus a learning rate 𝛼  times the derivative ” 𝑑𝑤 “
When derivative is positive, so we end up subtracting from 𝑤 and taking a step to the left. Gradient Descent would make your algorithm slowly decrease the parameter if you have started off with this large value of 𝑤.

When the derivative is negative,  the Gradient Descent update would subtract 𝛼 times a negative number, and so we end up slowly increasing 𝑤 and we are making 𝑤 bigger and bigger with each successive iteration of Gradient Descent. So, whether you initialize 𝑤 on the left or on the right, Gradient Descent would move you towards this global minimum.

<td> <img src="https://media5.datahacker.rs/2018/06/word-image-30.jpeg" width="500"/> </td>

# Reference 
Wikipedia, Gradient descent, Nov 30th.2021.https://en.wikipedia.org/wiki/Gradient_descent

Shreedhar,vellayaraj. Gradient Descent for Linear Regression. Oct 6th.2017. https://medium.com/@Shreedharvellay/gradient-descent-for-linear-regression-8e1389058d07

Data Hacker, #003B Gradient Descent,Oct 22nd, 2018. https://datahacker.rs/gradient-descent/
