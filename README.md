# Titanic Dataset – Exploratory Data Analysis (EDA)

This project explores the Titanic dataset to uncover patterns and insights into passenger survival using visual and statistical analysis. It aims to identify key features that influenced survival and prepare the dataset for future modeling.

## Objective
Perform a detailed Exploratory Data Analysis (EDA) on the Titanic dataset to understand the data distribution, feature relationships, and survival factors using Python-based tools.

## Files Included

- `Titanic_EDA.ipynb` – Jupyter Notebook containing the full EDA workflow
- `Titanic_EDA.pdf` – Exported PDF version of the notebook (for easy sharing)
- `train.csv` – Original Titanic dataset from Kaggle

## Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

- Initial data checks: `.info()`, `.describe()`, null value inspection
- Univariate analysis: distribution of `Age`, `Fare`, and categorical features
- Bivariate analysis: survival by `Sex`, `Pclass`, `Age`, and family features
- Visualization tools: histograms, boxplots, countplots, heatmaps
- Statistical checks: skewness of numeric features
- Correlation matrix to detect multicollinearity
- Summary of insights presented in Markdown at the end of the notebook

## Key Insights

- **Gender and Class Matter**: Female passengers and 1st class passengers had much higher survival rates.
- **Age Plays a Role**: Younger passengers, especially children, were more likely to survive.
- **Fare Distribution**: Heavily right-skewed; higher fares often correlated with higher survival (likely due to class).
- **Pclass is Crucial**: Survival rate was highest in 1st class and lowest in 3rd class.
- **No Major Multicollinearity**: Features were generally not strongly correlated, which is helpful for modeling.

## Dataset Source

[Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)

## Author Notes

This analysis is part of a learning task to practice real-world EDA techniques. It lays the groundwork for predictive modeling and highlights how visual insights can inform data-driven decisions.

