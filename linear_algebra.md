# linear algebra
## aim
Learning linear algebra is to study `linear spaces`.Planes and spaces are just special cases of `n-dimensional vector spaces`.

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

### Contracts and Similarities

### inverse matrix
逆矩阵与伴随矩阵的关系
伴随矩阵与原始矩阵的乘积关系
We can use inverse matrix to calculate A^n.

### 分块矩阵与初等变换

### rank
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

### the rank of vector array 

### block matrix

### relation of inverse matrix and adjugate matrix


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

## 过渡矩阵
如果 AP=B.
那么，P就称为从A到B的过渡矩阵，注意计算时，应该与单位矩阵以及基联系起来

## 基变换（坐标变换）
注意与过渡矩阵的联系
$$ P^{-1}a=b (target) $$

## 正交矩阵
### 规范正交基

### 施密特 正交化
学会推导过程

### 正交矩阵的性质
$$ A^{T}A=E $$

### 正交变换的性质
经过正交变换的向量长度保持不变，角度不变

# eigenvalue en eigenvector
In linear algebra, an eigenvalue is an important characteristic of a square matrix. For an n × n matrix A, if there exists a scalar λ and a non-zero vector v that satisfy the following equation:

A * v = λ * v

## the conclusion of eignvalue
特征值之和等于对角线上元素之和
特征值之积等于行列式的值

注意，任意两个特征向量之和不是新的特征向量

## 与原始矩阵相关的矩阵的特征值
$$ A^{-1} A^{*} A^{k} 对应的特征值 $$

## 相似关系
Similar matrices are matrices that share certain properties in linear algebra. Given two n × n matrices, A and B, they are said to be similar if there exists an invertible matrix P such that the following relationship holds:

B = P⁻¹ * A * P

Here, P⁻¹ represents the inverse of matrix P.

In other words, if matrix B can be obtained by performing a similarity transformation on matrix A, then A and B are considered similar matrices. The transformation matrix P connects the two matrices, and by multiplying A by P and P⁻¹, we can transform one matrix into the other while preserving certain properties.

$$A与B 相似，那么A^k与B^k也相似 $$

## 相似对角化的条件与求法

## 相似的作用
$$ 可以用来求解A^k $$

# quadratic form
In mathematics, a quadratic form is a polynomial with terms all of degree two ("form" is another name for a homogeneous polynomial). For example,
is a quadratic form in the variables x and y. The coefficients usually belong to a fixed field K, such as the real or complex numbers, and one speaks of a quadratic form over K. If {\displaystyle K=\mathbb {R} }{\displaystyle K=\mathbb {R} }, and the quadratic form takes zero only when all variables are simultaneously zero, then it is a definite quadratic form, otherwise it is an isotropic quadratic form.

Quadratic forms occupy a central place in various branches of mathematics, including number theory, linear algebra, group theory (orthogonal group), differential geometry (Riemannian metric, second fundamental form), differential topology (intersection forms of four-manifolds), and Lie theory (the Killing form).

Quadratic forms are not to be confused with a quadratic equation, which has only one variable and includes terms of degree two or less. A quadratic form is one case of the more general concept of homogeneous polynomials.

## symmetric matrix
1. 对称矩阵不同特征值对应的特征向量正交。
2. $$ A 为n阶 symmetric matrix, \\ Then there must be a orthogonal matrix P, so\\ P^{-1}AP=P^TAP= \varLambda $$

### normal form 标准型
The standard form of a quadratic form is a generalization of coordinate transformation.
基础的二次型定义，要理解。
$$ row*A*col $$

### 规范型

### 合同矩阵
$$ B=C^TAC, 那么 A与B合同 $$
1. 合同关系为等价关系
2. 与对称矩阵合同的矩阵也是对称矩阵
3. 合同矩阵有相同的秩

不对称矩阵之间也可以合同，但是注意，与对称矩阵合同的一定是对称矩阵
考试基本只要求 对称矩阵 之间的合同

### 正交变换

### 任意一个二次型化为标准型的过程
就是将二次型转化为对角矩阵
二次型一定是对称阵

1. 二次型表示为矩阵形式
2. 求出对应的特征向量
3. 将向量正交化，单位化,得到P
4. 注意，作正交变换 x=Py .
5. 得到标准型

### 正定与负定
1. 负定的条件
负定就是奇数为负，偶数为正。

2. 正定的充分必要条件
 - 特征值都大于0
 - 主子矩阵的行列式都大于0
 - cholesky 分解
 


# TODO
## 余子式与代数余子式的区别

## 行列式计算 每天都要做

## 为什么要引入伴随矩阵
为了计算逆矩阵
注意伴随矩阵与原矩阵之间的 rank 联系.

## 为什么要引入逆矩阵
$$ 计算多项式，即 A^n $$

## 矩阵可逆的充分必要条件
$$ |A|\not = {0} $$

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

## 过渡矩阵
坐标变换公式

## 特征值  特征向量（为什么需要这个）
是为了做线性变换，并且会有特征多项式，
也是为了引出相似矩阵

1. 注意，特征向量要求非0
2. 特征值以及相关的算术运算法则。
3. 特征多项式的定义

补充：n阶方阵A不可逆时，即`R(A) < n`, 那么该方阵一定有一个特征值为0。
注意此时方阵A仍然可以是对称矩阵

## 相似矩阵
### 矩阵可以相似对角化的条件
快速举出一个不能相似对角化的反例。

## 对称矩阵的特征值，特征向量
由于对称矩阵一定可以相似对角化，而且是正交变换。
故任意二次型一定可以变为规范型

## 二次型
主要问题是变为规范型，求解x=Cy中的C。
注意有两种方法
1. 对应的 symmetric matrix 作正交变换
2. 使用拉格朗日配方法。

### 基本定义

### 正定与负定
注意，正定时，充分必要条件与负定时有很大区别，还有就是除这两者之外
还有半正定的概念。

### 要证明正定
那就只要看标准型的二次项系数是否都是正数。

## 合同与相似的对比 
都具有传递性，等价性，因此可以拓展出一些概念。
相似，也就是有相同的特征值

A与B相似的充要条件判定不简单

A与B相似，无法得出都可以相似对角化的结论

$$A与B相似 \iff A和B都与同一个对角矩阵相似 \\（也就是除了看特征值之外，要看是否可以相似对角化）\\ 有相同的 jordan 型
$$

$$A与B合同 \iff 有相同数量的正负惯性指数$$

正交，两两列向量乘积为0


### 计算矩阵多项式
利用相似对角化计算矩阵多项式的时候，切记不要弄混所乘矩阵的次序

## 什么时候需要正交化
原矩阵为对称阵，就是一个二次型，求让其对角化的矩阵。

## 矩阵等价的判定条件
A与B的 rank equal, A与B 等价

## n阶对称阵有  特征向量 问题
注意告诉 n-1 个 特征向量，求最后一个特征向量。结合最后一个向量的正交性去求

如果要求原始矩阵，注意用特征向量的基本结论。
