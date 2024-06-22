
Fish Length Analysis Using Bootstrap Methods

Overview
This GitHub repository contains code and analysis for a research project focused on analyzing fish length data using bootstrap methods. The project aims to estimate population parameters such as the mean and standard deviation of fish lengths, assess bias in these estimates, construct confidence intervals, and visualize the distribution of sample means.

Dataset
The dataset used in this project, named "Salmon_Sample_6_24.csv," includes measurements of fish lengths in centimeters. The initial exploration of the dataset revealed it consists solely of the "Fish_Length_cm" variable.

Files
README.md: Overview of the project, its objectives, and structure.
fish_length_analysis.R: R script containing the entire analysis process from data loading to visualization using ggplot2.
Salmon_Sample_6_24.csv: CSV file containing the raw data on fish lengths.
Analysis Steps
Descriptive Statistics: Calculated the mean, standard deviation, and variance of fish lengths to summarize the dataset.
Bootstrap Sampling: Used bootstrap resampling (500 samples) to estimate the sampling distribution of the mean and standard deviation, and assessed bias in these estimates.
Confidence Intervals: Constructed bootstrap-based confidence intervals (5% and 12%) for the mean fish length using 25,000 bootstrap samples.
Visualization: Created a histogram of bootstrap sample means to visualize the distribution's shape and variability, confirming the normality around the estimated population mean.
Statistical Concepts
Mean and Standard Deviation: Basic measures of central tendency and dispersion.
Variance: Measure of the spread of data points around the mean.
Bootstrap Sampling: Resampling technique used to estimate sampling distributions and calculate confidence intervals without assuming specific population distributions.
Bias: Discrepancy between estimated and true population parameters.
Confidence Intervals: Range of values within which the true population parameter is estimated to lie with a certain level of confidence.
Conclusion
This project showcases the application of statistical methods in analyzing fish length data, emphasizing the use of bootstrap sampling to derive robust estimates and insights into population parameters. The findings underscore the variability inherent in sampling processes and provide a foundation for further research in fisheries science and related fields.
