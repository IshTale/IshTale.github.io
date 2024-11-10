## Researcher - NBA Prediction Model
**Project description:** Conducted a comprehensive analysis of NBA player performance data, with mentorship from Maria Konte, a research scientist at Georgia Tech. Focused on the Player Efficiency Rating (PER) metric and developed a predictive model using linear regression to forecast players' future performance. The model aims to assist in player selection and draft decisions by determining relationships between key player statistics and PER.
**GitHub Repository:** [NBA Prediction Model](https://github.com/IshTale/reasearch)
### 1. Hypotheses about the causes of observed phenomena
Hypothesized that certain player statistics (e.g., scoring, rebounds, assists) correlate strongly with PER, and tracking these metrics can provide insights into a player’s career trajectory. Formulated a linear regression model to test these relationships over multiple seasons.
```python
# Linear regression model setup for predicting future PER
from sklearn.linear_model import LinearRegression
model = LinearRegression()
model.fit(player_stats, PER)
predicted_PER = model.predict(future_stats)
```
### 2. Assess assumptions on which statistical inference will be based
Assessed the consistency and reliability of historical data by cleaning and preprocessing it. This included handling missing values and outliers to ensure the integrity of the regression model’s results.
```python
# Data preprocessing example
player_stats = player_stats.fillna(player_stats.mean())
player_stats = player_stats[(player_stats.zscore() < 3)]  # Remove outliers
```
### 3. Appropriate statistical tools and techniques
Utilized Python’s Pandas, Numpy, Scipy, and machine learning libraries to analyze and visualize data patterns. Implemented Seaborn and Matplotlib for data visualization, which helped in understanding trends and validating the linear regression assumptions.
<img src="images/nba_prediction_visualization.jpg?raw=true"/>
### 4. A basis for further data collection through surveys or experiments
Recommended continued collection of NBA player statistics as new seasons unfold to enhance the model’s accuracy. Future data collection can refine the regression model, allowing it to adapt to evolving gameplay and player dynamics.
For more details, see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
