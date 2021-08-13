# Finding_outlier

What is an outlier?
An outlier is a data point in a data set that is distant from all other observations. A data point that lies outside the overall distribution of the dataset.

What are the criteria to identify an outlier?
Data point that falls outside of 1.5 times of an interquartile range above the 3rd quartile and below the 1st quartile
Data point that falls outside of 3 standard deviations. we can use a z score and if the z score falls outside of 2 standard deviation

What is the reason for an outlier to exists in a dataset?
Variability in the data
An experimental measurement error

What are the impacts of having outliers in a dataset?
It causes various problems during our statistical analysis
It may cause a significant impact on the mean and the standard deviation

Various ways of finding the outlier.
Using scatter plots
Box plot
using z score
using the IQR interquantile range

Detecting outlier using Z score
Using Z score
Formula for Z score = (Observation — Mean)/Standard Deviation

z = (X — μ) / σ

InterQuantile Range
75%- 25% values in a dataset

Steps
1. Arrange the data in increasing order
2. Calculate first(q1) and third quartile(q3)
3. Find interquartile range (q3-q1)
4.Find lower bound q1*1.5
5.Find upper bound q3*1.5
Anything that lies outside of lower and upper bound is an outlier
