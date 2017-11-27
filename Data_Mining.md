# Data Mining

## Humans Are Good At Filtering Information 

The world is filled with information.  Everyday we have to decide what to pay attention to and what to ignore. 
Our brains are very good at filtering out noise.  We can understand speech even in a loud room.
If there are many people talking and we want to focus on only one person, we can.  Our brains do a great job. 
The same is true with sight.  We learn what to pay attention to and what to ignore. Humans use life experiences to 
develop intuition.  We understand the relationships that exist between events we observe.


## Algorithms Can Be Used to Filter Information


## How Can Statistical Analysis Be Used To Understand Outcomes.

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

It is alows a good idea to start out by getting to know your data.  A good approach is through the 
visual displays of graphs.  In the case of regression analysis, scatter plots and box plots do a great job.

## The Mathematical Model
Mathematically, the most elementary regression model is simple linear regression.  Other regression models are
generalizations of it.  Lets look at a few examples using the graphs we just produced.

## Interpreting the model
After finding a few good models, we need to interpret from a mathematical representation to human understanding.  
What does the model mean interms of housing prices.  We will look at the models we just developed.

## How Well Does the Model Fit the Data?
We need a mathematical measurement that states how well the model did.  This measurement will help use decide which of a 
few good models is the best one.  We must have a loss or objective function that captures what we want.  


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
We need mathematical methods to measure the explanatory power of information, that way we can pick 
only the information with a high explanatory power.

## Explanatory Power of Information as a Measure

If you can measure something, you can control it an optimize it.  
We need a mathematical definition for the concept of explanatory power so we can 
measure it and then optimize it. 

Perspective describes how we perceive day to day events.  We need a mathematical way to express the concept of perspective.  This is the model.  The model we choose will limit our perspective.  It will also enable us to translate the mathematical model to a logical cause and effect relation. The easiest model to understand is the average.  What is the average income of your county?  
That is important for understanding the economy, but we can do better than the average.  But in this example, the average isn't the actual model,  the identifier of county is the actual model.  The mean is the statistic we used to measure difference.
This of this exercise.  Consider an object that has five sides.  Two apposing side are a triangle,  the other three are squares.  If you only looked at the triangular face, you would think the object contained triangular sides.  If you looked at one of the square faces, you would think that the object contained only square faces.  

So, up to now we have data and a model.  We also talked about a statistic.  A statistic is a function of the data: it is a formula.  What is the formula for the average.  Take the average income by county, that is an statistical analysis using county identifier as income as the data as the data and the average by county as the model.  Three product characteristics drive sales: quality, price and brand.  If you want to sell a product based on quality, you need to market in high income counties. 

Dealing with errors.  If you through a dart at a board, the dart hits a different spot every time.  If you knew only where the darts landed but nothing about the dart board, could you draw the dart board.  
If you understood the game of darts and had data from enough games you could.  If you average the location of the darts, you will be able to find important marks of the dart board like the bull's eye.  
Statistical methods give us the ability to deal with errors.  
The first major method was least squares invented by Legendre. in the appendix to a paper in 1810.  He developed a method to handle conflicting measurements.

Use of probability distributions. Statisticians use probability distributions to quantify errors.  This is the main characteristic that differentiates machine
learning from statistical analysis.  Machine learning can be applied without every worrying about probability distributions.  Monti-carlo simulation and bootstrapping can
eliminated the need for statistical distributions, but they are very useful.  The most useful is the normal distribution.  It is useful because of the central limit theorem.  The
CLT shows that many sampling distributions will follow the normal distribution.  A sampling distribution is the distribution of statistic calculated on a sample.  
The average location of a dart during a dart game is an example of a sample statistic.  A statistical distribution helps us understand if difference is large or small


Statistical significance is the technical designation for a large difference.  When you upgraded the firmware on your cell phone, did it increase your battery life?  
or is any difference you observe only due to random change?  In inferential statistics, this is measure by probability. Probability is associated with the value of 
a statistic calculated from a random sample.  Probability is graphically represented as the area under a curve.  Get used to thinking of probability as area under a curve.

Effect size is the other measure of difference.  If you saw the dart patterns from an expert in darts and one from a poor player, would you be able to tel the difference?  Yes you would. 

If you classify something and can measure the proportion of times you classified correctly, that proportion will take the place of calculating a distribution based probability. If you 
can think of your analysis as a dart throw and you can program the computer to simulate dart throws, you can completely avoid the need for probability distributions. 
Methods to do this are Monti-carlo simulation and bootstrapping.  

Data consists of data you can measure and data you are trying to predict.   The data you can measure is called features. What you are trying to predict is call the response. In some 
cases it is call the labels.  There is a third type. This is data you can't measure.  Ultimately there is a fourth type.
This is data related to what you are trying to predict but unavailable to you.  

A model is a mathematical formula you apply to your features to get the response.  If you have measurement of the response, you can compare the calculated response to 
the actual response.  Your model should have parameters that can be adjusted so that your model will get as close as possible to the actual response.

The measurement of how close your model gets to the actual response requires a loss function.  The lose function is just a formula.  In the case of least squares,
the loss function is the square error,  The method is named after the concept of minimizing this loss function "least squares."  

Models are tuned by minimizing the loss function.  We need to take about the value of the model.  Explain-ability is a term used to measure a model.  Does a model
explain the response.  This is calculated by comparing a very simple model to the tuned model.  If I am a retailer and want to predict how much product I will need
each month for each store, I need a model.  The simple model or null model is the average.  I just average the monthly sales for all the stores.  I could even do this over 
all the months.  Calculate the loss function for that model.  Explain-ability will now just be the ratio of the loss function for the best tuned model divided by the loss for 
the mean model.  In regression analysis, this is the $R^2$.  No appeal to a probability distribution is needed.

There is another way to think about regression models.  Projections.  

















