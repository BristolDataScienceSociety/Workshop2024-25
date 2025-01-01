# What is Machine Learning? (total ~20 mins to read)

🔴 **TODO**
- a brief introduction explain what is machine learning and what we can do by using machine learning methods, can use text + images to illustrate and give an intuition.
- may include history, challenges
- relation to AI and DL (could refer to wikipedia), use a Venn graph

Machine learning (ML) is a field of study in artificial intelligence concerned with the development and study of statistical algorithms that can learn from data and generalize to unseen data, and thus perform tasks without explicit instructions. Advances in the field of deep learning have allowed neural networks to surpass many previous approaches in performance.

The following graph shows relationship between three key concepts: Artificial Intelligence (AI), Machine Learning (ML) and Deep Learning (DL).

<img src="img/AI_hierarchy.png" alt="AI hierarchy" height=400px>

## History

The term machine learning was coined in 1959 by Arthur Samuel, an IBM employee and pioneer in the field of computer gaming and artificial intelligence. The synonym self-teaching computers was also used in this time period.

The earliest machine learning model was introduced in the 1950s when Arthur Samuel invented a program that calculated the winning chance in checkers for each side.

By the early 1960s, an experimental "learning machine" with punched tape memory, called Cybertron, had been developed by Raytheon Company to analyze sonar signals, electrocardiograms, and speech patterns using rudimentary reinforcement learning.

Tom M. Mitchell provided a widely quoted, more formal definition of the algorithms studied in the machine learning field: "A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P if its performance at tasks in T, as measured by P, improves with experience E."

Modern-day machine learning has two objectives. One is to classify data based on models which have been developed; the other purpose is to make predictions for future outcomes based on these models.

## Approaches

Machine learning approaches are traditionally divided into three broad categories, which correspond to learning paradigms, depending on the nature of the "signal" or "feedback" available to the learning system:

- Supervised learning: The computer is presented with example inputs and their desired outputs, given by a "teacher", and the goal is to learn a general rule that maps inputs to outputs. There are two major types: Regression to predict a number and Classification to predict categories.

- Unsupervised learning: No labels are given to the learning algorithm, leaving it on its own to find structure in its input. Unsupervised learning can be a goal in itself (discovering hidden patterns in data) or a means towards an end (feature learning).

- Reinforcement learning: A computer program interacts with a dynamic environment in which it must perform a certain goal (such as driving a vehicle or playing a game against an opponent). As it navigates its problem space, the program is provided feedback that's analogous to rewards, which it tries to maximize.[5]
Although each algorithm has advantages and limitations, no single algorithm works for all problems.

# What will we learn in this TB?

- Workshop 6: loss function, linear regression, generalised linear model (extra)
- Workshop 7: decision tree and random forest
- Workshop 8: support vector machine (SVM) and principal component analysis (PCA)
- Workshop 9: k-neighbours and unsupervised learning algorithms (i.e. k-means)
- Workshop 10: multilayer perceptron (MLP)

# Prerequisites

1. Python Basics

   All the Python knowledge needed is available in previous workshop materials.

   - Workshop 1: variables, data types, operators, control flows, functions and modules
   - Workshop 2: data structures, object-oriented programming (OOP)
   - Workshop 3: Numpy (comprehensive functionalities for scientific computing)
   - Workshop 4: Pandas (data analysis)
   - Workshop 5: matplotlib.pyplot (data visualisation)

   The last three workshops are important as you can find the usage of them in everywhere of machine learning, make sure you fully understand contents in these materials.

2. Jupyter Notebook

   The Jupyter Notebook is the original web application for creating and sharing computational documents. It offers a simple, streamlined, document-centric experience.

   You can simply see it as a combination of Markdown and Python.

   You can open Jupyter Notebook files (.ipynb) in github if you did not installed the software, but with the software you can run Python code in these files by yourself. You can follow the instructions to [install Jupyter Notebook](https://jupyter.org/install#jupyter-notebook).