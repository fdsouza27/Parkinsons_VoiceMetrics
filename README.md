# Deciphering Parkinson's: Vocal Biomarkers and Demographic Insights

## Overview
To investigate the relationship between vocal biomarkers and Parkinson's disease progression, examining how these metrics, along with demographic factors (age and sex), can predict disease severity. The goal is to enhance early diagnosis and monitoring of Parkinson’s disease through non-invasive vocal analysis.

## Objectives
- To explore the correlation between vocal metrics and Parkinson's disease severity.
- To assess the impact of age and sex on these vocal metrics.
- To determine the predictive capability of vocal features for disease severity, measured by UPDRS scores.

## Methodology
The project was conducted in four main stages:
1. **Data Collection**: Acquired a structured dataset from Kaggle, including key variables such as age, sex, and vocal metrics (e.g., Jitter, Shimmer, NHR).
2. **Data Cleaning**: Verified the integrity of the dataset and confirmed the absence of missing values.
3. **Exploratory Data Analysis**: Used boxplots and histograms to examine the distribution and normality of the data.
4. **Statistical Analysis**:
   - **Spearman’s Correlation** was used to analyze the relationship between age and vocal metrics.
   - **Mann-Whitney U Test** compared the mean values of vocal metrics between male and female participants.
   - **Multiple Linear Regression** assessed the predictive ability of age, sex, and vocal metrics for Parkinson’s severity.

## Key Findings
- A weak to moderately positive correlation was found between age and vocal metrics.
- Statistically significant differences in certain vocal metrics were observed between male and female participants.
- The regression model indicated that while age and some vocal metrics contribute to predicting UPDRS scores, the overall model explains a modest portion of the variability.

## Limitations
The presence of outliers, while relevant for severe cases, may have impacted the analysis results.

## References
Bowen et al. (2014), Mayo Clinic Staff (2023), Vandana et al. (2021)
