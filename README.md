# An introduction to Topological Data Analysis 

A repository for a tutorial on Topological Data Analysis (TDA) for the Midwest
Big Data Summer School in 2019 in Ames, Iowa.

This tutorial covers persistent homology and mapper, 
two of the main tools used in TDA.   

## Persistent Homology
For persistent homology, we use the
[Ripser](https://github.com/Ripser/ripser) algorithm, a
very efficient C++ implementation of persistence.
To simplify the presentation and make it easier to get started, 
we rely on [live.ripser.org](https://live.ripser.org) for the actual
calculation.

## Mapper
We use [kepler-mapper](https://github.com/scikit-tda/kepler-mapper) 
for our mapper implementation. Kepler-mapper is written in python,
and easily combines with other machine learning packages,
like [scikit-learn](https://scikit-learn.org/stable/) 
for example.


### Other tutorials
There are a variety of excellent and much more thorough tutorials available
online by experts in the field. Some of the data sets in this tutorial
are either motivated by or come directly from the following:

* [Charleston-TDA-ML](https://github.com/henryadams/Charleston-TDA-ML/wiki).
A tutorial on Persistent Homology written by Henry Adams, 
Melissa McGuirl, and Yitzchak Solomon.

* [Peter Bubenik's TDA with R worksheet](https://people.clas.ufl.edu/peterbubenik/intro-to-tda/). A tutorial on using R to analyze data with Persistence Landscapes.

* [MAA-NCS18](https://github.com/MatthewZabka/MAA-NCS18). Matt Zabka's 
Persistence Homology tutorial.

* [R-TDA tutorial](http://www.stat.cmu.edu/topstat/topstat_old/Talks/files/Jisu_150623_TDA_tutorial.pdf). An R-TDA worksheet tutorial written by Jisu Kim.

This list is nowhere near complete, and there are lots of other great tutorials for learning TDA.
