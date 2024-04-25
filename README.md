

# World Happiness Index Analysis

## Overview
This report presents a detailed analysis of the World Happiness Index to explore the factors contributing to global happiness levels. Conducted by Deepak Vishwakarma (Student ID: 23035559), this study utilizes advanced statistical techniques and data visualization to understand and present the dynamics of happiness across various countries.

## Data Source
The analysis is based on the World Happiness Index dataset, which includes several socio-economic factors from countries worldwide. Key features in the dataset are:
- GDP per Capita
- Social Support
- Healthy Life Expectancy at Birth
- Freedom to Make Life Choices
- Generosity
- Perceptions of Corruption

Each entry represents a country's annual data, encompassing happiness scores and associated socio-economic attributes.

## Key Components of the Analysis
### 1. **Statistics and Graphical Analysis**
   - Computation of average happiness scores and their variability.
   - Analysis of economic indicators and social factors.
   - Distribution analysis of corruption perceptions and affective states.

### 2. **Visualization Techniques Employed**
   - **Categorical Bar Graph** (Pie Chart): Showcases the ladder score distribution among the top five countries.
   - **Correlation Heat Map**: Illustrates the relationships between different socio-economic factors and happiness scores.
   - **Regression Plot**: Demonstrates the relationship between Healthy Life Expectancy and the Life Ladder score.
   - **Elbow Graph for Clustering**: Helps determine the optimal number of clusters.
   - **Cluster Scatter Plot**: Visualizes the clustering of countries based on key features.

### 3. **Modeling and Clustering**
   - **Linear Regression Model**: Analyzes the impact of Healthy Life Expectancy on happiness.
   - **K-Means Clustering**: Identifies patterns and groups in the data based on socio-economic indicators.

## Results
- Strong correlations were found between GDP per capita, Healthy Life Expectancy, and happiness scores.
- The regression model and clustering analysis provided deeper insights into the predictive power of socio-economic factors on happiness.
- Evaluation metrics such as MAE and RMSE were used to assess the model's accuracy.

## Conclusions
The analysis reaffirmed the significant role of economic prosperity, social support, and health in contributing to happiness, while also highlighting the nuanced impact of corruption and freedom on societal well-being.


## Dependencies
- Python 3.8+
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Acknowledgements
This report is part of an academic project under the guidance of Prof William Cooper. Gratitude is extended to all those who provided data, insights, and peer reviews.
