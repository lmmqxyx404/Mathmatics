# linear algebra
## aim
Learning linear algebra is to study linear spaces.Planes and spaces are just special cases of n-dimensional vector spaces.

### partial chapters
linear equations
linearly dependent attribute
quadratic form
linear space and linear transformation

## basis
The basis of a vector space is always linearly independent.

## Quadratic homogeneous polynomial.
The term "n-variable quadratic form" refers to an n-variable quadratic homogeneous polynomial.
It can be seen as a generalization of quadratic curves and quadratic surfaces.

## tools
matrix and determinant。
The matrix plays an important role when studying linear transformations.


# determinant
### Inversion number
Inverse number, also known as the inversion number or the number of inversions, is a concept in mathematics related to permutations. In the context of a permutation of a set of numbers, an inversion occurs when two elements in the permutation are in reverse order compared to their natural order. `The inverse number of a permutation is the count of such inversions.` It is often used in combinatorics and the study of permutations.
$$
\text{The inversion number of a permutation } \sigma \text{ is denoted as } \textit{inv}(\sigma).\\ \tau(3,1,2)=2.  \\ \tau(3)+\tau(1)+\tau(2)=2+0+0 \\ (3,1) (3,2)
$$

### parity(even or odd permutation)


### The expansion of a determinant(n)
1. The result is the sum of the n! item of permutation.
2. row index is raw incremental sort. and the column index is the all permutation
3. pay attention to the symbol(positive or negative)

### features
1. swap the row can cause the value*-1.

# matrix
### difference
pay attention to a*A and a*|A|.
ab=a b

$$ \begin{vmatrix} \begin{pmatrix}A\end{pmatrix} * \begin{pmatrix}B \end{pmatrix} \end{vmatrix} = \begin{vmatrix} \begin{pmatrix} A \end{pmatrix} \end{vmatrix} * \begin{vmatrix} \begin{pmatrix}B \end{pmatrix} \end{vmatrix} $$ 



### notions
Symmetric matrix
Antisymmetric Matrix
Accompanying Matrix
Inverse matrix

### operations
- multiply
f(A)=(A+E)(A-E);

## Contracts and Similarities

# quadratic form
In mathematics, a quadratic form is a polynomial with terms all of degree two ("form" is another name for a homogeneous polynomial). For example,
is a quadratic form in the variables x and y. The coefficients usually belong to a fixed field K, such as the real or complex numbers, and one speaks of a quadratic form over K. If {\displaystyle K=\mathbb {R} }{\displaystyle K=\mathbb {R} }, and the quadratic form takes zero only when all variables are simultaneously zero, then it is a definite quadratic form, otherwise it is an isotropic quadratic form.

Quadratic forms occupy a central place in various branches of mathematics, including number theory, linear algebra, group theory (orthogonal group), differential geometry (Riemannian metric, second fundamental form), differential topology (intersection forms of four-manifolds), and Lie theory (the Killing form).

Quadratic forms are not to be confused with a quadratic equation, which has only one variable and includes terms of degree two or less. A quadratic form is one case of the more general concept of homogeneous polynomials.

### normal form
The standard form of a quadratic form is a generalization of coordinate transformation.


# block matrix

# relation of inverse matrix and adjugate matrix


# Linear transformations
The basic properties of a linear transformation T: V → W are as follows:

1. Additivity: T(u + v) = T(u) + T(v) for any vectors u, v in V.
2. Homogeneity: T(ku) = kT(u) for any scalar k and vector u in V.
3. The combination of 1 and 2.
## elementary matrix 
$$A = {P_1} E {P_2}$$
${P_1}$ is in left, equals elementary row operations. ${P_2}$ is in right, equals elementary column operations.

# TODO
## 余子式与代数余子式的区别

## 行列式计算 每天都要做