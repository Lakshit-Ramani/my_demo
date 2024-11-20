## my_demo
My first step towards git and github.
Author-Lakshit 

## Mathematical Expression

# Vector Dot-Product Implementation

This repository contains an implementation of the vector dot-product algorithm.

## Styling Text
 
The **dot product** is also called the scalar product.

The _dot product_ is also called the scalar product.

~~This text was mistaken text.~~

**This text is _extremely_ important**

***All this text is important***

This is a <sub>subscript</sub> text

This is a <sup>superscript</sup> text

This is an <ins>underlined</ins> text

## Quoting text

Text that is not a quote

> Text that is a quote

## Links

This site was built using [GitHub Pages](https://pages.github.com/).


[Go to Mathematical Expression](#mathematical-expression)


def dot_product(A, B):
    if len(A) != len(B):
        raise ValueError("Vectors must be of the same length.")
    return sum(a * b for a, b in zip(A, B))

### Example usage
A = [1, 2, 3]
B = [4, 5, 6]
result = dot_product(A, B)
print("Dot product:", result)

