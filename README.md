# README

This repository contains R code for conducting statistical analysis on two different datasets: `pima` and `women_data`.

## Analysis on Dataset: pima

### 1. Descriptive Statistics

Summary statistics are computed for variables `pregnant`, `glucose`, `diastolic`, `triceps`, `insulin`, `bmi`, `diabetes`, and `age`.

### 2. Correlation Tests

A correlation plot is generated for variables `age`, `bmi`, `glucose`, `diastolic`, `insulin`, and `test`. The plot displays both the correlation coefficients and the associated p-values.

### 3. Sort Test Variable for Further Analysis

The data is subset based on the binary `test` variable (0 or 1) indicating diabetes status.

### 4. Check for Normality

Q-Q plots are generated for `bmi`, `glucose`, and `age` in both test positive and test negative groups.

### 5. Check for Homogeneity

Levene's tests are conducted to check the homogeneity of variances for `age`, `bmi`, and `glucose`.

### 6. Testing for Significance

Welch's t-tests are performed for `age`, `bmi`, and `glucose` to test for significant differences between test positive and test negative groups. Effect sizes (Cohen's d) are also computed.

## Analysis on Dataset: women_data

### 1. Descriptive Statistics

Summary statistics are computed for variables `AGE`, `HbA1c`, `Chol`, `BMI`, and `CLASS`.

### 2. Correlation Tests

A correlation plot is generated for variables `AGE`, `HbA1c`, `Chol`, `BMI`, and `CLASS`. The `CLASS` variable is converted to numeric values (0, 1, 2) for plotting.

### 3. Sort Test Variable for Further Analysis

The data is subset based on the `CLASS` variable representing diabetic, prediabetic, and negative groups.

### 4. Check for Normality

Q-Q plots are generated for `AGE`, `BMI`, and `HbA1c` in diabetic, prediabetic, and negative groups.

### 5. Check for Homogeneity

Levene's tests are conducted to check the homogeneity of variances for `AGE`, `BMI`, and `HbA1c`.

### 6. Testing for Significance

Welch's ANOVA-like tests are performed for `AGE`, `BMI`, and `HbA1c` to test for significant differences between diabetic, prediabetic, and negative groups.
