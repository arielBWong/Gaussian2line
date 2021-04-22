# Gaussian2line

This is to record thought process on project n-dimentional Gaussian to a line.

My problems exposed includes: inference ability on linear algebra is close to zero. I don't know how to use vector operators. 

https://math.stackexchange.com/questions/1385624/projection-of-gaussian-distribution-along-a-vector

https://www.stat.cmu.edu/~cshalizi/uADA/12/lectures/ch14.pdf

For my projection code, I use the above inference results. There are still a few questions unclear. 

(1) Projection line:  how to project to v2?

![referenceline](https://github.com/arielBWong/Gaussian2line/blob/main/images/referencelines.png)

![x multi-variant gaussian](https://github.com/arielBWong/Gaussian2line/blob/main/images/x.png)

(2) New random variable:  Projection creates a new random variable (which is a scalar random variable), which can be represented as follows. 
With this new random variable representation, we can infer the mean and variance of this new Gaussian distribution.

![reference line presentation](https://github.com/arielBWong/Gaussian2line/blob/main/images/linereps.png)

(3)  The inference process 

![mu inference](https://github.com/arielBWong/Gaussian2line/blob/main/images/mu.png)


![sigma square inference](https://github.com/arielBWong/Gaussian2line/blob/main/images/sigma.png)
