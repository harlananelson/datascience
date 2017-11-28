# Data Mining Curriculum

## Philosophy

"Model-dependent realism is a view of scientific inquiry that focuses on the role of scientific models of phenomena.[1] It claims reality should be interpreted based upon these models"

— Wikipedia: Model-dependent_realism

"Like the overlapping maps in a Mercator projection, where the ranges of different versions overlap, they predict the same phenomena. But just as there is no flat map that is a good representation of the earth's entire surface, there is no single theory that is a good representation of observations in all situations[5]"

— Stephen Hawking & Leonard Mlodinow, The Grand Design, p.9

"[M]odels are an important tool for exploration. "

— Hadley Wickham


## Purpose
Data mining is about understanding the data.  Machine learning on the other hand is centered around predictions and forecasting.
Hadley uses three tools for Data Mining:
* Visualization
* Transformation (includes data reduction)
* Modeling

Hadley groups data analysis into two groups: 
* Hypothesis generation
* Hypothesis validation.  

Validation requires that each data point be used 
only once.  Multiple models cannot be validated on the same set of data points.  Data mining is hypothesis generation.


Hadley uses a transform > visualize > Model cycle with the final step of communication.  Communication requires good graphics.

Data Mining is not a list of skills but a matrix of them.  It includes a list of modeling methods to learn, data reduction and transformation skills, and a list of
graphical techniques to use.  Along the way it is good to understand something about probability and probability distributions.

A list of methods and some of the concepts associated with them are listed.  I tried to classify each method, but logistic regression is listed twice.
This lists includes methods I have used, although I haven't really used the Apriori, Eclat, FP_Growth methods.  Methods I have not used such as neural networks are not 
listed.

# Methods and Concepts
## Association Rule Mining
### Concepts
1. Item set
3. Support
4. Frequent Item set
5. Rule Generation
### Algorithms
* Apriori Algorithm
* The Eclat Algorithm
* The FP_Growth Algorithm
## Classification, Segmentation and Clustering
### Concepts
1. Distance
1. Dis-proportionality: Observed/Expected
1. Probability: logit function
1. Bayes Theorem
### Methods
* The Naive Bayes Classifier
* Market Basket analysis
* Gamma-Poisson estimator
* K-nearest Neighbors
* Clustering
   * K-means
   * Hierarchical Clustering
   * Distribution-based-Clustering
* Logistic Regression
* regression and classification trees and random forests.  
## Modeling
### Concepts
1. projections
1. Transformations
1. Loss functions
1. Linear Dependence or correlation
1. Principal Components.
1. Model selection.
1. Probability Distributions
1. Co-variate, Modifiers, Confounders
1. Cross validation
1. Over-fitting
1. Model evaluation
### Methods
* Regression modeling
   * Linear models
   * Generalized Linear Models
   * Repeated measures and longitudinal Modeling
   * Non-Linear Modeling 
* logistic regression (bis)
* time series analysis
* Bayesian time series analysis and Kalman Filters.
* Survival analysis.  (Time to event with time dependent covariates.)
* Kernel smoothing and spline methods
* Bootstrap and Monti-Carlo Simulation
* Text Mining



## References 
The Elements of Statistical Learning
https://github.com/tpn/pdfs/blob/master/The%20Elements%20of%20Statistical%20Learning%20-%20Data%20Mining%2C%20Inference%20and%20Prediction%20-%202nd%20Edition%20(ESLII_print4).pdf

R For Data Science
http://r4ds.had.co.nz/

Udemy.com Data Mining with R
https://www.udemy.com/data-mining-with-r-go-from-beginner-to-advanced/

Data Visualization and Statistical Literacy for Open and Big Data
https://www.safaribooksonline.com/library/view/data-visualization-and/9781522525127/
