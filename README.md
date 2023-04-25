# Dynamical-Systems

Hi, my name is Alex and i am a pure and applied mathamatics student at Concordia Univerity.

This is my repository for all works pertaining to my class on Dynamical Systems. 
Each folder pertains to a specific topic related to the course material.

## Assignment 1 - Dynamic Mode Decomposition (DMD)

The goal of this assignment is to use Dynamic Mode Decomposition (DMD) to analyze two videos and isolate static and critical information. The method we will use involves the creation of a low-rank Singular Value Decomposition (SVD), which results in a DMD, which provides us with all of the necessary information to achieve our intended goal, which is to reconstruct the frames of this video and capture the motion of images against a static background. My intended audience is my graders and my future
self.

## Assignment 2 - SINDy

The goal of this assignment is to use video data from three different cameras to extract mass positions from video frames in order to perform the Principal Component Analysis (PCA) method. After applying PCA to the mass positions, extract the time evolution from only the first two dominant principal components. Then, using the Sparse Identification of Nonlinear Dynamics (SINDy) method, try to find the equations of motion that govern the dynamics of this system.

## Assignment 3 - Neural Networks (NN)

The goals that were set by this assignment were to establish the loss function that leads to the best predictions, to assess how many time steps the prediction remains correct, and to determine whether the recurrent neural networks (RNNs) that are properly trained to predict data. This is accomplished by employing ordinary differential equations, specifically the Lorenz equations, to train RNNs to take data from one time step to the next using the parameter ρ. To obtain the optimum error approximation, many loss functions were explored to forecast shifting data from one time step to the next.

## Final Project - Origami

This study has the aim of tracking and analyzing the motion of origami as the four corners of the paper fold into the traditional crane, using Principal Component Analysis (PCA) and Sparse Identification of Nonlinear Dynamics (SINDy) on three videos at the x -, y-, and z -axes. This is accomplished by approximating the motion of the folds in space and time, through the SINDy algorithm. Particularly, it was found that one principal component is typically required to do so up to some error, most likely due to tracking method error. Furthermore, model comparison is explored organically due to the symmetry of the origami crane.

My professor is Jason Bramburger and his github can be found here: https://github.com/jbramburger/DataDrivenDynSyst.git

Disclaimer: Everything is a work in progress, some lines of code may not work.
