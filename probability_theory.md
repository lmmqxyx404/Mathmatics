# probability and statistics

# random test
1. before the test, we can predict all possible results.
2. before the test, we can not know the precise result.
3. The test could be repeated in the same condition.

## 1.1 sample spaces(always noted as S)
###  random event.
basic event
certain event
impossible event
The subset(not the element in S) of S is A.

### the relation between events and relative computing.
Union event
Difference event
Product event
Inverse event

## the axiomatic definition of probability
The axiomatic definition of probability, often referred to as the Kolmogorov's axioms, provides a formal framework for describing probability. According to this definition, probability is defined based on three axioms:

1. Axiom of Non-Negativity: For any event A, the probability of A is a non-negative real number. In mathematical terms, this means that P(A) ≥ 0.

2. Axiom of Additivity: If A and B are mutually exclusive events (i.e., they cannot occur simultaneously), then the probability of the union of A and B is equal to the sum of their individual probabilities. Mathematically, this can be expressed as P(A ∪ B) = P(A) + P(B).

3. Axiom of Normalization: The probability of the entire sample space (the set of all possible outcomes) is equal to 1. In other words, the probability of the sample space S is P(S) = 1.

These axioms provide the foundation for defining and manipulating probabilities. From these axioms, various properties and rules of probability can be derived, such as the complement rule, the multiplication rule, and the inclusion-exclusion principle.

It's worth noting that these axioms are just one way to define probability, and alternative approaches exist, such as the subjective interpretation of probability. However, the axiomatic definition based on Kolmogorov's axioms is widely used in probability theory and forms the basis of many statistical and probabilistic analyses.

# Multidimensional random variable
## 1. Definition
A multivariate random variable, also known as a multidimensional random variable, consists of a vector of multiple random variables. For example, a bivariate random variable \((X, Y)\) includes two random variables \(X\) and \(Y\).

## 2. Joint Distribution
- **Joint Probability Density Function (Continuous Variables)**: If \(X\) and \(Y\) are continuous, their joint probability density function \(f_{X,Y}(x, y)\) represents the probability density at the point \((x, y)\) for these values to occur simultaneously.

- **Joint Probability Mass Function (Discrete Variables)**: If \(X\) and \(Y\) are discrete, their joint probability mass function \(p_{X,Y}(x, y)\) represents the probability of simultaneously taking specific values \(x\) and \(y\).

## 3. Marginal Distribution
- **Marginal Probability Density Function**: Obtained from the joint probability density function by integrating (continuous variables) or summing (discrete variables) over the other variable(s).
- **Example**: The marginal density of \(X\) from a bivariate random variable \((X, Y)\) is \(f_X(x) = \int_{-\infty}^\infty f_{X,Y}(x, y) \, dy\).

## 4. Conditional Distribution
- **Conditional Probability Density Function**: The probability distribution of one variable given the value of another variable.
- **Example**: The conditional probability density function of \(X\) given \(Y = y\) is \(f_{X|Y}(x|y) = \frac{f_{X,Y}(x, y)}{f_Y(y)}\) (assuming \(f_Y(y) > 0\)).

## 5. Independence
- **Independence**: Two random variables are independent if their joint distribution is equal to the product of their marginal distributions. For the bivariate random variable \((X, Y)\), if \(f_{X,Y}(x, y) = f_X(x) f_Y(y)\) for all \(x, y\), then \(X\) and \(Y\) are independent.

## 6. Covariance and Correlation Coefficient
- **Covariance**: A measure of how much two random variables change together. It is calculated using the formula \(\text{Cov}(X, Y) = E[(X - E[X])(Y - E[Y])]\).
- **Correlation Coefficient**: The standardized form of covariance, used to measure the strength and direction of a linear relationship between variables. The formula is \(\rho_{X,Y} = \frac{\text{Cov}(X, Y)}{\sqrt{\text{Var}(X) \text{Var}(Y)}}\).

These are some of the basic concepts associated with multivariate random variables. If you're interested in a specific topic or need examples and mathematical derivations, feel free to ask for more details!

# The numerical characteristics of a random variable
## Expectation (Mean)

## Variance

## Standard Deviation

## Covariance

### TODO: consider the following formula
$$
P( \bigcup_{\text{i=1}}^{n} A_i)=\sum_{i=1}^{n}P(A_i)+...
$$

## traditional probability
1. the number of S is limited.
2. each probability of the basic point is equal.

### classical problem
pay attention to the sample space.

### conditional probability

### the law of total probability(Bayes)
the keyword is partition.

### basic point

# random variable.
$$ X(e):S \rightarrow  R $$
pay attention that multiple basic point could be same value.
多个样本点可能对应同一个随机变量。（一般是让每一个样本点对应唯一一个随机变量）

## ideas
1. 划分样本空间为基础的样本点。
2. 定义随机变量(定义完后，有时候可以确定取值范围。即值域)
3. 则随机事件的取值可以确定


## Probability distribution
 - 1. Binomial distribution 
 - 2. Bernoulli distribution
 - 3. Poission distribution
 - 4. Unify
 - 5. Exponential
 - 6. Normal distribution

补充关于5的说明
指数分布具有无记忆性，指数分布一般是连续型随机变量
泊松分布与指数分布类似，但是泊松分布是离散型随机变量

# Probability density function
The relation of variable and probability density function
in general,
  $$F(x) = \int_{-{\infty}}^{x}f(x){\mathrm{d}x} $$

# The function of R(X)
if Y is the function relatived with X.


# Expectation
## Random variables with finitely many outcomes


## Random variables with density
  $$E[X] = \int_{-{\infty}}^{+{\infty}}x*f(x){\mathrm{d}x} $$

Ram
Rsm

# point estimate method

# Law of the unconscious statistician
In probability theory and statistics, the law of the unconscious statistician, or LOTUS, is a theorem which expresses the expected value of a function g(X) of a random variable X in terms of g and the probability distribution of X.

# multivariable
## how to calculate F(X,Y)
$$F(a<X<b,c<Y<d)=F(b,d)-F(b,c)-F(a,d)+F(a,c)$$

#

# statistic
## population

## sample

### simple sample

## sample statistic
### sample mean

\[
\bar{X} = \frac{1}{n} \sum_{i=1}^{n} X_i
\]

### sample variance

\[
S^2 = \frac{1}{n-1} \sum_{i=1}^{n} (X_i - \bar{X})^2
\]

# TODO
## 独立与相容的概念对比（venn graph）
犯过错误
不要以为独立，交集就是空集。

## basic point relations
不同样本点的概率不一定是相同的，可以不同，相同就认为是均匀分布

## 常见的概率密度分布函数 
指数分布要多练习，泊松分布，正态分布，每天多写一写。

## 概率密度与随机变量类型的联系
为什么会有概率密度函数

## f(x) F(x) 各自的性质

## F(X) 的函数
根据定义去计算

方差的定义，以及相关系数定义
