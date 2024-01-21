# Multi-class_Classification_and_Neural_Networks

Introduction

In this exercise, you will implement one-vs-all logistic regression and neural networks to recognize hand-written digits. Before starting the programming exercise, we strongly recommend watching the video lectures and completing the review questions for the associated topics. 

To get started with the exercise, you will need to download the starter code and unzip its contents to the directory where you wish to complete the exercise. If needed, use the cd command in Octave/MATLAB to change to this directory before starting this exercise.

You can also find instructions for installing Octave/MATLAB in the \Environment Setup Instructions" of the course website. Files included in this exercise ex3.m - Octave/MATLAB script that steps you through part 1 ex3 nn.m - Octave/MATLAB script that steps you through part 2 ex3data1.mat - Training set of hand-written digits ex3weights.mat - Initial weights for the neural network exercise submit.m - Submission script that sends your solutions to our servers displayData.m - Function to help visualize the dataset fmincg.m - Function minimization routine (similar to fminunc) sigmoid.m - Sigmoid function

1. lrCostFunction.m - Logistic regression cost function
2. oneVsAll.m - Train a one-vs-all multi-class classifier
3. predictOneVsAll.m - Predict using a one-vs-all multi-class classifier
4. predict.m - Neural network prediction function
5. indicates files you will need to complete
   
Throughout the exercise, you will be using the scripts ex3.m and ex3 nn.m. These scripts set up the dataset for the problems and make calls to functions that you will write. You do not need to modify these scripts. You are only required to modify functions in other files, by following the instructions in this assignment.
