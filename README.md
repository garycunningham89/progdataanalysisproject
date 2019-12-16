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

# Pre research considerations for dataset simulation from Cohen (2019):
# Which data to sample.
# Which sampling distribution to follow and when?
# Which sampling algorithm to use.
# How many to sample?

# Within this poker tournament data set the attributes are be subdivided into:
# Categorical data:
# - gender
# - level
# Numerical data:
# - age
# - gwp
# - totalpts
# - chips
# - count
# - handswon%

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

# Packages used:
# * Pandas - "is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language" (pandas Documentation, 2019).
# * Matplotlib - "tries to make easy things easy and hard things possible. You can generate plots, histograms, power spectra, bar charts, errorcharts, scatterplots, etc., with just a few lines of code" (Matplotlib Documentation, 2019). 
# * Seaborn - a higher level data visualization package than matlplotlib which is built on top of it and Waskom has described it as "If Matplotlib “tries to make easy things easy and hard things possible”, seaborn tries to make a well-defined set of hard things easy too.” (Singh, 2019). Seaborn is an amazing Python visualization library built on top of matplotlib and seaborn has a high-level interface as compared to the low level of Matplotlib (Singh, 2019).

# Primary Issues:
# * Formulating a real world phenomenon which could be simulated accurately and that could have analysis performed on it with multiple variables.
# * Generating accurate data measurements for the data set, using a lot of trial and error.
# * Trying to include too much in a simulated data set.
# * Choosing the correct generation and analysis techniques.
# * Time keeping in line with other assignments and other aspects as part of entire online course.

# Reference List within Notebook: Programming for Data Analysis Assignment.ipynb