# Apple App Store Analysis 
## Project Overview

This project analyzes Apple App Store data using Python and statistical techniques to identify patterns in app ratings, popularity, pricing, and genres.
The analysis combines data cleaning, exploratory data analysis, statistical analysis, correlation, regression, outlier analysis,Business Findings and probability distributions.
## Objectives

- Analyze app ratings and pricing patterns
- Compare free and paid applications
- Identify genres with higher average ratings
- Investigate factors associated with app popularity
- Analyze relationships between app features and user ratings
- Perform statistical hypothesis testing
- Apply regression analysis
- Analyze rating success using binomial distribution

## Dataset

The dataset contains information about Apple App Store applications, including:

- App name
- Price
- User ratings
- Rating counts
- Genre
- Number of supported devices
- iPad screenshot URLs
- Number of supported languages
- Version information

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Jupyter Notebook

## Analysis Performed

### Data Cleaning
- Checked for missing values
- Checked for duplicate records
- Verified data types
- Prepared variables for analysis

### Exploratory Data Analysis
- Descriptive statistics
- Histograms
- Boxplots
- Bar charts
- Scatter plots
- Correlation heatmap

### Statistical Analysis
- Correlation analysis
- Independent samples t-test
- Simple linear regression
- Outlier analysis
- Binomial distribution

## Key Findings

- 43.84% of apps achieved a rating of 4 or above.
- Most apps are free or low-priced.
- Productivity and Music had the highest average ratings among the analyzed top genres.
- App popularity is not strongly explained by any single factor.
- Supported devices had very little predictive power for user ratings.
- User rating and current-version rating showed a strong positive relationship.
- Apps with more iPad screenshots tended to have higher average ratings.

## Conclusion

The analysis demonstrates how Python and statistical techniques can be used to extract meaningful insights from real-world app data. The results suggest that app success and popularity depend on multiple factors rather than a single feature.

## Project Structure

```text
Apple-AppStore-Analysis/
│
├── data/
├── notebook/
├── report/
├── images/
├── README.md
└── requirements.txt
