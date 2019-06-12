---
Machine Learning in Physics
===

This is to facilitate the “Machine Learning in Physics” course that I am
teaching at Sharif University of Technology for winter-19 semester. For more
information, see the course page at

<http://sharif.edu/~sraeisi/ML>

Requirements:
=============

-   Decent understanding of programming and python and the following
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

-   Final exam (set for Thursday, June 20th, 9AM): 30% 

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

-   Oral presentation (See me to set up the time, it should be before **June 24th**.)

-   Written term paper (It should be submitted by **July 5th**.)

__Some notes:__
- Make sure you include citations to all the resources you use!
- You should submit your work as a group rather than separate individual submissions.
- Scripts, notebooks and figures without description would not count toward your grade.
- Your codes should include enough comments and information that can be easily followed.
- It is essential that all group members contribute (make commits) to their repositories, this is the only way I can make sure that everyone participated in their project. 



Assignments
==================

| Assigment  | Deadline and Submission link | Solutions |
|------------|------------------------------|-----------|
|[Assigment 1](Assignments/A1/A1_Problems.ipynb)| [Submit it here](https://goo.gl/forms/WK4URJLc8LsxIVup2) | Solution 1 |
|[Assigment 2](Assignments/A2/A2_Problems.ipynb)| [Deadline: extended to March 22th](https://goo.gl/forms/MLQ2PTLAzCXrYfBV2) | Solution 2 |
|[Assigment 3](Assignments/A3/A3_Farsi_Hand_written_digits.ipynb)| [Deadline: April 18th](https://forms.gle/AQ1gL2wSYLLb8LT1A) |  |
|[Assigment 4](Assignments/A4/Assignment4.md)| [Deadline: May 9th](https://forms.gle/uyHW7HqvYHoWbQ5T6) |  |
|[Assigment 5](Assignments/A5/NN_datareduction.md)| [Deadline: May 26th](https://forms.gle/kSyTRbFwLzJpK77H9) |  |


Reading Materials
=============
- Mehta, Pankaj, et al. "A high-bias, low-variance introduction to machine learning for physicists." Physics Reports (2019).

- Nielsen, Michael A. Neural networks and deep learning. Vol. 25. San Francisco, CA, USA:: Determination press, 2015. ([Available online](http://neuralnetworksanddeeplearning.com) )

- Chollet, François,  ["Deep Learning with Python." (2018)](http://bioserver.cpgei.ct.utfpr.edu.br/disciplinas/eeica/papers/Livros/%5BChollet%5D-Deep_Learning_with_Python.pdf).


Table of contents 
==================

The course material is posted here and you can use either [Google
Colab](http://colab.research.google.com/) or [Mybinder](http://mybinder.org/) to
work with these Jupyter notebooks.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sraeisi/MachineLearning_Physics/master)

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/) 



| Topic                                 | Contents of the Lectures                                                                                                                                                                                              | Notebook(s) |
|---------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| Basics of machine learning            | Lecture 1: Introduction To Machine Learning <br> Notation <br> Regression, logistic regression and classification  <br><br> Lecture 1: Noise <br> ML beyond simple examples  |       [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_1/MLP_lec_1_Introductory_notes_B.ipynb)   <br><br><br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_1/MLP_lec_1_Introductory_notes_C.ipynb) <br> |
|Basic Techniques|Lecture 2: Basic Techniques <br>Overview of some of the most common techniques  <br><br> Lecture 2: Kernels|   [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_2/Basics_techniques.ipynb)  <br><br> <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_2/Kernels.ipynb) |
| Model Selection   | Lecture 3: Concepts from Statistical Learning <br> - Variance and bias <br> - Learning and Validation curves <br> Bayesian inference <br><br> Lecture 3: Model Complexity <br>- Practical model selection with scikit-learn <br><br> Lecture 3: Model Evaluation        <br> -Confusion Matrix <br> - Recall, precision, f-score <br> -  Precision-recall and ROC curve, ROC_AUC             |           [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_3/Model_Selection.ipynb)    <br><br><br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_3/Model_Selection_complexity.ipynb)    <br><br><br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_3/Model_Selection_Evaluation.ipynb)  |
| Data Preparation   | Lecture 4: Data Preparation <br>- Standardization <br>- Clean-up: nan and outliers <br>- Feature Selection: Features Importance, variance threshold<br> <br><br><br> Lecture 4: Data Reduction   <br> Feautre Extraction: PCA, Manifold Learning        |       [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_4/Data.ipynb)    <br><br><br><br><br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_4/Data_Reduction.ipynb) |
| Ensemble Techniques | Lecture 5: Ensemble Techniques <br> Aggregation, Stacking, Bagging, Boosting                                                                                                                                                                                   |  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_5/Ensemble_techniques.ipynb)            |
| Neural Networks                       | Feedforward <br> - Model Geometry and formulation <br> - Universality <br> - Non-linearity: Activation function <br>  Back propagation <br> - Details <br> -   Initialization <br>-   Optimizations <br> -   Batch and epoch <br> -   Couple of example <br> Practical implementations: <br> -   TensorFlow and Keras                                                                                                                                                                                       |   [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_6/Logistic_Regression.ipynb)       <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_6/NN_FeedForward.ipynb) <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_6/NN_implementation.ipynb ) <br> [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_6/Optimizing_the_Optimization.ipynb )  <br> [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_6/NN_Overfitting.ipynb )  |
| Convolutional Neural Networks         | - Basic Idea of Convolution <br> - Simple implementation of convnet with Keras <br> - Well-known models        <br> Some examples                                                                                                                                                           |   [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_7/Convolution.ipynb)   <br> [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_7/Convnet.ipynb)   <br> [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_7/Galaxy_ZooII.ipynb)      <br> [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_7/Convnet_visulaization.ipynb)     |
| Recurrent Neural Network              | - Basic Idea <br> - Example   |  [Note](Lec_8/Recurrent%20Neural%20Networks.pdf) <br>   [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_8/Simple_RNN.ipynb) <br>  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sraeisi/MachineLearning_Physics/blob/master/Lec_8/Sunspots.ipynb)       |
| Reinforcement Learning                   | Basic Idea and details Example(s)                                                                                                                                                                     |             |

 


