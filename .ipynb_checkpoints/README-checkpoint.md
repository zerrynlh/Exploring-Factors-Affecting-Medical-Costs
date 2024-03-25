# Data Analysis of Medical Charges
Analyzing factors that affect the amount an individual spends on medical care.

This project analyzes factors such as age, sex, body mass index (BMI), smoker status and region. The dataset was located on [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance).

Preprocessing of the data involved removing outliers from the medical charges columns using the IQR method. 
Individuals in the data are listed as belonging to one of four U.S. regions: Northeast, Northwest, Southeast, and Southwest.

Correlation analysis determined that the numerical variable with the strongest relationship to medical costs was age.

Further analysis found that the Northeast, the region with the highest smoker count from the sample data, had the highest mean and median medical costs. The Southern regions had the lowest mean and median costs.

The average medical cost for smokers was $13,658.53 higher than costs for non-smokers.

The data did not indicate a strong relationship between BMI and age with a correlation coefficient of 0.12.

A Welch Two Sample t-test was conducted to compare the mean medical costs between females and males.

- Null Hypothesis (H0): The mean medical costs for males and females are equal. H0: μ_male = μ_female
- Alternative Hypothesis (Ha): The mean medical costs for males and females are not equal. Ha: μ_male ≠ μ_female

With a p-value of 0.3998, the null hypothesis failed to be rejected.