---
layout: exercise
topic: Matrix operations in R
title: Matrix Operations
language: R
---

Matrix operations have many uses in modeling, and can be performed in R.

1. Create a matrix called `A` that has three rows and two columns. This matrix should include numbers 1:6 (the first row should consist of `[1 2]`, the second row should consist of `[3 4]` and so on.
2. Create a matrix called `B` that has three rows and two columns using the code below, and then multiply `A` time `B` using element-wise multiplication.
```
B <- matrix(c(0, 4, 7, 2, 3, 1), nrow = 3)
```
3. Try to multiply A and B using matrix multiplication. What error do you get?
4. You get an error in step 3 because matrix multiplication can only be applied if the inner dimensions match. Here `A` is a 3 x 2 matrix. We can successfully multiply A by any matrix with 2 x m dimensions (where m is any number of columns). Transpose matrix `B` to a 2 x 3 matrix, then multiply `A` by the transpose of `B`.
5. Create a square matrix called `C` using the code below, and then calculate the inverse of matrix `C`.
```
C <- matrix(1:4, nrow = 2)
```
