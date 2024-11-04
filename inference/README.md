# Chapter Topics Overview

### Chapter 1

- Calculate relative risk
- Odds of success for both rows
- Calculate odds ratio
- Verify $\pi_i = \frac{\Omega_i}{1 + \Omega_i}$ for $i = 1, 2$
- Association between groups based on $\theta$
- Verify odds ratio = $relative risk$ $\times \left( 1 - \pi_2 \right)$

### Chapter 2

- Create a Contingency table using the “HairEyeColor” dataset in R
- Distribution of hair, eye color, and sex in students
- Convert dataset to a data frame and construct contingency table for hair and eye color
- Manually verify that sum of row marginals = sum of column marginals = n
- Verify that $p_{1+} + p_{2+} = p_{+1} + p_{+2} = 1$
- Create a contingency table for Employee status vs Sex
- Calculate expected frequency for each column
- Calculate $\sum \frac{(f_i - e_i)^2}{e_i}$

### Chapter 3

- Calculate confidence interval for odds ratio, $\theta$
- Calculate confidence interval for difference of proportion, $\pi_1 - \pi_2$
- Calculate confidence interval for relative risk, r
- Comment on association between gender and employability based on confidence intervals
- Compute Chi-square statistic, $X^2$
- Compute Wilk's statistic, $G^2$
- Compare statistics with Chi-square cut-off value and comment on testing $H_0: \pi_{ij} = \pi_{i+} \pi_{j+}$
- Find number of concordant pairs for Job satisfaction vs income level data using a loop
- Understand and compute number of discordant pairs
- Calculate p-value in Fisher's tea taster experiment for hypothesis testing of independence

### Chapter 4

- Load Horseshoe crab data and apply Poisson link function to estimate expected number of satellites
- Compare original satellite values with estimated values from Poisson model
- Plot original vs estimated satellite values for Poisson model
- Calculate sum of squared difference for Poisson model estimates
- Run linear regression of satellite on "color", "spine", "width", and "weight"
- Compare original satellite values with estimated values from both Poisson and linear regression models
- Plot original vs estimated (Poisson and linear regression) satellite values
- Calculate sum of squared difference for both Poisson and linear regression estimates
- Produce table of horseshoe crab data based on grouped width values
- Run Poisson GLM with log link, using offset as “t” and “New width values” as explanatory variable
- Interpret parameter values from model summary
- Determine 95% confidence interval for beta
- Find expected satellites of each group in grouped table
- Calculate Chi-square statistic and p-value
- Calculate Pearson residual

### Chapter 5

- Predict probabilities of heart disease for different levels of snoring using a logistic model
- Manually write likelihood function for logistic model and optimize it with `optim` function
- Find value of beta that maximizes likelihood for given alpha value of -3.86625
- Plot likelihood and identify maximizing beta value
- Predict probabilities of heart disease for different levels of snoring using a logistic model
- Manually write likelihood function for logistic model and optimize it with `optim` function
- For alpha = -3.86625, find the value of beta that maximizes the likelihood and plot likelihood
- For beta = 0.39734, find the value of alpha that maximizes the likelihood and plot likelihood
