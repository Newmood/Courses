## Introduction to Machine Learning

|Lectures | https://youtube.com/playlist?list=PLCof9EqayQgv6tP8gfDUGqpkBn8u5c5PY |  
|--------| ---------|
|Slides | https://mlvu.github.io/introduction/ |

### Types of machine learning
**Supervised Learning** is the case where we have input variables and output variables and the model learns the map between the two. 
Examples are Regression and Classification.  
Regression is when output vairables are numeric, we assign numbers on the new data, for example predicting house prices based on location, land area, number of floors etc.
Classification where we assign the new data to classes, for example marking an email as spam or ham.

**Unsupervised Learning** is when there is only input data, no output data. Or we can say, we have unlabelled input data. (We have labelled input data in case of Supervised learning). In such an approach our goal might be to find patterns in the data, clusters them based on similar features.  
Examples include clustering, dimensionality reduction and generative modelling.

**Reinforcement Learning** : https://towardsdatascience.com/reinforcement-learning-101-e24b50e1d292

**Online Learning** : This is a technique where data is acquired sequentially ("one datum at a time") and updated in predictor. It learning and predicting at the same time.

**Semi Supervised Learning** is a way where we have both labelled and unlabelled data. First we train on labelled data then predict for the unlabelled data, and then the entire set becomes our training data and this process is repeated. The method exists because obtaining labelled data can be costly. Regression and classification can be used for semi supervised learning.

**Self-supervised learning:** Also known as predictive learning or pretext learning. Examples: masking, auto-regressive modelling.

### Loss function
**Loss function:** Loss function can be thought of as a measure of how good a model is. The lower the value of loss funciton, the better the model is.

#### Loss function for regression
$\text{loss(f)}= \dfrac{1}{n} \sum_{i}(f(x_i)-t_i)^2$ this is also known as the mean squared error loss.

