# USCollegeDataAnalysisR
USCollegeDataAnalysisR is a comprehensive analysis of college and university data in the United States using R. 


### Description

This repository is designed to perform a thorough preliminary analysis of data from colleges and universities across the United States using R. The analysis includes understanding features, data preparation, identifying and handling outliers, examining distribution types, and performing regression analysis with diagnostics and model evaluation.

### Features

- **Data Understanding**: The meaning of features in the dataset is comprehended.
- **Feature Selection**: 7-10 important features are selected based on relevance and correlations.
- **Data Type Identification**: Feature types (quantitative, ordinal, categorical) are identified and handled accordingly.
- **Data Preparation**: Data is loaded and preprocessed, missing values are handled, and correct encoding of ordinal variables is ensured.
- **Visualization**: Matrix plots (pairs plots) are created to identify outliers, heterogeneity, and dependency types.
- **Transformation**: Skewed distributions are log-transformed and pairs plots are updated for better linearity.
- **Outlier Handling**: Outliers are identified, explained, and removed if necessary.
- **Group Analysis**: Heterogeneity within groups is examined and descriptive statistics are analyzed.
- **Distribution Analysis**: Distribution types are analyzed using normal probability plots, Lilliefors, AD, chi-square, and Shapiro-Wilk tests.
- **Group Comparison**: Boxplots are used for initial comparison, followed by t-tests and non-parametric tests (Mann-Whitney) for more detailed analysis.
- **Regression Analysis**: Linear regression is performed, results are interpreted, and multicollinearity and redundancy are checked.
- **Residual Analysis**: Normality of residuals is assessed and outliers are identified using Cook's distance and Mahalanobis distance.
- **Dependency Analysis**: Linear dependencies are analyzed with Pearson correlation, and rank correlations with Spearman's coefficient.
- **Partial Correlations**: Partial correlations are used to account for hidden factors affecting multiple features.

