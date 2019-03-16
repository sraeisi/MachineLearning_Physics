---
Machine Learning in Physics
===

This is to facilitate the “Machine Learning in Physics” course that I am
teaching at Sharif University of Technology for winter-19 semester. For more
information, see the course page at

<http://sharif.edu/~sraeisi/ML>

Requirements:
=============

-   Decent understanding of programming and python syntax and the following
    libraries

    -   Numpy

    -   Pandas

    -   Plotting and graphical presentation tools in python

-   Git and Github (if you not familiar, let me know.)

-   Basic understanding of quantum mechanics and statistics.

-   Basic understanding of machine learning

Marking Scheme
==============

This is a tentative plan and we may change it as we move on.

-   Course Project: 40%

-   Assignments: 30%

-   In-class exercises 10%

-   Final exam: 30%

These add up to 110% which include the bonus as well.

Course Projects
===============

This is a group project and counts towards 40% of the final grade.

The idea is that each group decides on a project at the beginning of the course
and apply everything that we cover to their project. Here are some of the
expectations for the course project:

-   Some initial proposal: Clear statement of the problem and some primary
    assessment of why using ML could help answer this problem. (Due Feb 28th)

-   Data collection/generation and preparation: (Due March 15th => <span style="color:red">Extended to March 20th</span> )
    - Create a folder for this part
    - Have a description (readme file) for the data
    - Describe your data: Where it comes from, different feautres and their physical significance, your target value(s)
    - Create a notebook and implement the following in different sections:
        - Clean up the data (remove the missing data and convert everything to numerical values)
        - Scale your data
        - Analysis of features and target (Histograms and )
        - Feature selection (Try different techniques and assess how well they work on your data)
        - Feature extraction (Try different techniques and assess how well they work on your data)

-   Application of the basic ML techniques: (Due April 15th)

    -   A table of assessment (Will give an example later.)

    -   Investigation of variance and bias of the techniques investigated.

    -   Learning and validation curves

-    Application of NN and setting the hyperparameters (Due April 30th)

-   Oral presentation (TBA)

-   Written term paper (TBA)

__Some notes:__
- Make sure you include citations to all the resources you use!
- You should submit your work as a group rather than separate individual submissions.
- Scripts, notebooks and figures without description would not count toward your grade.
- Your codes should include enough comments and information that can be easily followed.



Assignments
==================
Assigment 1: You can submit the first assignment here:

https://goo.gl/forms/WK4URJLc8LsxIVup2

Assigment 2:  <span style="color:red">Deadline extended to March 22th</span> 

You can submit the first assignment here:

https://goo.gl/forms/MLQ2PTLAzCXrYfBV2


Table of contents 
==================

The course material is posted here and you can use either [Google
Colab](http://colab.research.google.com/) or [Mybinder](http://mybinder.org/) to
work with these Jupyter notebooks.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sraeisi/MachineLearning_Physics/master)

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/) 

| Topic                                 | Contents of the Lectures                                                                                                                                                                                              | Notebook(s) |
|---------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| Basics of machine learning            | Introduction and notation <br> Regression, logistic regression and classification <br> overview and practical tips <br> Why? ML beyond simple examples <br> Overview of some of the most common techniques |       Lecture 1 <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_1/MLP_lec_1_Introductory_notes_B.ipynb)   <br>Lecture 1: Noise <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_1/MLP_lec_1_Introductory_notes_C.ipynb) <br>Lecture 2: Basic Techniques <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_2/Basics_techniques.ipynb)  <br>Lecture 2: Kernels <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_2/Kernels.ipynb)  |
| Concepts from Statistical learning    | Variance and bias <br> Learning curves <br> Model selection and validation curve <br> Practical methods for dealing with overfitting <br> Bayesian inference                                                                                        |         Lecture 3: Model Selection <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_3/Model_Selection.ipynb)    <br> Lecture 3: Model Selection-p2 <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_3/Model_Selection_complexity.ipynb)   <br> Lecture 3: Model Selection-p3 <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_3/Model_Selection_Evaluation.ipynb)  |
| Data Preparation                      | Standardization <br>Clean-up: nan and outliers <br> Data reduction: PCA, variance threshold …                                                              |     Lecture 4: Data Preparation <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_4/Data.ipynb)    <br> Lecture 4: Data Reduction <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_4/Data_Reduction.ipynb) |
| Ensemble Techniques | Aggregation  <br>  Stacking, Bagging, Boosting                                                                                                                                                                                   | Lecture 5: Ensemble Techniques <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_5/Ensemble_techniques.ipynb)            |
| Neural Networks                       | Feedforward <br> - Model Geometry and formulation <br> - Universality <br> - Non-linearity: Activation function <br>  Back propagation <br> - Details <br> -   Initialization <br>-   Optimizations <br> -   Batch and epoch <br> -   Couple of example <br> Practical implementations: <br> -   TensorFlow and Keras                                                                                                                                                                                       |             |
| Convolutional Neural Networks         | Basic Idea and details Example(s)                                                                                                                                                                     |             |
| Recurrent Neural Network              | Basic Idea and details Example(s)                                                                                                                                                                     |             |
| Reinforced Learning                   | Basic Idea and details Example(s)                                                                                                                                                                     |             |

 

Cheat sheets and guides
=======================

See the files in the CheatSheet folder.

| Item                                  | Description                                                                                                                                                        |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Jupyter                               | It provides an interactive environment for programming. We will be mostly using the python 3 kernel.                                                               |
| Git and Github                        | Git provides a strong infrastructure for version control. Github is web-based hosting service for version control and it also provides services for collaboration. |
| Python                                | It is the programming language that we will be mostly using for this course.                                                                                       |
| NumPy                                 | It’s a python library that provides strong and efficient tools for manipulation of high-dimensional arrays.                                                        |
| SciPy                                 | It’s a python library, built on NumPy for mathematical and scientific computing.                                                                                   |
| Pandas_basics Pandas 2 Importing data | It’s a python library, built on NumPy that provides efficient tools for handling and analysis of data.                                                             |
| Matplotlib Seaborn                    | These are two of the most common python library for visualization.                                                                                                 |
| Scikit-Learn                          | It’s a python library that provides a nice and fairly efficient implementation of most the machine learning techniques and ideas.                                  |
| Keras                                 | It is python library that provides a high-level and easy-to-use interface for Tensorflow and some other deep learning libraries.                                   |





Please Fill in the student list form
====================================
<https://goo.gl/forms/ZNp4X5MvuzGmOVKq2>
