---
title: 'Introduction of R'
description: 'Introduction of R'
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

1. Define a vector with values (5, 2, 11, 19, 3, -9, 8, 20, 1). Calculate the sum, mean, and standard deviation.
2. Re-order the vector from largest to smallest, and make it a new vector.
3. Convert the vector to a 3*3 matrix ordered by column. What is the sum of first column? What is the number in column 2 row 3? What is the column sum?

4. Download the CustomerData to your working directory. Load it to R.

- How many rows and columns are there?

- Extract all variable names.

- What is the average “Debt to Income Ratio”?

- What is the proportion of “Married” customers?

`@instructions`


`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}

```

`@solution`
```{r}
z <- c(1, 3, 5, 7)

z + 2
z * 2

z2 <- c(2,4,6,8)

z3 <- c(z, z2)
z3
A <- matrix(data = z3, nrow = 2, ncol = 4, byrow = T)

t(A)
t(A) %*% A

A[1,]
A[,3]
A[2,3]
A

```

`@sct`
```{r}

```
