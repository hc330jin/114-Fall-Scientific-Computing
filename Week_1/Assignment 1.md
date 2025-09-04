# Assignment 1
## Question 1
Show that $\sum_{i=0}^n l_i(x)=1$, where $l_i(x)=\prod_{j=0, j\ne i}^n\dfrac{x-x_j}{x_i-x_j}$

### Solution
Consider that we want to interpolate the constant function $f(x)=1$, then we have
$$1=\Pi_n f(x)=\sum_{i=0}^n 1\cdot l_i(x)$$

## Question 2
Show that $\omega_{n+1}^\prime(x_i)=\dfrac{1}{w_i}$

### Solution
Recall that $\omega_{n+1}(x)=\prod_{i=0}^n (x-x_i)$.

Then $\omega_{n+1}^\prime(x)=\sum_{i=0}^n\prod_{j=0, j\ne i}^n (x-x_j)$.

$\omega_{n+1}^\prime(x_i)=\prod_{j=0, j\ne i}^n (x_i-x_j)=\dfrac{1}{w_i}$

## Question 3
Reproduce Runge phenomenon.
