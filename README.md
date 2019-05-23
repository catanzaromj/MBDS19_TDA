# An introduction to Topological Data Analysis 

A repository for a tutorial on Topological Data Analysis (TDA) for the Midwest
Big Data Summer School in 2019 in Ames, Iowa.

This tutorial covers persistent homology and mapper, 
two of the main tools used
in TDA. 

## Persistent Homology
For persistent homology, we use the
[https://github.com/Ripser/ripser](Ripser) algorithm, a
very efficient C++ implementation of persistence.
To simplify the presentation and make it easier to get started, 
we rely on [https://live.ripser.org](live.ripser.org) for the actual
calculation.

## Mapper
We use [https://github.com/scikit-tda/kepler-mapper](kepler-mapper) 
for our mapper implementation. Kepler-mapper is written in python,
and easily combines with other machine learning packages,
like [https://en.m.wikipedia.org/wiki/Scikit-learn](sci-kit learn) 
for example.


### Other tutorials
There are a variety of excellent and much more thorough tutorials available
online by experts in the field. Some of the data sets in this tutorial
are either motivated by or come directly from the following:

* [https://github.com/henryadams/Charleston-TDA-ML/wiki](Charleston-TDA-ML).
A tutorial on Persistent Homology written by Henry Adams, 
Melissa McGuirl, and Yitzchak Solomon.

* [https://people.clas.ufl.edu/peterbubenik/intro-to-tda/](Peter Bubenik's TDA with R worksheet). A tutorial on using R to analyze data with Persistence Landscapes.

* [https://github.com/MatthewZabka/MAA-NCS18](MAA-NCS18). Matt Zabka's 
Persistence Homology tutorial.

* [http://www.stat.cmu.edu/topstat/topstat_old/Talks/files/Jisu_150623_TDA_tutorial.pdf](R TDA tutorial). An R-TDA worksheet tutorial written by Jisu Kim.

This list is nowhere near complete, and there are lots of other great tutorials for learning TDA.
