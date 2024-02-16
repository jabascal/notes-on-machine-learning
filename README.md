# notes-on-machine-learning

Notes on machine learning: Theory and examples.

## Summary

*Notes on machine learning* (ML) provides a summary of the theory and examples using R and Python. There are great books that introduce the theory of ML and statistical learning [1]-[3]. In the case of examples, there is also a large number of sites and blogs. Many blogs are a great sources of implementations but in many cases the mathematical descriptions and links between theory and examples are missing.    

This repository gathers the theory and examples from the course in Statistical Learning by T Hastie and R Tibshirani from Stanford University ([online course](https://online.stanford.edu/courses/sohs-ystatslearning-statistical-learning)), several books on statistical learning and machine learning [1]-[3] and a diverse source of examples based on different sources ([Scikit-Learn Machine Learning in Python](https://scikit-learn.org/stable), examples in R from the Statistical Learning course, among others). Examples are provided using google colab cloud services. 

## Contents
The first part of this repository comprises theory and examples on statistical learning and machine learning: 

* [Theory](https://colab.research.google.com/drive/1R5NFTzQqUwz01_1kFdB713auQU-fOgLR#scrollTo=mV7Ze-DFpsbd): Theory and definitions on statistcs, information theory and machine learning. 

* Descriptive statistics/Exploratory analysis
    *   Exploratory image analysis - Density plots: [colab notebook](https://github.com/jabascal/notes-on-machine-learning/blob/master/exploratory_analysis_histograms.ipynb), [Medium article](https://medium.com/@juanabascal78/exploratory-image-analysis-part-1-advanced-density-plots-19b255075dbd)
    *   Exploratory image analysis - Projection embeddings on Tensorboard: [colab notebook](https://github.com/jabascal/notes-on-machine-learning/blob/master/exploratory_analysis_embedding_tb.ipynb), [Medium article](). 


* Classification
    *   [Classification](https://colab.research.google.com/drive/1JFIdH2KGtlHSKJX5TsnMMzlYmZetrqXx?usp=sharing): Introduction to classification methods (logistic regression, LDA, QDA). 
    *   [Classification in R - Example S&P 500](https://colab.research.google.com/drive/1ji_5NzWL_JmrKGSTy49k-5i4PF0glwWO#scrollTo=8bE8yP1Ohf0B): Predict direction on percentage return of S&P 500 using logistic regression, LDA and QDA.  
    *   [Classification in R - Example Caravan insurance](https://colab.research.google.com/drive/1EzIgorpz0mj6KkgOfasdNXkL-Rrypf-1#scrollTo=8bE8yP1Ohf0B): Predict customers that buy insurance using logistic regression and K-NN. 
    *   [Classification in Python - Example iris dataset](https://colab.research.google.com/drive/11icBQQRi2R2GsmrUgblNEi0fgVrSjLY8#scrollTo=8bE8yP1Ohf0B): Comparison of wide range ol algorithms: logistic regression, K-NN, SVC, decission trees, random forest and ensembme methods (voting classifier and Adaboost). 

* [Markov random fields](https://colab.research.google.com/drive/1kS0iExQAe6P0TJ1RADAqFtxzU2Iscm77?usp=sharing): Introduction to to directed graphs or Markov Random Fields (MRF)

* [Model selection, assessment and resampling methods](https://colab.research.google.com/drive/1kDbgbdCwlgUOSB1QM6d97mlT9FUOiOb7#scrollTo=hEA06EZ9eVEF&line=1&uniqifier=1): Validation strategies, cross validation and boostrap methods. 

## Setup for running examples
*   Setup for using R in google colab: [setup_for_using_R](https://colab.research.google.com/drive/1n-sSjdtflSvF5nPoe0qvSFRtfk_XfImf?usp=sharing)

## Bibliography
[1] Trevor Hastie and Robert Tibshirani, and Jerome Friedman. The elements of statistical learning, Springer New York Inc., Springer Series in Statistics, 2001. 

[2] Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani. An introduction to statistical learning with applications in R, Springer New York Heidelberg Dordrecht London, ISBN 978-1-4614-7137-0, 2013.

[3] Christopher M Bishop. Pattern recognition and machine learning, Springer Science+Business Media, LCC, 2006.