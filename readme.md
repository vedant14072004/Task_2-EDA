# Task 2: Exploratory Data Analysis (EDA)

## Objective
Understand the Titanic dataset using summary statistics and visualizations.

## Dataset
Titanic Dataset (891 rows, 12 columns) from Kaggle.

## Steps Performed
1. **Summary statistics:** mean, median, standard deviation, quartiles, skewness and missing values.
2. **Histograms and boxplots:** for Age, Fare, SibSp and Parch, plus count plots for Survived, Pclass, Sex and Embarked.
3. **Feature relationships:** correlation heatmap and pairplot.
4. **Patterns and anomalies:** survival by Sex, Pclass and Embarked, age distribution by survival, fare by class, missing-value map, and an interactive Plotly chart.
5. **Key insights:** written conclusions from the visuals.

## Key Insights
- Women survived at about 74% vs about 19% for men.
- 1st class survived more (about 63%) than 3rd class (about 24%).
- Fare is heavily right-skewed (skewness about 4.8) with 15 zero values.
- Age has 177 missing values and Cabin has 687.
- Pclass and Fare have a moderate negative correlation (-0.55).

## Tools Used
Python, Pandas, Matplotlib, Seaborn, Plotly

## Files
- `EDA.ipynb`: notebook with all steps
- `Titanic-Dataset.csv`: dataset
- `age_survival_plotly.html`: interactive Plotly chart
- `Screenshots/`: key charts