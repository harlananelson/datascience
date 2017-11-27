# Data Mining

## Humans Are Good At Filtering Information 

The world is filled with information.  Everyday we have to decide what to pay attention to and what to ignore. 
Our brains are very good at filtering out noise.  We can understand speech even in a loud room.
If there are many people talking and we want to focus on only one person, we can.  Our brains do a great job. 
The same is true with sight.  We learn what to pay attention to and what to ignore. Humans use life experiences to 
develop intuition.  We understand the relationships that exist between events we observe.


## Algorithms Can Be Used to Filter Information
(How Can Statistical Analysis Be Used To Understand Outcomes.)

How can we quantify relationships mathematically with algorithms instead of human intuition?
Data mining is a mathematical version of what we do every day. 
Data mining methods allow us to sort through large amounts of information to focus on what is important. 

We will learn about one method: Regression analysis. 

The housing prices data set provided by Kaggle will be used to test our methods.
Anyone who has bought a house, has developed the ability to price houses. 
We will develop mathematical models to price houses. 
We will use information about a house (predictors or features) 
to explain the outcome (price). 

What will we learn how to do?

* Represent relationships using scatter plots and other graphical methods.
* Represent relationships using a mathematical model.  Example: Quantify the relation of housing size to housing price with an equation.
* Understand how to interpret this mathematical model.
* Quantify how well the model describes the outcome (Explanatory power).
* Model building
   * Select the most important pieces of information.  Select the best variables out of many provided.
   * Combine many pieces of information in one model 
   * Describe how using a loss function or utility function enables us to tune the parameters.
* Apply statistical inference to quantify random variation in our predictions. 
* Predict and forecast. 
* Think about mathematical models a few different ways. 
* Apply methods to avoid over fitting.

## Graphical Representations of Relationships.

It is always a good idea to start out by getting to know your data.  A good approach is through the 
visual displays of graphs.  In the case of regression analysis, scatter plots and box plots do a great job.

## The Mathematical Model
Mathematically, the most elementary regression model is simple linear regression.  Other regression models are
generalizations of it.  Lets look at a few examples using the graphs we just produced.

## Interpreting the model
After finding a few good models, we need to interpret from a mathematical representation to human understanding.  
How does the model give us insight into housing prices.  We will look at the models we just developed.

## How Well Does the Model Fit the Data?
(Explanatory Power of Information as a Measure.)

We need a mathematical measurement that states how well the model did.
If you can measure something, you can control it and optimize it. 
We need a mathematical definition for the concept of explanatory power so we can 
measure it and then optimize it. 
This measurement will help use decide which of a 
few good models is the best one.  This measurement will be a loss or objective function that captures model fit. 
In least squares regression, which is the same as linear regression, the loss function is the sum of squares of the errors.
We will talk about that.

## Housing Prices Data
The data set is called: "House Prices: Advanced Regression Techniques."
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data
Here is the Kaggle description:

```
ask a home buyer to describe their dream house, and they probably won't begin with the 
height of the basement ceiling or the proximity to an east-west railroad. 
But this playground competition's dataset proves that much more influences 
price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in 
Ames, Iowa, this competition challenges you to predict the final price of each home.
```
We need to predict the housing price. 

## What Information Is Important?

What is important: The information that helps us explain a certain phenomenon?
We want to know why things happen. We need to focus on the important information and discard the  rest. 
We need mathematical methods to select what information to include in the model. that way we can fit a simple
model with high explanatory power. The are many measurements, but we can also use our previous measure of model fit.


