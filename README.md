# Final Project for Programming Data Analysis Project
# Lecturer - Brian McGinley
# Submission Date - 16/12/19
# Objectives - 
# * Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four diﬀerent variables. 
# * Investigate the types of variables involved, their likely distributions, and their relationships with each other. 
# * Synthesise/simulate a data set as closely matching their properties as possible.
# * Detail your research and implement the simulation in a Jupyter notebook – the data set itself can simply be displayed in an output cell within the notebook.

# The primary resources for data analysis of the simulated dataset in this assignment are: 
# utilizing python programming language through Anaconda, Visual Studio Code, Python.org tutorials and w3schools tutorials
# packages such as pandas, seaborn, matplotlib and numpy by researching their respective documentation and this will be utilized alongside various other compositions regarding the same.
# These will be stored on a Jupyter notebook and submitted and hosted in a Github repository for reviewing.
# The primary graphical types that will be used bar charts, line charts, box plots, scatter plots, violin plots and histograms.

# KEY TERMS/TOOLS IN ASSIGNMENT:
# Jupyter - "a loose acronym meaning Julia, Python, and R" (Datacamp, 2019) - The base languages jupyter was created to include but it now includes various other languages, including Python.
# GitHub account previously created on GitHub.com for creation of repositories of code, assignment and lecture content input. GitHub is the worlds leading software development and sharing platform which brings together the worlds greatest community of developers (GitHub.com, 2019).
# Descriptive statistics - "are brief descriptive coefficients that summarize a given data set, which can be either a representation of the entire or a sample of a population" Investopedia (2019).
# Mean - average of all numbers.
# Median - is the middle value or average of two middle values of a sorted set of numbers.
# MACHINE LEARNING - allows "computers the ability to learn without being explicitly programmed" (Arthur Samuel). Allows processing of BIG DATA.
# DATA ANALYSIS - is the inspection and modelling of data to discover information and conclusions which may aid the process of decision making.
# DATA MINING - is the examination of existing databases in order to produce new information.
# MULTIVARIATE ANALYSIS: more than two forms of variables for analysis.
# BIVARIATE ANALYSIS: two variable for analysis.
# UNIVARIATE ANALYSIS: one varaible for analysis.
# STANDARD DEVIATION: the variance from the mean. It can be a low or high variance depending on the distribution of differences from the mean.
# Dependent Variable: factor that needs to understood or predicted.
# Independent Variables: the factors that may impact on your dependent variable.

# NumPy is "the fundamental package supported for presenting and computing data with high performance in Python" Phuong and Czygan (2015, p. 11).
# Features, (list adapted from Phuong and Czygan, 2015);
# Built into Python.
# Multidimensional arrays (ndarrays).
# Other objects such as masked arrays, vectorization matrices, and broadcasting functions.
# Computational operations on arrays of data including mathematical manipulation, statistics, sorting, selecting, random number generation, Fourier transforms, etc.
# Integration with C/C++ and Fortran Code.

# Some key NumPy related terms which are discussed in the assignment are defined briefly here as adapted from Marsland (2015) and from class content;
# i) Arrays - basic data structure that is used and are called as functions with values passed in as a list or set of lists. >>> np.array().
# ii) Linear algebra - NumPy includes standard linear functions within its package, e.g. >>> np.linalg.inv(a) = getting the inverse of a.
# iii) Plotting - use of the Matplotlib library, imported as: >>> import matplotlib as pl. Most important are >>> pl.plot and >>> pl.hist which plot function as graphs or histograms respectively.
# iv) Pseudorandom Number Generator - abbreviated to PRNG - uses seed information to produce an algorithm which for generating a sequence of numbers which in turn approximates sequences of random numbers. 
# v) Pseudorandomness - process for producing predictable outcomes if given information or statistical randomness without.
# vi) Mersenne Twister - is a pseudorandom number generator (PRNG) and is widely used in software packages.

# The following shows the list of all subset functions of NumPy's numpy.random routine quoted from SciPy.Org's reference manual webpage titled: Random sampling (numpy.random). 
# [*each function called as x in numpy.random.()]
# The depictions within the list are briefly detailed here:
# size = shape of distribution.
# low = minimum of distribution
# high =  maximum of distribution
# p = probability.
# x, a, d, = inputs of the distribution
# scale = scaled range of distribution
# length, mean, mode, median, sigma, etc., as expected.

# Some of the functions used in assignment are:
# randint(low[, high, size, dtype]) Return random integers from low (inclusive) to high (exclusive).
# random_integers(low[, high, size]) Random integers of type np.int between low and high, inclusive.
# sample([size]) Return random floats in the half-open interval [0.0, 1.0).
# choice(a[, size, replace, p]) Generates a random sample from a given 1-D array
# permutation(x) Randomly permute a sequence, or return a permuted range.
# sort(x) - sorts a random sequence from low to high.
# seed([seed]) Seed the generator.

# Seaborn is an amazing Python visualization library built on top of matplotlib and seaborn has a high-level interface as compared to the low level of Matplotlib (Singh, 2019).
# Reference List within Notebook: Programming for Data Analysis Assignment.ipynb

