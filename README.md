# Image Completion Using Low Tensor Tree Rank and Total Variation Minimization

Tensor completion recovers missing entries of multiway data. Most of the current methods exploit the low-rank tensor structure for image completion applications. In this paper, we simultaneously exploit the globally multi-dimensional structure and locally piece-wise smoothness to further enhance the performance. In the proposed optimization model, the low tensor tree rank minimization is used for the global data structure, and the total variation minimization is used for the local structure. Two kinds of total variation functions are discussed. The optimization problem is transformed into several sub-problems by alternating direction method of multipliers. The sub-problem on low tensor tree rank minimization is solved by singular value thresholding, and the sub-problem on total variation minimization can be solved by soft thresholding. Numerical experiments on color images and light field images demonstrate that the proposed
method outperforms most of the state-of-the-art methods in terms of recovery accuracy and computational complexity.


------------------------------------------------------
# demo

demo_test.m for color image completion

------------------------------------------------------
# setting up

adding path as follows:

addpath('mylib');
addpath('htucker_1.2');
addpath('tensorlab');

------------------------------------------------------
# notes

We also provide introducotry slides for quickly understanding our algorithm. 
