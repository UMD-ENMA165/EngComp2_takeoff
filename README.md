# Engineering Computations Module 2

*[forked from https://github.com/engineersCode/EngComp2_takeoff]*

_Engineering Computations_ is a collection of stackable learning modules, flexible for adoption in different situations.
It aims to develop computational skills for students in engineering, but it can also be used by students in other science majors.
The course uses the Python programming language and the Jupyter open-source tools for interactive computing.

The first module, [_"Get data off the ground with Python"_](https://github.com/engineersCode/EngComp1_offtheground),
assumed no coding experience and created a foundation with Python programming constructs and data structures.
You learned to play with strings, lists and NumPy arrays, using indexing, slicing, `for`- and `if`-statements, and Python functions.

This second course module explores practical statistical analysis with Python, and the [`pandas`](https://pandas.pydata.org) library for data analysis.

## Module 2: Take off with stats in Python

_Hands-on data analysis using a computational approach and real-life applications._

Clone the repository to your desktop and run the notebooks in `jupyter lab`. Commit the results as a branch and submit a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests). You are encouraged to work in teams of two.

### Lesson 1: Cheers! Stats with beers

[1_Cheers_Stats_Beers.ipynb](notebooks_en/1_Cheers_Stats_Beers.ipynb)

Exploratory analysis using a data set of canned craft beers in the US. Introduces the `pandas`library and its data types: Data Frames and Series. Use `pandas` to read a data file, extract selected columns, and remove null values. Descriptive statistics: measures of central tendency and variability. Distribution plots: histograms with Matplotlib. Comparing with a normal distribution.

### Lesson 2: Seeing stats in a new light

[2_Seeing_Stats.ipynb](notebooks_en/2_Seeing_Stats.ipynb)

Continuing with the data set of canned craft beers, this lesson focuses on _visualizing statistics_. For quantitative data: histograms and box plots; for categorical data: bar plots. Visualizing multiple data with scatter plots and bubble charts.

### Lesson 3: Lead in lipstick

[3_Lead_in_Lipstick.ipynb](notebooks_en/3_Lead_in_Lipstick.ipynb)

A full worked example using what you learned in lessons 1 and 2: using data from studies by the US Food and Drug Administration on the lead content in lipstick, we fact-check alarming news headlines. Based on Prof. Kristin Sainani's lecture, ["Exploring real data: lead in lipstick,"](https://youtu.be/nlKIT-_b2jU) of her Stanford Online course ["Statistics in Medicine."](https://lagunita.stanford.edu/courses/Medicine/MedStats-SP/SelfPaced/about)

### Lesson 4: Life expectancy and wealth

[4_Life_Expectancy.ipynb](4_Life_Expectancy.ipynb)

Deeper dive into `pandas`, using data for life expectancy and per-capita income over time, across the world. Inspired by the work of Hans Rosling.
Pandas methods: `head()`, `info()`, `value_counts()`, `groupby()`, `describe()`, `groupby.first()`, `groupby.get_group()`, `idxmin()`
Categorical data type.
Bubble plots, spaghetti plots, and interactive widgets.

## Further Information

> (**note:** the following doesn't appear to work due to a problem with installing `pandas` on the Binder server)
>
>Get an interactive session in [MyBinder.org](https://mybinder.org/) with these course materials by clicking on the button below.
> Select the folder `notebooks_en` to access the five lessons of this course as fully executable Jupyter notebooks.
>
> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/engineersCode/EngComp2_takeoff/master)


* **Join the [open online course](http://go.gwu.edu/engcomp2)** in our _Open edX_ platform.
* **Get a PDF version to print**: _Engineering Computations Module 2: Take off with stats._ figshare. https://doi.org/10.6084/m9.figshare.5673499.v1

## Copyright and License

(c) 2017 Lorena A. Barba, Natalia C. Clementi. (c) 2021 Jonathan E. Guyer. All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/engineersCode/EngComp/blob/master/LICENSE). We are happy if you re-use the content in any way!

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
