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

# inverse matrix
逆矩阵与伴随矩阵的关系
伴随矩阵与原始矩阵的乘积关系
We can use inverse matrix to calculate A^n.

# 分块矩阵与初等变换

# rank
任意一个k阶子式为0，则对应的 R 值一定小于k。
任意的初等变换不会影响对应矩阵的秩。

# 向量组
## 向量类型
单位向量
零向量

## 向量组合
## 组合系数
## n维单位向量
向量组合成为矩阵

## 向量组等价的含义及其相关推论

## 线性相关 
有很多相关结论以及推论，要学会与方程组结合起来理解

# the rank of vector array 

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

# vector space
## the basis of a space.
向量空间中的任意一个向量就是由系数坐标和基相乘得到的。

## 基变换（坐标变换）

# quadratic form
In mathematics, a quadratic form is a polynomial with terms all of degree two ("form" is another name for a homogeneous polynomial). For example,
is a quadratic form in the variables x and y. The coefficients usually belong to a fixed field K, such as the real or complex numbers, and one speaks of a quadratic form over K. If {\displaystyle K=\mathbb {R} }{\displaystyle K=\mathbb {R} }, and the quadratic form takes zero only when all variables are simultaneously zero, then it is a definite quadratic form, otherwise it is an isotropic quadratic form.

Quadratic forms occupy a central place in various branches of mathematics, including number theory, linear algebra, group theory (orthogonal group), differential geometry (Riemannian metric, second fundamental form), differential topology (intersection forms of four-manifolds), and Lie theory (the Killing form).

Quadratic forms are not to be confused with a quadratic equation, which has only one variable and includes terms of degree two or less. A quadratic form is one case of the more general concept of homogeneous polynomials.

### normal form
The standard form of a quadratic form is a generalization of coordinate transformation.

# TODO
## 余子式与代数余子式的区别

## 行列式计算 每天都要做

## 为什么要引入伴随矩阵
为了计算逆矩阵

## 为什么要引入逆矩阵
$$ 计算多项式，即 A^n $$

## 矩阵可逆的充分必要条件
$$  $$ 

## 求可逆矩阵的方法

## 逆矩阵有什么用
mooc 课后有一个选择题  14
可交换的含义。

answer： E和O都属于可交换矩阵

## 分块矩阵的引入以及应用
1. 主要可以用来证明O矩阵的充要条件
2. 快速求对角阵的逆举证

## 初等变换
1. 行变换与列变换应该是什么样。
2. 为什么需要初等变换
依据分块矩阵与初等变换
可以求出逆举证

## rank（秩）
1. 注意k阶子式为0，则对应的秩小于k。不是k-1。

## 齐次线性方程组解集的rank与系数对应的rank取值

## 方程组同解的定义

## 向量组等价的定义

## 证明线性相关思路
利用定义，向量组线性相关的定义

## 证明是否可以相似对角化

## 两两正交与线性相关的联系

## 正交矩阵的定义
