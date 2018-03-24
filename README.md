# Face Detection with SVM

### This is my submission to the Machine Learning (CSE 512) HW 2, detecting upper bodies using HOG features

#### 1. SVM using Stochastic Gradient Descent
The file question3.m holds the code for this method. The SGD method is written from scratch. <br/>
The SVM formulation used is: Crammer and Singer's multiclass SVM (https://www.csie.ntu.edu.tw/˜cjlin/papers/multisvm.pdf)

#### 2. SVM using Quadprog solver
The file question4.m holds the code for this method. The SVM is formulated as a Quadratic Programming problem and then passed on to quadprog
