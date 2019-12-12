# progdataanalysisproject
# Final Project for Programming Data Analysis Project

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
# vii) Gaussian distribution - also known as normal distribution is a common continuous probability distribution and is useful for determining random values as their distributions are unknown.

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

# Simple random data
# rand(d0, d1, ..., dn)	Random values in a given shape.
# randn(d0, d1, ..., dn) Return a sample (or samples) from the “standard normal” distribution.
# randint(low[, high, size, dtype]) Return random integers from low (inclusive) to high (exclusive).
# random_integers(low[, high, size]) Random integers of type np.int between low and high, inclusive.
# random_sample([size]) Return random floats in the half-open interval [0.0, 1.0).
# random([size]) Return random floats in the half-open interval [0.0, 1.0).
# ranf([size]) Return random floats in the half-open interval [0.0, 1.0).
# sample([size]) Return random floats in the half-open interval [0.0, 1.0).
# choice(a[, size, replace, p]) Generates a random sample from a given 1-D array
# bytes(length) Return random bytes.

# Permutations
# shuffle(x) Modify a sequence in-place by shuffling its contents.
# permutation(x) Randomly permute a sequence, or return a permuted range.

# Distributions
# beta(a, b[, size]) Draw samples from a Beta distribution.
# binomial(n, p[, size]) Draw samples from a binomial distribution.
# chisquare(df[, size]) Draw samples from a chi-square distribution.
# dirichlet(alpha[, size]) Draw samples from the Dirichlet distribution.
# exponential([scale, size]) Draw samples from an exponential distribution.
# f(dfnum, dfden[, size]) Draw samples from an F distribution.
# gamma(shape[, scale, size]) Draw samples from a Gamma distribution.
# geometric(p[, size]) Draw samples from the geometric distribution.
# gumbel([loc, scale, size]) Draw samples from a Gumbel distribution.
# hypergeometric(ngood, nbad, nsample[, size]) Draw samples from a Hypergeometric distribution.
# laplace([loc, scale, size]) Draw samples from the Laplace or double exponential distribution with specified location (or mean) and scale (decay).
# logistic([loc, scale, size]) Draw samples from a logistic distribution.
# lognormal([mean, sigma, size]) Draw samples from a log-normal distribution.
# logseries(p[, size]) Draw samples from a logarithmic series distribution.
# multinomial(n, pvals[, size])	Draw samples from a multinomial distribution.
# multivariate_normal(mean, cov[, size, ...) Draw random samples from a multivariate normal distribution.
# negative_binomial(n, p[, size]) Draw samples from a negative binomial distribution.
# noncentral_chisquare(df, nonc[, size]) Draw samples from a noncentral chi-square distribution.
# noncentral_f(dfnum, dfden, nonc[, size]) Draw samples from the noncentral F distribution.
# normal([loc, scale, size]) Draw random samples from a normal (Gaussian) distribution.
# pareto(a[, size]) Draw samples from a Pareto II or Lomax distribution with specified shape.
# poisson([lam, size]) Draw samples from a Poisson distribution.
# power(a[, size]) Draws samples in [0, 1] from a power distribution with positive exponent a - 1.
# rayleigh([scale, size]) Draw samples from a Rayleigh distribution.
# standard_cauchy([size]) Draw samples from a standard Cauchy distribution with mode = 0.
# standard_exponential([size]) Draw samples from the standard exponential distribution.
# standard_gamma(shape[, size]) Draw samples from a standard Gamma distribution.
# standard_normal([size]) Draw samples from a standard Normal distribution (mean=0, stdev=1).
# standard_t(df[, size]) Draw samples from a standard Student’s t distribution with df degrees of freedom.
# triangular(left, mode, right[, size]) Draw samples from the triangular distribution over the interval [left, right].
# uniform([low, high, size]) Draw samples from a uniform distribution.
# vonmises(mu, kappa[, size]) Draw samples from a von Mises distribution.
# wald(mean, scale[, size]) Draw samples from a Wald, or inverse Gaussian, distribution.
# weibull(a[, size]) Draw samples from a Weibull distribution.
# zipf(a[, size]) Draw samples from a Zipf distribution.

# Random generator
# RandomState Container for the Mersenne Twister pseudo-random number generator.
# seed([seed]) Seed the generator.
# get_state() Return a tuple representing the internal state of the generator.
# set_state(state) Set the internal state of the generator from a tuple.

# For certain formulaic inputs the LaTeX tutorial on Math.ubc.ca was sampled and the link for such is: https://www.math.ubc.ca/~pwalls/math-python/jupyter/latex/.
# pandas (2019) pandas: powerful Python data analysis toolkit. Accessed online at: https://pandas.pydata.org/pandas-docs/stable/index.html
#  GeeksforGeeks (2019) Creating a Pandas DataFrame.Accessed online at: https://www.geeksforgeeks.org/creating-a-pandas-dataframe/
# Like Geeks (2019) Python NumPy Array Tutorial. Accessed online at: https://likegeeks.com/numpy-array-tutorial/
# Tanguy (2019) How Does Your Computer Generate Random Numbers? Accessed online  at: https://www.sicara.ai/blog/2019-01-28-how-computer-generate-random-numbers
# Cohen, O. (2019) The Definite Guide For Creating An Academic-Level Dataset With Industry Requirements And Constraints. Accessed online at: https://towardsdatascience.com/the-definite-guide-for-creating-an-academic-level-dataset-with-industry-requirements-and-6db446a26cb2
# Inferential Thinking (2018) Randomness. Accessed online at: https://www.inferentialthinking.com/chapters/09/Randomness.html
