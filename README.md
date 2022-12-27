# Salary Analysis using ANOVA and Principal Component Analysis (PCA) on College Admissions Data

## Problem 1A:

Salary is hypothesized to depend on educational qualification and occupation.
To understand the dependency, the salaries of 40 individuals [SalaryData.csv] are collected and each person’s educational qualification and occupation are noted.
Educational qualification is at three levels, High school graduate, Bachelor, and Doctorate.
Occupation is at four levels, Administrative and clerical, Sales, Professional or specialty, and Executive or managerial.
A different number of observations are in each level of education – occupation combination.

[Assume that the data follows a normal distribution. In reality, the normality assumption may not always hold if the sample size is small.]

1. State the null and the alternate hypothesis for conducting one-way ANOVA for both Education and Occupation individually.
2. Perform a one-way ANOVA on Salary with respect to Education. State whether the null hypothesis is accepted or rejected based on the ANOVA results.
3. Perform a one-way ANOVA on Salary with respect to Occupation. State whether the null hypothesis is accepted or rejected based on the ANOVA results.
4. If the null hypothesis is rejected in either (2) or in (3), find out which class means are significantly different. Interpret the result. (Non-Graded)

## Problem 1B:

1. What is the interaction between two treatments? Analyze the effects of one variable on the other (Education and Occupation) with the help of an interaction plot.[hint: use the ‘pointplot’ function from the ‘seaborn’ function]
2. Perform a two-way ANOVA based on Salary with respect to both Education and Occupation (along with their interaction Education*Occupation). State the null and alternative hypotheses and state your results. How will you interpret this result?
3. Explain the business implications of performing ANOVA for this particular case study.

## Problem 2:

The dataset Education - Post 12th Standard.csv contains information on various colleges.
You are expected to do a Principal Component Analysis for this case study according to the instructions given.
The data dictionary of the 'Education - Post 12th Standard.csv' can be found in the following file: Data Dictionary.xlsx.

1. Perform Exploratory Data Analysis [both univariate and multivariate analysis to be performed].
What insight do you draw from the EDA?
2. Is scaling necessary for PCA in this case? Give justification and perform scaling.
3. Comment on the comparison between the covariance and the correlation matrices from this data [on scaled data].
4. Check the dataset for outliers before and after scaling. What insight do you derive here? 
5. Extract the eigenvalues and eigenvectors.[Using Sklearn PCA Print Both]
6. Perform PCA and export the data of the Principal Component (eigenvectors) into a data frame with the original features
7. Write down the explicit form of the first PC (in terms of the eigenvectors. Use values with two places of decimals only).
8. Consider the cumulative values of the eigenvalues.
How does it help you to decide on the optimum number of principal components?
What do the eigenvectors indicate?
9. Explain the business implication of using the Principal Component Analysis for this case study.
How may PCs help in the further analysis? 
