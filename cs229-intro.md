# Machine Learning (CS229)
--------------------------

[YouTube Link for this note](https://www.youtube.com/watch?v=Bl4Feh_Mjvo&t=1833)
## Introduction

Machine Learning is the use of computers to do tasks without being explicitly programmed.

### Types
1. Supervised Learning
2. Unsupervised Learning
3. Reinforcement Learning
The types are not clearly separated.

### Terminology
Features or input variables: Characteristics on which the output or target variable depends on. (usually $n$ in number)

Target variable or output: The value you are trying to predict with the features as input

Example: A single data point in your data set. (Usually $m$ in number) (Notation: $(x^{(i)}, y^{(i)})$ represents the $i^{\mathrm th}$ example.)

For instance, in a housing price prediction problem your features maybe *size* and *lot size* ($x \in \mathbb{R}^2$);
Similarly the price is the target or output variable.

One way to solve this is to fit a straight line on to our dataset and use that to predict the prices. This is called *linear regression*.
Another way might be to fit a different curve to the data.

### High Dimensional features
When $x \in \mathbb{R}^d$ for large $d$

Regression: When $y$ is a continuous variable.

Classification: When $y$ the output is in a discrete and distinct set of classes e.g (malignant or beneign)

Unsupervised learning: When you are not given any labels in yoour data set.

Reinforcement Learning: Learning to do a sequential set of steps.