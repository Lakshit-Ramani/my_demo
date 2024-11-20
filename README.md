# my_demo
My first step towards git and github.
Author-Lakshit 


# Vector Dot-Product Implementation

This repository contains an implementation of the vector dot-product algorithm.

def dot_product(A, B):
    if len(A) != len(B):
        raise ValueError("Vectors must be of the same length.")
    return sum(a * b for a, b in zip(A, B))

### Example usage
A = [1, 2, 3]
B = [4, 5, 6]
result = dot_product(A, B)
print("Dot product:", result)

