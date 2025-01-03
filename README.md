# My_demo
My first step towards git and github.
Author-Lakshit 

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


:point_right:[Go to Mathematical Expression](#mathematical-expression)


## images

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

## Lists

* Item 1
+ Item 2
- Item 3

1. First item
2. Second item
3. Third item

- Fruits
  - Apples
  - Bananas
- Vegetables
  - Carrots
  - Broccoli

- [x] Implement dot product function
- [ ] Write unit tests
- [ ] Document the code

## Adding Emojis

This PR looks great - it's ready to merge! 

:smile:
:laughing:
:sweat_smile:
:point_up_2:
:leg:
:brain:

## Footnotes

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
This is a second line.

## Alerts

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## Ignoring Markdown formatting

Let's rename \*our-new-project\* to \*our-old-project\*.

## Tables

| Name     | Age | Occupation  |
| :---     |:---:|      ---:   |
| Alice    | 25  | Engineer    |
| Bob      | 30  | Designer    |
| Charlie  | 22  | Developer   |





# Vector Dot-Product Implementation

This repository contains an implementation of the vector dot-product algorithm.

def dot_product(A, B):
    if len(A) != len(B):
    <!-- This content will not appear in the rendered Markdown -->
        raise ValueError("Vectors must be of the same length.")
    return sum(a * b for a, b in zip(A, B))

### Example usage
A = [1, 2, 3]
B = [4, 5, 6]
result = dot_product(A, B)
print("Dot product:", result)

## Time complexities for dot product using various different methods..

| Version   | Time Complexity | Space Complexity | Description                           |
|-----------|-----------------|------------------|---------------------------------------|
| Version 1 | O(n)            | O(1)             | Simple dot-product calculation        |
| Version 2 | O(n log n)      | O(n)             | Optimized using dynamic programming  |
| Version 3 | O(n)            | O(n)             | Parallelized version using numpy     |


<p>The dot product of two vectors <b>A</b> and <b>B</b> is Mathematically calculated as:</p>
<p><b>A</b> &middot; <b>B</b> = <i>&sum;</i><sub>i=1</sub><sup>n</sup> <b>A<sub>i</sub></b> &middot; <b>B<sub>i</sub></b></p>