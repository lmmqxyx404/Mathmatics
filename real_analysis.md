# Chapter1 Function and Limitation
## function
 a function from a set X to a set Y assigns to each element of X exactly one element of Y.The set X is called the domain of the function and the set Y is called the codomain of the function.

In short,domain and conversions forms a unique function.

### common types
- 1. absolute
- 2. segmentation
- 3. rounding
- 4. sign
- 5. constant
- 6. Dirichlet

### features
- 1. boundedness
- 2. Monotonicity
- 3. period
- 4. odd and even

## functional limitation

### definition

### features
1. continuous
2. infinite series


# Chapter2 Two critical limits and Limit Existence Criteria

## Limit Existence Criteria
Monotone bounded series must converge.

## calculate the limit

### $a-b$ $(0-0)$
In mathematics, rationalizing is the process of converting a fraction expression into an equivalent expression in which the denominator does not contain irrational or other undesirable terms.
try to rationalizing the relative a-b. For example, you can multiply a+b.

### $\frac{\infty}{\infty}$
get the ${\infty}$ factor and pay attention to the $+$ $-$ symbol.

### the case that have to consider the left limit and right limit
 - piecewise function
 - $\mathrm{e}^{\infty}$ because the symbol of ${\infty}$ could be + and -
 - $\arctan{x}$ and $x={\infty}$

### low-order infinitesimal plus a high-order infinitesimal
The result is a low-order infinitesimal
# Chapter3 Derivatives
## 0. origin
研究加速度与瞬时速度问题。必须求一个极限值，这个极限值表示的含义就是瞬时速度

## 1. How to get the derivative of the inverse function
## 2. Common trigonometric functions for derivatives

## 3.tangent line and normal line.
Tangent Line (切线):
The tangent line to a curve at a specific point is a straight line that touches the curve at that point, sharing the same slope as the curve at that point. The tangent line represents the instantaneous rate of change or the direction of the curve at that particular point. It provides a linear approximation to the curve near the point of tangency.

Normal Line (法线):
The normal line to a curve at a specific point is a straight line that is perpendicular (at a right angle) to the tangent line at that point. The normal line represents the direction that is orthogonal to the tangent line and is pointing away from the curve. It provides a reference line for measuring angles and is often used in various mathematical applications.

Both the tangent line and the normal line play important roles in calculus and differential geometry. They help in analyzing the behavior of curves, determining critical points, finding derivative values, and understanding the geometric properties of curves at specific points.
### pay attention that the derivative limit value of some point is infinite.
the relative normal line could be the $y_0$

## 4.导数之间的运算法则

## 5.高阶导数
### 计算方法
1. 直接法
2. 间接法
3. 公式法（Leibniz）
$$[f(x)*g(x)]^{(n)}=f^{(n)}g+C_n^1f^{(n-1)}g'+\cdots+ g^{(n)}f $$

## 6.隐函数和参数方程求导
$$F(x,y)=0,且x确定，y就可以确定。那么就称F(x,y)确定了一个隐函数 $$
### 1. 主要是对数求导法
### 2.参数方程确定的函数求高阶导数。要冷静分析


# Chapter4 differential
## concept
$$ calculate the \Delta{y}  $$

# Chapter5 常见的微分中值定理 
## 费马引理

## 罗尔定理

## 拉格朗日中值定理

## 柯西中值定理

## 泰勒公式
### 配亚诺余项
### 拉格朗日余项

## 渐近线条
### 水平渐近线（斜渐近线）
可以同时存在，但是在一侧，不可能同时存在

### 垂直渐近线

