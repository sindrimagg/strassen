# Finding a Strassen like multiplication for commutative and symmetric matrices
When commutative and symmetric matrices are multiplied the result is also symmetric. Using this fact we can reduce the number of inner multiplications needed to compute the matrix multiplication. This is similar to[Strassen's algorithm](https://en.wikipedia.org/wiki/Strassen_algorithm) but for this structure. I made a simple script in Sage to find such an algorithm.
 
 There are two notebooks in this repository one is for the case when squaring a symmetric matrix and the other for the general case. They are essentially identical. 
