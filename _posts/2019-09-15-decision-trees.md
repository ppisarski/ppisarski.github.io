---
layout: post
title: Decision Trees
---

Decision trees can be used for problems where 
attributes are both numeric and nominal,
target function takes on a discrete number or continuous values,
data may have errors and missing values.

# CHAID algorithm

The acronym CHAID stands for Chi-squared Automatic Interaction Detector.
The algorithm was originally proposed by Kass (1980) 
and is one of the oldest tree classification methods.
CHAID builds trees where more than two branches (also known as non-binary) 
can attach to a single root node.



# CART algorithm

CART: Breiman et al (1984) - classification and regression trees




# QUEST algorithm

QUEST algorithm was proposed by Loh and Shih (1997). 
The acronym stands for Quick, Unbiased, Efficient, Statistical Tree.


CART was slow. 
This was because CART considers all possible split points.
Quest doesn't do it that way
CHAID on the other hand is biased toward branches with a large number of child nodes.
What is means is that CHAID gravitates towards categorical variables with lots of categories.
Or grows trees that are wider than other techniques.

Quest uses statistical tests instead of a brute force search for all possible cut points.
Uses different tests appropriate for different variable types (nominal, ordinal, and scale) and ranks the p-values.
Uses surrogates for missing data just like CART.

# C5.0 algorithm

C5.0 other algorithms that are comming up C4.5 and ID3
Ross Quinlan is the person who developed all three algorithms.
He licensed C5.0 
