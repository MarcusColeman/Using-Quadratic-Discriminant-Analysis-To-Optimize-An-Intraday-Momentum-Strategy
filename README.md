# Using-Quadratic-Discriminant-Analysis-To-Optimize-An-Intraday-Momentum-Strategy

# Problem Statement

This notebook provides an overview of an approach for optimizing intraday trading strategies. Often, algorithmic/quantitative traders encounter 
a common problem of taking a strategy that shows potential and getting it into a production quality state. This post seeks to replicate
that problem and offer a means of solving it.

# Data
3 minute data on the eMini S&P 500 is used for this analysis

# Insights

The commencement of this work shows that an intraday strategy can be improved even in the absence of a significant change in the win 
loss ratio. The QDA model is used to predict losing trades before they occur which allows for the avoidance of poor trade selection.

