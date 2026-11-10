# Economic preferences across countries

Team project (three students) for the course Applied Data Analysis and Machine Learning, M.Sc. International Economic Policy, University of Würzburg.

The notebook works with the individual-level file of the [Global Preferences Survey](https://gps.iza.org/): about 80,000 respondents in 76 countries, with measures of patience, risk taking, positive and negative reciprocity, altruism and trust.

## What the notebook does

1. **Data handling.** Fixes data types (dates, age), measures missing values and imputes them.
2. **Visualisation.** Correlation heatmap, regional comparisons, distributions by demographic group and an interactive country map.
3. **Supervised learning.** Predicts a respondent's country from preferences and demographics; compares several classifiers. Fills gaps in the preference measures with Random Forest regressors.
4. **Unsupervised learning.** Clusters individuals and countries with K-Means, chooses the number of clusters with the elbow method and plots the clusters with PCA.

## Data

The survey data are not included. They can be requested from the Global Preferences Survey website (Falk et al., 2018, *Quarterly Journal of Economics*). Save the individual-level file as `individual_new.csv` next to the notebook.

## Requirements

Python 3.11 with pandas, numpy, scikit-learn, matplotlib, seaborn, folium and geopandas.
