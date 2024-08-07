# Machine Learning Specialization

## Supervised Machine Learning : Regression and Classification
* Intoduction to Machine Learning
* Regression with multiple input variables
* Classification

## Intoduction to Machine Learning
## General
What is machine learning ? 

It is a science of getting computers to learn without being explicitly programmed.
Examples: Google Search, AI Assistants (Siri), Movie Recommendations, Spam Email Categorization etc.
Machine Learning is the sub-field of Artifical Intelligence.

Types of Machine Learning 
* Supervised Learning (used in most of real world applications)
* Unsupervised Learning
* Recommender Systems / Semi-suprvised Learning
* Reinforcement Learning

## Supervised Learning 
Supervised Learning are alogorithms that learn : X ---> Y

![SL1](https://github.com/vyasaarsh/Learnings/blob/main/Machine%20Learning%20Specialization/Images/SL1.png)

Examples for the X ---> Y algorithms include : 

![SL2](https://github.com/vyasaarsh/Learnings/blob/main/Machine%20Learning%20Specialization/Images/SL2.png)

Regression

* Housing Prediction is particular type of supervised learning called the Regression
* Regression: Predicting a number from infinetly many particular outputs

Classification

* Breast Cancer Detection is particular type of supervised learning called the Classification
* Classification: Predicting categories (also can be numbers but with small possible outputs such if (0,1,2) but not (0.5,1.7))
* Exmamples include To Predict if it is a picture of a dog or cat (non-numerical) 

## Unsupervised Learning
Data only comes with input (X) but not any output labels (Y). The Algorithm has to find structure in the data

Clustering

* Grouping similar data points (individuals) together (categories)
* Examples include Given just patients age & tumor size and not if beningn or malignant, DNA Microarray, Grouping Customers

Anomaly Detection

* Find unusual data points
* Examples include Fraud Detection (unusual transaction) in the financial system

Dimensionality Reduction 

* A big-data set and magically compress it to a much smaller data-set with losing as little information as possible. Compress data using fewer numbers 

## Regression Model

Supervised Learning Model

* Regression Model: Any supervised learning model that predicts NUMBERS (such as 200000,1.5,-33.2) is addressing what's called a Regression Model

Linear Regression Model

Example: Housing Price Prediction

![SL3](https://github.com/vyasaarsh/Learnings/blob/main/Machine%20Learning%20Specialization/Images/SL3.png)

Training Set: Dataset used to train models is called Training Set

Terminology

x = input variable / feature / input feature
y = output vairanle / target variable
m = total number of training examples (total number of rows in the data set)
(x,y) = single training example
(x^(i), y^(i)) = i^th training example (i^th row)

* Classification Model: Any supervised learning model that predicts CATEGORIES or DISCRETE CATEGORIES (such as predicting if a picture is a cat or dog, if a given medical record it has to predict if patient has a particular disease) is addressing what's called a Classification Model
