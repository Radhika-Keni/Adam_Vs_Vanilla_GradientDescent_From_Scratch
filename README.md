# Adam_Vs_Vanilla_GradientDescent_From_Scratch
Implement Adam and compare it with Vanilla GD


## Objective of this notebook
- Implement Adam and compare its convergence with that of Vanilla Gradient Descent
- Details of the **problem statement**  , **data set** ,  **summary of the code/solution**  , **sample output/Prediction** from the program and **final result** of the project are listed in the sections to follow.

## Problem Statement/Prologue
This Note book build upon our previous notebook "Vanilla Gradient Decsent From Scratch" which is present in my repository .In this notebook ,we build on top of that notebook , implement Adam and observe its effects on convergence.We jump staright into Adam , so if the reader needs more of a background on gradient descent then I would recommend going through the previous notebook(which has detailed comments on Gradient Descent)

## Data Description:
The dataset is manually created for the purpose of this exercise

## Domain:
Deep Learning :Proof of concept

## Summary of the Solution/Code:
- We implement Vanilla Gradient Descent on a dataset and log observations
- We implement Adam on the same data set and log observations
- We compare results and demostrate which algorithm is superior 
- Refer **python worksheet Adam_Vs_VanillaGD.ipynb** for the solution

## Visualizing Input :

![image](https://user-images.githubusercontent.com/68383273/209479217-1954188c-72ff-49d5-b8b0-cd940459b1f0.png)


The above image depicts the following
- We start at a random line (marked in RED)
- The BLUE line indicates the best fit line which is our target
- We need to arrive at this line through the Gradient Descent Algorithm
- Let us see how changing learning rate affects this convergence


## Result with Vanilla Gradient Descent :

![image](https://user-images.githubusercontent.com/68383273/212476615-513e8f7f-f762-490e-85c1-c4980dab0cba.png)
![image](https://user-images.githubusercontent.com/68383273/212476697-1e6fe1d2-b79c-47f4-b513-60cf479704fa.png)



## Result with Adam  :

![image](https://user-images.githubusercontent.com/68383273/212478214-cd60a2db-d1d4-4170-af90-dd65fccade7c.png)
![image](https://user-images.githubusercontent.com/68383273/212478242-97f1c383-cc76-400d-81ad-f1a9d497cbc3.png)




## Compare Results :
![image](https://user-images.githubusercontent.com/68383273/212478260-4e8e1818-76d6-4ff9-9e09-80e27a032ed9.png)





## References
The following references were used while creating this notebook:
- https://machinelearningmastery.com/adam-optimization-from-scratch/ by Jason Brownlee
- Post Graduation AI/ML Study Material by GL/UAT


