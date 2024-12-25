# Airline Sentiment Analysis and Customer Satisfaction Evaluation

This project analyzes airline customer reviews to uncover factors influencing satisfaction, compare airline performance, and assess the reliability of verified vs. unverified reviews. The project employs machine learning models, including VADER (a rule-based sentiment analyzer) and an LSTM-based neural network, to classify sentiments and derive actionable insights for the airline industry.

## Project Overview
The airline industry is highly competitive, and customer satisfaction plays a crucial role in retaining passengers. This project:

- Analyzes a dataset of airline reviews to identify key performance indicators (KPIs).
- Evaluates the impact of verified and unverified reviews on customer satisfaction.
- Implements sentiment analysis using VADER and LSTM-based models.
- Visualizes findings to provide actionable recommendations for airlines.

  ## Key Features
- **Data Cleaning and Preprocessing:** Handles missing values, converts data types, and removes duplicates.
- **Exploratory Data Analysis (EDA):** Includes statistical analysis, heatmaps, and visualizations.
- **Sentiment Analysis:** Utilizes VADER for quick sentiment classification and LSTM for more nuanced predictions.
- **Airline Performance Comparison:** Ranks airlines based on overall ratings and evaluates customer feedback.
- **Visualizations:** Heatmaps, bar charts, pie charts, and word clouds to present insights clearly.

## Technologies Used
- **Programming Languages:** Python
- **Libraries:**
  - Data Processing: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `wordcloud`
  - Machine Learning: `tensorflow`, `keras`, `nltk`, `sklearn`
  - Sentiment Analysis: `vaderSentiment`
 
## Results and Insights

### Sentiment Analysis
- VADER achieved an accuracy of ~65%, but struggled with mixed sentiments.
- LSTM achieved an accuracy of ~92.15%, significantly improving sentiment classification.

### Key Findings
- **"Value for Money"** is the most significant factor influencing overall ratings.
- Verified reviews are more reliable and consistent than unverified ones.
- Economy class feedback constitutes 82.6% of all reviews, highlighting a critical area for improvement.
