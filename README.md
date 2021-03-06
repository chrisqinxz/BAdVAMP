###  Bilinear Adaptive Vector Approximate Message Passing (BAdVAMP) [IEEE](https://ieeexplore.ieee.org/document/8712432), [arxive](https://arxiv.org/pdf/1809.00024.pdf)

BAdVAMP is an algorithm based on [VAMP](https://ieeexplore.ieee.org/document/8006797) to recover b and x from measurements y=A(b)x + w, where w is white Gaussian noise and A(b) is of the form A(b) = A0 + b1\*A1 + ... + bk \* Ak with known matrices A0, ..., Ak. 

There are two example files provided,

demo_CSMU.m : Compressive Sensing with Matrix Uncertainty (CSMU) problem 

demo_DL.m   : Dictionary Learning problem


**Note**: before runnning the files make sure that the [gampmatlab](https://sourceforge.net/projects/gampmatlab/) toolbox is added to Matlab's path. 
