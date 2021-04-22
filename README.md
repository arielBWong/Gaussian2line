# Gaussian2line

This is to record thought process on project n-dimentional Gaussian to a line.

My problems exposed includes: inference ability on linear algebra is close to zero. I don't know how to use vector operators. 

https://math.stackexchange.com/questions/1385624/projection-of-gaussian-distribution-along-a-vector

For my projection code, I use the above inference results. There are still a few question unclear. 

(1) Projection line:  I can understand that if a projection line starts from zero as in following line v1, but what if a different line that does not pass zeros like v2?

![referenceline](https://github.com/arielBWong/Gaussian2line/blob/main/images/referencelines.png)

(2) Inference process: A projection result is represented as follows, **NOT** reference line. vT is assumed the same size as the given n-dimensional Gaussian process.  What causes confusion is that y is **NOT** on the n-dimensional space. y becomes an random variable. Only x is on the n-dimensional space. vT is assumed of length 1 unit.  

![reference line presentation](https://github.com/arielBWong/Gaussian2line/blob/main/images/linereps.png)

(3)
