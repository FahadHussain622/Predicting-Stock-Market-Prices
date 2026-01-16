# Fundamentals of Big Data Analysis (FDBA) – Stock Market Price Prediction

**Project:** Predicting Stock Market Prices of USA Stocks (Daily Dataset)  

---

## Overview
This project focuses on predicting stock market prices of USA stocks using a combination of **time series analysis, machine learning models, and sentiment analysis**. The dataset includes daily stock prices and financial indicators, processed and analyzed using Apache Spark to handle large-scale data efficiently. The project applies preprocessing, feature engineering, predictive modeling, and visualization techniques to extract insights and build robust predictive models.

---

## Data Collection
A comprehensive dataset containing stock market data, including various financial indicators and stock prices, was collected. The dataset was loaded into a Spark DataFrame to facilitate large-scale processing and analysis.

---

## Preprocessing Steps
To prepare the data for modeling, the following preprocessing steps were applied:

- **Removing Outliers:** Outliers were identified and removed to prevent skewed results and improve model accuracy.  
- **Time Series Analysis:** Trends in the 'Date' column were analyzed to capture seasonal and temporal patterns.  
- **Correlation Analysis:** Relationships between features were examined using correlation matrices and visualizations to select the most relevant predictors.

---

## Analysis Techniques

### Time Series Analysis
Time series analysis was performed to identify long-term trends, seasonal patterns, and periods of high volatility in stock prices. Visualizations were created to better understand market behavior over time.

### Feature Engineering & Model Training
- **Feature Engineering:** Raw data was transformed into meaningful features to improve model performance.  
- **Models Used:** Linear Regression, Decision Trees, and Ensemble methods suitable for time series data and large datasets.  
- **Hyperparameter Tuning:** Systematic tuning using cross-validation and grid search to optimize predictive performance.

### Sentiment Analysis
- Performed on the 'Ticker' column using the **SentimentIntensityAnalyzer (SIA)**.  
- Generated sentiment scores for text data to gauge market sentiment.  
- Insights from sentiment analysis were used as additional features to improve predictions.

### Data Visualization
- **Graphs:** Trend plots of mean stock prices over time.  
- **Correlation Matrices:** Highlighting relationships between features.  
- **Box Plots:** Displaying sentiment score distributions.  
- **Word Clouds:** Showing most frequent terms in sentiment data.

---

## Findings & Interpretation
- **Stock Market Trends:** Time series analysis revealed significant trends, seasonal patterns, and periods of high volatility.  
- **Model Performance:** Feature engineering and model training produced highly accurate predictive models. Hyperparameter tuning further improved performance.  
- **Sentiment Insights:** Sentiment analysis correlated with stock price movements, highlighting the role of market sentiment in predictions.  

These results provide insights into market dynamics and demonstrate the importance of combining quantitative features with sentiment data for accurate stock price prediction.

---

## Technologies Used
- **Big Data Processing:** Apache Spark  
- **Programming Languages:** Python, SQL  
- **Machine Learning:** Linear Regression, Decision Trees, Ensemble Methods  
- **Sentiment Analysis:** NLTK SentimentIntensityAnalyzer  
- **Visualization:** Matplotlib, Seaborn, WordCloud

---

## License
This project is intended for educational purposes as part of the FDBA course. Please refer to any accompanying license documents for usage details.
