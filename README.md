# Movies_Correlation_Project
 Python Data Analysis Project: Exploring Movie Industry Trends 🎬

📊 Objective: Analyzing the correlation between various movie features using Python, Pandas, Seaborn, and Matplotlib.

📂 Dataset: Utilized a movies dataset ('movies.csv').

Key Steps:

Data Exploration:

Imported Pandas, NumPy, Seaborn, and Matplotlib.
Explored dataset using head(), tail(), describe(), and info().
Data Cleaning:

Checked for NaN values in each column.
Adjusted data types for 'budget,' 'gross,' 'score,' 'votes,' and 'runtime.'
Removed rows with missing values.
Data Analysis:

Explored and visualized the correlation between 'budget' and 'gross' through scatter and regression plots.
Utilized a heatmap to analyze the correlation matrix of all features.
Feature Normalization:

Converted categorical features to numerical for correlation analysis.
Visualized the normalized correlation matrix.
Correlation Insights:

Explored correlation pairs and identified high correlations.
Noteworthy correlations found:
71% correlation between 'budget' and 'gross.'
63% correlation between 'votes' and 'gross.'

Conclusion:

Identified significant correlation between movie budget and gross earnings.
Explored the relationship between votes and gross earnings.
Concluded that a higher budget tends to lead to higher gross earnings, and movies with higher earnings generally receive better votes.
