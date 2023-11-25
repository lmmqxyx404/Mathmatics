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

# Probability density function
The relation of variable and probability density function
in general,
  $$F(x) = \int_{-{\infty}}^{x}f(x){\mathrm{d}x} $$

# Expectation
## Random variables with finitely many outcomes


## Random variables with density
  $$E[X] = \int_{-{\infty}}^{+{\infty}}x*f(x){\mathrm{d}x} $$

Ram
Rsm

# point estimate method

# Law of the unconscious statistician
In probability theory and statistics, the law of the unconscious statistician, or LOTUS, is a theorem which expresses the expected value of a function g(X) of a random variable X in terms of g and the probability distribution of X.

# TODO
## 独立与相容的概念对比（venn graph）
犯过错误
不要以为独立，交集就是空集。

## basic point relations
不同样本点的概率不一定是相同的，可以不同，相同就认为是均匀分布

## 常见的概率密度分布函数 

## 概率密度与随机变量类型的联系
为什么会有概率密度函数

## f(x) F(x) 各自的性质