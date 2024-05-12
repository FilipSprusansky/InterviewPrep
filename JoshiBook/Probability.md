#### Problem 3.6 
Suppose we have a fair coin, let N denote the number of tosses until we get H. Calculate mean and variance of N.

*Solution:*
We can use the law of total expectation: $E(X) = E(E(X|Y))$, where Y is the first toss.

$$
\begin{align}
E(X) &= pE(X|H) + (1-p)E(X|T) \\ 
&= p . 1 + (1-p)E(X+1) \\
&= p + E(X) + 1 - pE(X) - p \\
E(X) &= \frac{1}{p}\\
E(X^2) &= pE(X^2|H) + (1-p)E(X^2|T) \\
&= p.1 + (1-p)E((X+1)^2) \\
&= p + (1-p)(E(X^2) + 2E(X) + 1) \\
E(X^2) &= \frac{2-p}{p^2} \\
\text{Var}(X) &= E(X^2) - E(X)^2 = \frac{1-p}{p^2}
\end{align}
$$

*Subproblems:*

TODO


#### Problem 3.7
TODO

E(N) = 3

Var(N) = 2 (based on simulation)
