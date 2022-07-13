# advanced_astroinformatics

Advanced Astroinformatics (Universidad de Antofagasta) material for the project



-----------------

**Variability detection and classification in astronomical datasets**

What is the problem? 

Nowadays large-scale astronomical surveys enable us to see the universe in a much more detail. Currently, the methodological
approach to analyze the gathered data is particularly different than the one implemented in the past. Historically, variable 
stars have been identified by manually sorting images or making brightness-over-time (light curve) plots based on small, targeted surveys. 
Modern all-sky astronomical surveys allow for evaluating huge amounts of data. Machine-learning tools are extremely important to cope with such an amount of 
data, as well as to allow for a more precise evaluation of the data than done with classical algorithms.

Approaches like that were already carried out and proven as very successful for some astronomical surveys such as Pan-STARRS1, which provided relatively sparse data.

What does the project need to do?

The project is structured as follows:

1) an overview of machine-learning techniques applicable for astronomical data (depending on preknowledge, this can serve either as an intro or as a refresher)

2) preparing astronomical data (which comes in the form of tables containing light curves) for processing them with machine learning techniques

3) applying machine-learning techniques to astronomical data

4) understanding the benefits, relevance and limitations of machine learning classification on the example of the light-curve data provided for this project

The outcome of this project will be a machine-learning program which is capable of classifying variable star light curves.


How do you get started? 

1) Code will be written in Python3.x. Code should be made available on github.

Regarding Python: If you don't have Python3.x installed, please take a look here:
https://github.com/ninahernitschek/astr3890/blob/main/class_notebooks/lecture_1.ipynb under "1. Python installation".
Make sure to have the following Python packages installed:
numpy, scipy, matplotlib, sklearn, astroml, corner. The "corner" library is this one: https://corner.readthedocs.io/en/latest/
In case you don't have much Python knowledge yet, I can recommend taking a look at this course (but you could also take another one):
https://www.w3schools.com/python/python_intro.asp

Regarding github: If you haven't done so already, please sign up for github and create a repository.


2) Lecture "Selected Topics: Data Science for Large Astronomical Surveys" available on https://github.com/ninahernitschek/astr3890#readme
Here I can especially recommend lecture 10, "Data Mining & Machine Learning: Intro to Scikit-Learn" as well as lecture 13, "Supervised Classification". Slides as well as Jupyter notebooks are provided.
For students with little or no preknowledge regarding coding in Python, I recommend strongly taking a look at lecture 1, "Introduction & Introduction to Python".

3) Read Baron (2019), "Machine Learning in Astronomy: A Practical Overview" http://research.iac.es/winterschool/2018/media/summaries/ml_summary_dbaron.pdf
This should give an introduction to the relevance of machine learning concepts in nowadays astronomical research.

4) There is a book
"Statistics, Data Mining, and Machine Learning in Astronomy: A Practical Python Guide for the Analysis of Survey Data" by Ivezic et al.
In case you easily have access to this book, please use it for this project. Otherwise, a lot of example Python code is also available on the book's website https://www.astroml.org/ for free.

5) Throughout the project, the online documentation of many Python libraries, especialls scikit-learn (sklearn) will be very helpful. https://scikit-learn.org/stable/tutorial/basic/tutorial.html

How will this help the big picture? 

Most stars, like the sun, have approximately constant brightness, but approximately 1 - 5 % of all stars show a significant amount of variability in their intensity. 
Variable stars are important tracers of the Milky Way's evolution. Stars such as RR Lyrae allow to precisely estimate distances in the 
old Milky Way components, providing important information to answer questions regarding formation and evolution of galaxies. Other stars such as spotted stars allow 
to gain insight into magnetic activity of stars. Rare supernova events allow to calculate distances at cosmological scales. This research project aims to test the 
effectivity of using machine learning to classifying variable stars for TESS, whose data quality should allow for a very detailed classification.