# Reference List:

# Python Software Foundation. Accessed online at: https://www.python.org/
# w3Schools.com Tutorials. Accessed online at: https://www.w3schools.com
# Python by Programiz Tutorials. Accessed online at: https://www.programiz.com/
# Pandas: Python Data Analysis Library. Accessed online at: https://pandas.pydata.org.
# NumPy. Accessed online at: http://www.numpy.org
# matplotlib (2019) Pyplot Tutorial. Accessed online at: https://matplotlib.org/3.1.1/tutorials/introductory/pyplot.html.
# Seaborn (2019) Official Seaborn Tutorial. Accessed online at: https://seaborn.pydata.org/tutorial.html
# Stack Overflow - Various queries for comparison and improving code output. Accessed online at: https://stackoverflow.com
# SciPy.org (2019) Random Sampling (numpy.random). Accessed online at: https://docs.scipy.org/doc/numpy-1.14.0/reference/routines.rand
# Tutorialspoint (2019) NumPy Tutorial. Accessed online at: https://www.tutorialspoint.com/numpy/index.htm.
# NumPy Community (2017) NumPy User Guide. Accessed online at: https://numpy.org/doc/_downloads/numpy-user-1.13.0.pdf
# Seaborn (2019) Visualizing statistical relationships. Accessed online at: https://seaborn.pydata.org/tutorial/relational.html
# Investopedia (2019) Descriptive Statistics. Accessed online at: https://www.investopedia.com/terms/d/descriptive_statistics.asp
# Doshi, S. (2019) Analyze the data through data visualization using Seaborn. Towards Data Science. Accessed online at: https://towardsdatascience.com/.analyze-the-data-through-data-visualization-using-seaborn-255e1cd3948e
# Pynative (2019) Python Random Number Generation tutorial. Accessed online at: https://pynative.com/python-random-module/
# Brownlee, J. (2018) How to Generate Random Numbers in Python. Machine Learning Mastery.
# Phuong, V. T. H and Cyzgan, M. (2015) Getting Started with Python Data Analysis. Accessed online at: https://subscription.packtpub.com/book/big_data_and_business_intelligence/9781785285110/backindex
# Singh, S. (2019) Become a Data Visualization Whiz with this Comprehensive Guide to Seaborn in Python. Analytics Vidhya. Accessed online at: https://www.analyticsvidhya.com/blog/2019/09/comprehensive-data-visualization-guide-seaborn-python/
# Wajiha (2019) Python Seaborn Tutorial | Data Visualization Using Seaborn. Accessed online at: https://www.codementor.io/wajihaurooj/python-seaborn-tutorial-data-visualization-using-seaborn-wpj9qydr2.
# Marsland, S. (2015) Machine Learning: An Algorithmic Perspective. Taylor and Francis Group.
# pandas (2019) pandas: powerful Python data analysis toolkit. Accessed online at: https://pandas.pydata.org/pandas-docs/stable/index.html
#  GeeksforGeeks (2019) Creating a Pandas DataFrame.Accessed online at: https://www.geeksforgeeks.org/creating-a-pandas-dataframe/
# Like Geeks (2019) Python NumPy Array Tutorial. Accessed online at: https://likegeeks.com/numpy-array-tutorial/
# Tanguy (2019) How Does Your Computer Generate Random Numbers? Accessed online  at: https://www.sicara.ai/blog/2019-01-28-how-computer-generate-random-numbers
# Cohen, O. (2019) The Definite Guide For Creating An Academic-Level Dataset With Industry Requirements And Constraints. Accessed online at: https://towardsdatascience.com/the-definite-guide-for-creating-an-academic-level-dataset-with-industry-requirements-and-6db446a26cb2
# Inferential Thinking (2018) Randomness. Accessed online at: https://www.inferentialthinking.com/chapters/09/Randomness.html
# BlackRain79 (2018) What is a Good Poker Winning Percentage? Accessed online at: https://www.blackrain79.com/2018/05/good-poker-winning-percentage.html.
# Sofen, J. (2018) WSOP Main Event Inside Data: Fields Growing, Women Underrepresented, California Dreamin’. Accessed online at: https://www.cardschat.com/news/wsop-main-event-fields-growing-women-underrepresented-california-dreams-66819
# Ruddock, S. (2017) The Reduced Numbers Of Young Players In Poker IS Probably A Good Thing. https://www.uspoker.com/blog/young-players-good-bad-poker/18237/
# Willems, K (2019) Pandas Tutorial: DataFrames in Python. Accessed online at: https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python
# Srinivasulu, R (2018) Different Ways to Create Numpy Arrays. Accessed online at: https://www.pluralsight.com/guides/different-ways-create-numpy-arrays
# pandas (2019) Styling. Accessed online at: https://pandas.pydata.org/pandas-docs/stable/user_guide/style.html
# For certain formulaic inputs the LaTeX tutorial on Math.ubc.ca was sampled and the link for such is: https://www.math.ubc.ca/~pwalls/math-python/jupyter/latex/.