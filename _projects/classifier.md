---
layout: page
title: Classifiers for Predicting the Success of the Generalization of Fulton’s Intersection Multiplicity Algorithm
description: In this paper we propose properties of polynomial systems which we believe may correspond to the success of the Generalization of Fulton’s Intersection Multiplicity Algorithm, and compare 4 classifiers trained on a data set generated from extracting these properties from randomly generated regular sequeces.
img: /assets/img/ROC_Curve.png
importance: 5
category: work
---

The generalization of Fulton’s intersection multiplicity algorithm provides a powerful tool for computing intersection multiplicities without the use of standard bases. Since the generalization of Fulton’s algorithm may fail on some inputs it is natural to wonder what
properties of the input can be used to determine the algorithm’s success before runtime. In
this [paper](/assets/pdf/predictingSuccessOfIMHeuristics.pdf) we propose several candidate properties of these polynomial input systems and
train several classifiers on the features extracted using the proposed properties. The results
show that several of the properties can be used to reliably predict the success of the generalization of Fulton’s algorithm on tri-variate systems. 

Further effort is required to expand this experiment to `n`-variate systems, particularly with respect to the efficient generation of `n x n` regular sequences.

__Resources:__

* [Corresponding Slides](/assets/pdf/predictingSuccessOfIMHeuristics_slides.pdf)