## 曲率
$$K=|y''|/(1+{y'}^2)^{3/2}   $$

## 曲率半径
$$ R=1/K $$

#  Chapter5 Differentional equation
## definition
$$
F(x,y,y',y^{(2)},y^{(3)},\cdots,y^{(n)})=0 \\
y^{(n)} 中n为微分方程的阶
An ordinary differential equation of order n.
$$

## linear differentional equation
1. Seperation of variables method
2. Homogeneous differential equation method
3. Integrating factor method
$$dy/dx+P(x)y=Q(x) $$
4. Bernoulli differential equation method
$$dy/dx+P(x)y=Q(x)y^n $$

## 全微分方程

## Chi-square linear differential equations
### 高阶微分方程（主要是2阶及以上）
1. 要考虑是否是齐次
2. 要考虑是否是常系数
二阶常系数线性微分方程
### 常系数齐次微分方程有公式解

### 注意欧拉方程

# Chapter5 infinite integrals
## integral methods


# Chapter8 Infinite series

## 1.Number of constant term series
The sum of n terms convergents. The series convergent.
$$ S=a_1+a_2+...+a_n+... $$
$$ S_n=a_1+a_2+...+a_n$$

$$ if \lim_{n \to \infty}=A , \ Then\ S_n\ convergent $$

### 2.series of positive terms
1. Conmparision test
2. Limit comparison test
3. Ratio test
4. Root test

### alternative series

### absolute convergency


## 2.functional series
$$f(x)=a_1(x)+a_2(x)+a_3(x)+...+a_n(x)+... $$
### 2.1 convergence and divergence
函数项级数的特例是幂级数
### convergence radius. Convergence domain

## 3.power series
$$ In\ general, a_n(x)=a_n*(x-x_0)^n $$
 A power series is a representation of a function as an infinite sum of terms, where each term is a constant multiplied by a variable raised to a non-negative integer power. 

## 4.Fourin series


# Chapter8 Multiple Derivals
## calculate more than 2 variables

## Lagrange multiplier
In mathematical optimization, the method of Lagrange multipliers is a strategy for finding the local maxima and minima of a function subject to equation constraints

# Chapter9 Multiple Integrals
## calculate more than 2 integrals
### 分步积分法
要学会交换积分次序，三重积分时，如果要交换成指定的积分次序，可以考虑两两交换，不一定要直接按照空间形状去分割

### first 1 then 2
common ways. Priority of z. ∫， lower bound and upper bound could be f(x,y)

### first 2 then 1

### 极坐标

### 对称性，奇偶性
积分区域对称，函数值有奇偶性

### 变量对称性
积分区域关于 y=x 对称

### formula
$\mathrm{d}v=ρ\mathrm{d}ρ\mathrm{d}Θ$

dv=pin

### first 2 then 1
like calculate a sphere. 
$\mathrm{d}v=\mathrm{d}s\mathrm{d}z$

$$\iiint\limits_{V} f(x, y, z) dV = \int_{z_1}^{z_2} f(z)dz\iint\limits_{D_z} ds$$

## curve integration
In mathematics, a line integral is an integral where the function to be integrated is evaluated along a curve.[1] The terms path integral, curve integral, and curvilinear integral are also used; contour integral is used as well, although that is typically reserved for line integrals in the complex plane.
### Green formula
transform $\mathrm{d}x\mathrm{d}y$ to $\mathrm{d}s$
格林公式可以将封闭的曲线积分转化为曲面积分来做。

## surface integral
In mathematics, particularly multivariable calculus, a surface integral is a generalization of multiple integrals to integration over surfaces. It can be thought of as the double integral analogue of the line integral. Given a surface, one may integrate a scalar field (that is, a function of position which returns a scalar as a value) over the surface, or a vector field (that is, a function which returns a vector as value). If a region R is not flat, then it is called a surface as shown in the illustration.

Surface integrals have applications in physics, particularly with the theories of classical electromagnetism.

### Gauss's law
#### condition
where the integral is taken over a closed surface S enclosing a volume V that contains a charge Q. This equation relates the electric field E at every point on the surface S to the charge Q enclosed within the surface.

Transfer $\mathrm{d}x\mathrm{d}y\mathrm{d}z$ to $\mathrm{d}v$

### Stoke‘s Formula
Stokes' theorem establishes a connection between surface integrals and curve integrals.
In the application of Stokes' theorem, the direction of the surface should follow the right-hand rule.
There is a closing relation to Green's theorm

# The association between Green's Law and Stoke‘s Formula


# 函数奇偶性会影响到0点判定，进而可导性质也会受到影响


微分方程的种类
齐次性
连续函数的可导性

# space line equation
## vector algorithm
### X multiply
determinant rule.
### point multiply
only can get a number value.
### 混合积


## 空间平面方程 
### Normal form
$$
A(x-x_0)+B(y-y_0)+C(z-z_0)=0
$$

### general form
$$Ax + By + Cz + D = 0$$

## 空间直线方程
### 点法式方程

### 参数式方程
可导必定连续  连续未必可导

旋转体体积计算
F(x) ≠0且连续，则 |f(x)| 必定可导
变上限积分函数
一般都是和导数以及积分一起出

周期函数的积分
Series function 

三角函数求原函数
变上限函数求积分

# TODO
## 关于数列 极限 级数
数列有极限，一定有界。数列极限不存在，不一定无界。
级数收敛，对应的数列必定收敛于无穷小。
级数发散，对应的数列第n项必定极限不为0或者极限不存在。

## 间断点分类区别

## 导数
1. 函数求导的四则运算法则
2. 注意与复合函数求导区分开来（复合时，尽量让每一个中间函数是初等函数）
3. 反函数求导
4. 高阶导数的计算
5. 变上限积分公式求导

## 拐点  stationary point  凹凸性  极值点定义
求拐点的步骤
拐点是坐标还是一个x轴数据

## 曲率相关的概念和计算

## 各种积分
三角函数的积分与开根号的积分

## 级数的基本特性

## 微分方程的分类与求解
分子 分母都是整式的微分方程 求解技巧
二阶常系数非齐次微分方程

## 多重积分的计算技巧
1. 利用被积函数的对称性
2. 利用被积区域的对称性
3. 切记不要忘记了 y=x 这种对称性

## 中值不等式的证明
### 1. 常见的不含有导数的不等式
直接转化为一整个函数，然后求导

### 2. 条件中给出导数，也要证明同阶导数。

### 3.高阶导数
注意用到 泰勒公式


傅里叶级数
## 专题方程根的个数
1. 零点定理，也许会和极限的保号性结合在一起。
2. 罗尔定理
3. 也可能会和泰勒联系在一起考察。


## 一元函数积分学
### 不定积分
注意背诵公式

### 定积分
#### 反常积分
注意判断瑕点，这时候要用到反常积分审敛法

### 专题13 二重积分
1. 注意，优先看积分区域的特点。
2. 拆原来的二元函数，拆项后，注意有不好积的部分，可以抵消。
3. 换积分顺序或者改成极坐标形式

### 专题 无穷级数
级数分类
1. 常数项级数
2. 正项级数
阿贝尔定理
莱布尼茨准则

计算收敛域
直接看系数。
两种方法，比值法或者根值。

求和函数

计算函数极限的技巧
仅含有ln时，注意等价代换

等价无穷小可以和不定积分结合在一起
