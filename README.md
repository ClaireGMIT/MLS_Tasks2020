# MLS_Tasks2020
Repository for the Machine Learning and Statistics 2020 Module

This repository is the location for the Jupyter Notebook containing the answers to the tasks assigned for the Machine Learning and Statistics 2020 module for GMIT student Claire Nolan G00376464.

The notebook contains the question posed for each task followed by an answer describing the code used to get the answer, any references used and an explanation as to why the particular code was chosen.

**Question 1: Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on any module from the standard library1 or otherwise.**  
This question was answered using the Babylonian method for determining square root which is an iteration method. The output was only to 17 decimal places. Another of methods were performed to round the data to 100 decimal places. In one case the otput was to 100 decimal places but at teh 51st position only zeroes were returned. Numerous attempts did not rectify this issue. Further research founf a method which provided the answer to square root 2 to 100 decimal places.

**Question 2: The Chi-squared test for independence is a statisticalhypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example, stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value.**
This question was answered by discussing what is a Chi-squared statistic. Two methods for calculating chi-squared are discussed and both reults output a chi-squared value of 24.6 and the corresponding p-value is less than 0.05. 


**Question 3: The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) . However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x) . Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample.**
The difference between STDEV.P and STDEV.S is discussed and two different algorithms for each method is demsonstrated. This is also compared to the same result from MS Excel.


**Question 4 (original): Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set online.**
The work I did on K-means clustering is shown as I wanted to show the work I had already done for this question.
**Question 4 (updated): Use scikit-learn to apply k Nearest Neighbours clustering to Fisher’s famous Iris data set.**
An explanation on the KNN machine learning method is discussed. Two methods for performing KNN using the Iris dataset are discussed and demonstrated. The results are also discussed. The advantages and disadvantages of using KNN are also discussed.




**Question 4**
