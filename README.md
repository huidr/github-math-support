## Github's Math Support

Math expressions can be rendered natively in Github markdown using the usual math delimiters from TeX/LaTeX.

### Examples: Inline

Let $A$ and $B$ be any two sets such that $A \subset B$, then $A \cup B = B$ and $A \cap B = A$.

Let $p$ and $q$ are primes. Then $pq + 1$ is a perfect square if and only if $p$ and $q$ are twin primes.

### Examples: Display

The formal derivative on polynomial rings obeys:

$$ D\left( a_n \prod_{i=1}^n (t-\alpha_i)^{k_i} \right) = a_n \sum_{i=1}^n k_i (t-\alpha_i)^{k_i - 1}.$$

### Restrictions

Environments are not supported yet.

This is a matrix: 
\begin{pmatrix}
 -1 & 2 & 1 & 0 \\
 0  & 1 & -1 & 1 \\
 1 & -1 & 2 & 0 \\
 -1 & 2 & 0 & 1.
\end{pmatrix}
