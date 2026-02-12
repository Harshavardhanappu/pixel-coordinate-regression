# pixel-coordinate-regression
Deep learning model to predict pixel coordinates from 50x50 grayscale images using CNN regression.
Pixel Coordinate Regression using CNN
Overview

This project implements a Convolutional Neural Network (CNN) to predict the (x, y) coordinates of a single activated pixel in a 50x50 grayscale image.

The problem is formulated as a supervised regression task.

Problem Statement

Given a 50×50 grayscale image where exactly one pixel has value 255 and all others are 0, predict the coordinates of that pixel.

Approach

Synthetic dataset generation

Normalized coordinate regression

CNN architecture with BatchNorm and Dropout

MSE loss and Adam optimizer

Quantitative and qualitative evaluation

Results

Stable training convergence

Pixel-level localization performance evaluated using Euclidean error

Visualization confirms spatial learning behavior

Dependencies
pip install torch numpy matplotlib

How to Run

Open the Jupyter Notebook and execute all cells sequentially.