Cheat sheets and guides
=======================

See the files in the CheatSheet folder.

| Item                                  | Description                                                                                                                                                        |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Jupyter](CheatSheets/Jupyter%20Notebook_CheatSheet.pdf)    | Jupyter provides an interactive environment for programming. We will be mostly using the python 3 kernel.                                                               |
| [Git and Github](CheatSheets/git-CheatSheet.pdf)                        | Git provides a strong infrastructure for version control. Github is web-based hosting service for version control and it also provides services for collaboration. |
| [Python](CheatSheets/Python_CheatSheet.pdf)                               | It is the programming language that we will be mostly using for this course.                                                                                       |
| [NumPy](CheatSheets/NumPy_Basics_CheatSheet.pdf  )                               | It’s a python library that provides strong and efficient tools for manipulation of high-dimensional arrays.                                                        |
| [SciPy](CheatSheets/SciPy_CheatSheet.pdf)                                 | It’s a python library, built on NumPy for mathematical and scientific computing.                                                                                   |
| [Pandas_basics Pandas 2](CheatSheets/Pandas_basics_CheatSheet.pdf ) <br> [Importing data](CheatSheets/Pandas_2_CheatSheet.pdf) | It’s a python library, built on NumPy that provides efficient tools for handling and analysis of data.                                                             |
| [Matplotlib](CheatSheets/Matplotlib_CheatSheet.pdf) <br> [Seaborn](CheatSheets/Seaborn_CheatSheet.pdf)                    | These are two of the most common python library for visualization.                                                                                                 |
| [Scikit-Learn](CheatSheets/Scikit-Learn_CheatSheet.pdf)                          | It’s a python library that provides a nice and fairly efficient implementation of most the machine learning techniques and ideas.                                  |
| [Keras](CheatSheets/Keras_CheatSheet.pdf)                                 | It is python library that provides a high-level and easy-to-use interface for Tensorflow and some other deep learning libraries.                                   |





