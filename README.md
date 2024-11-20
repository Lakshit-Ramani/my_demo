# my_demo
My first step towards git and github.
Author-Lakshit 


# Vector Dot-Product Implementation

This repository contains an implementation of the vector dot-product algorithm.

## Mathematical Expression

The dot product of two vectors \( \mathbf{A} \) and \( \mathbf{B} \) is given by:

\[
\mathbf{A} \cdot \mathbf{B} = \sum_{i=1}^{n} A_i \cdot B_i
\]

def dot_product(A, B):
    if len(A) != len(B):
        raise ValueError("Vectors must be of the same length.")
    return sum(a * b for a, b in zip(A, B))

### Example usage
A = [1, 2, 3]
B = [4, 5, 6]
result = dot_product(A, B)
print("Dot product:", result)

