## Introduction to Machine Learning

|Lectures | https://youtube.com/playlist?list=PLCof9EqayQgv6tP8gfDUGqpkBn8u5c5PY |  
|--------| ---------|
|Slides | https://mlvu.github.io/introduction/ |

**Supervised Learning** is the case where we have input variables and output variables and the model learns the map between the two. 
Examples are Regression and Classification.  
Regression is when output vairables are numeric, we assign numbers on the new data, for example predicting house prices based on location, land area, number of floors etc.
Classification where we assign the new data to classes, for example marking an email as spam or ham.

**Unsupervised Learning** is when there is only input data, no output data. Or we can say, we have unlabelled input data. (We have labelled input data in case of Supervised learning). In such an approach our goal might be to find patterns in the data, clusters them based on similar features.  
Examples include dimensionality reduction and clustering.

**Loss function:** Loss function can be thought of as a measure of how good a model is. The lower the value of loss funciton, the better the model is.

### Loss function for regression
$\text{loss(f)}= \dfrac{1}{n} \sum_{i}(f(x_i)-t_i)^2$ this is also known as the mean squared error loss.
