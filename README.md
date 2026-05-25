# imdb-rating-prediction
## Overview

This project analyzes the IMDb Top 1000 Movies dataset from Kaggle to identify factors associated with highly rated films. The project includes data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning using Python.

A linear regression model was developed to predict IMDb ratings using movie metadata, audience engagement metrics, and engineered features.
## Objectives

- Analyze patterns in IMDb movie ratings
- Explore relationships between ratings, revenue, votes, and critic scores
- Visualize genre and release-year trends
- Engineer additional predictive features
- Build and evaluate a machine learning model for IMDb rating prediction

## Dataset

Dataset: IMDb Top 1000 Movies Dataset  
Source: Kaggle

The dataset contains movie information including:
- IMDb ratings
- genres
- runtime
- metascores
- gross revenue
- vote counts
- release years

## Technologies Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

## Project Workflow

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Machine Learning Model Development
5. Model Evaluation and Interpretation

## Key Findings

- Most movies in the dataset had IMDb ratings between 7.5 and 8.0.
- Audience engagement (number of votes) showed one of the strongest relationships with IMDb ratings.
- Older classic films tended to maintain slightly higher ratings.
- Gross revenue alone was not a strong predictor of IMDb ratings.
- Movies released after the 1980s were more heavily represented in the dataset.

## Machine Learning Results

A Linear Regression model was trained to predict IMDb ratings using:
- Runtime
- Meta Score
- Number of Votes
- Gross Revenue
- Revenue per Vote
- Movie Age

### Model Performance
- R² Score: 0.52
- RMSE: 0.20

The model demonstrated moderate predictive performance and identified critic scores and audience engagement as meaningful predictors of IMDb ratings.

## Future Improvements

- Test additional machine learning models such as Random Forest Regression
- Incorporate natural language processing (NLP) on movie descriptions
- Add genre encoding techniques
- Develop an interactive dashboard using Tableau or Streamlit
- Perform feature scaling and hyperparameter optimization

## How to Run the Project

1. Clone the repository
2. Install required Python libraries
3. Open the Jupyter Notebook
4. Run all cells sequentially

Required libraries include:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
