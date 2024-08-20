Data Collection, Cleanup, and Exploration
Data Source and Selection
I utilized the satellite Hipparcos' star catalog dataset for the analysis, chosen for its accuracy and real data. The data spans from 1989 to 1993, collected via satellite, which provides many different measurements and other types of data for over 50 thousand different stars.
Data Collection Process
* Source: Hipparcos Satellite dataset
* Coverage: Star Sprectral Type Predictions
* Time Period: 1989 to 1993
* Format: Initially in CSV and NetCDF formats
Data Exploration and Cleanup
1. Exploration:
    * Initial Review: Analyzed the dataset's structure and content to understand its scope and quality.
    * Descriptive Statistics: Calculated summary statistics to grasp the data's distribution and central tendencies.
    * Visualization: Created initial plots to visualize variables to check which were fit to use based on distribution. Also created plots   to check for correlations between variables.
2. Cleanup:
    * Handling Missing Values: Imputed or interpolated missing data points based on surrounding values or using statistical methods.
    * Correcting Anomalies: Identified and corrected outliers or inconsistencies that could skew results.
    * Data Formatting: Omitted star types that didn't have a high enough population and generalized star types to their letter.
Approach to Achieving Project Goals
Analytical Approach
1. Exploratory Data Analysis (EDA): Conducted to understand data characteristics and identify initial trends.
2. Trend Analysis: Used statistical methods to quantify correlations, including correlation plots and classification.
3. Visualization: Created various plots, such as correlation plots and matrixes, to illustrate correlation between variables, and prediction success rates.
4. Predictions: Applied predictive modeling techniques (e.g., RandomForests) to get the algorithm itself to predict the data types given certain variables. I did this through supervised learning and classification. 
* Data Gaps: Some star types had sparse and complex data, which complicated analysis, so I generalized spectral types down to their letter, and omitted spectral types which had too small of a population size.
* Model Variability: Forecasting models showed variability due to the generalization and omittion done on the spectral types. 
Results and Conclusions
Key Findings
* Trend Identification: Found that the visual magnitude and the BT magnitude both had normal distributions and correlated positivly.
* Found that the spectral types with the most data had the highest prediction scores, and the spectral types with the lowest had near the lowest scores. 
Visualizations:
* Distribution Plots: Checking for normal distribution between variables.
* Correlation Plots: Checking for correlations between variables.
Issues and Resolutions:
* Unresolved Data Anomalies: Some anomalies could not be fully resolved, leading to potential minor inaccuracies in trend analysis. I documented these issues and noted their potential impact on the results.
Next Steps
Potential Next Steps:
1. Extended Research: Incorporate recent and un-generalized date to refine forecasts and extend the analysis.
2. Advanced Modeling: Develop and test more sophisticated models, including deep learning and AI, to improve prediction accuracy and account for complex interactions in the data.
