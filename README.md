---
layout: home
title: Topics in High-Dimensional Econometrics and ML Theory

permalink: /:path/
seo:
  type: Course
  name: Topics in High-Dimensional Econometrics and ML Theory
nav_exclude: true
---
# Topics in High-Dimensional Econometrics and ML Theory
{:.no_toc}

{: .mb-2 }
Emory University, Spring 2024
{: .mb-0 .fs-6 .text-grey-dk-000 }

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## About

Designed to be a Directed Study (a intensive reading in econometrics on a topic not covered in a regular course at Emory University), this course will cover a variety of topics in high-dimensional econometrics and machine learning theory. The course is based on student presentations, and discussions among participants (students and faculty invited). 


## Course Description

This course aims to be a in-depth exploration of the theoretical foundations and practical applications of high dimensional statistics and machine learning theory at the graduate level. Since this a topics course, the content will be based on the interests of the participants and student presenter. The primary objective of this directed reading is to provide a comprehensive and self-contained overview of high-dimensional statistics, covering topics such as concentration inequalities, empirical processes, uniform laws, reproducing kernel Hilbert spaces, semiparametric theory, and their applications in causal inference.

## Content 

### Topic 1: Concentrations Inequalities

  * Motivating examples 
  * Classical bounds

### Topic 2: Uniform law of large numbers

  * Uniform convergence
  * Rademacher complexity

### Topic 3: Sparse linear models in high-dimensions

  * Different types of sparsity
  * Shrinkage estimators and regularizers
  * Regularization bias


### Topic 4: Reproducing Kernel Hilbert Spaces

  * Hilbert spaces
  * Kernels and operations
  * Reproducing kernel Hilbert spaces
  * Kernel Ridge regression

### Topic 5: Semiparametric Efficiency Theory
  
  * Semiparametric efficiency
  * Efficiency Influence Functions
  * Pathwise Defferentiability and Distributional Taylor Expansion

### Topic 6: Double/Debiased Machine Learning

  * Neyman Orthogonality
  * Sample Splitting
  * Cross-fitting
  * Applications

## References

The content of the course will be based on the following references:

1. [High-Dimensional Statistics: A Non-Asymptotic Viewpoint](https://www.cambridge.org/us/universitypress/subjects/statistics-probability/statistical-theory-and-methods/high-dimensional-statistics-non-asymptotic-viewpoint?format=HB&isbn=9781108498029) by Martin Wainwright.

2. [Lectures Notes for Machine Learning Theory (CS229M/STATS214)](https://tselilschramm.org/mltheory/ma.pdf) by Tengyu Ma.

3. [Introduction to RKHS, and some simple kernel algorithms](https://www.gatsby.ucl.ac.uk/~gretton/coursefiles/lecture4_introToRKHS.pdf) by Arthur Gretton.

4. [Machine Learning for Econometrics](https://drive.google.com/file/d/1L_iervUBKj3RsXHLEGOtAFlyHEHpmyT4/view) by Christophe Gaillac and Jeremy L’Hour.

## Acknowledgments

I thank Prof. [David Jacho-Chavez](https://www.davidjachochavez.org/) for his guidance and serve as Faculty Sponsor to develop this course.