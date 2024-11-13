# House Price Prediction Model

The **House Price Prediction Model** is a machine learning project designed to analyze and predict house prices based on various features from the Boston House Price dataset. This model leverages the XGBoost Regressor algorithm to provide accurate predictions, along with visualizations and statistical metrics to assess feature correlations and model performance.

## Key Features

- **Exploratory Data Analysis (EDA)**:
  - Examines the dataset through summary statistics and correlation analysis.
  - A heatmap visualization highlights relationships between various features in the dataset.

- **Machine Learning Model**:
  - Utilizes an XGBoost Regressor to predict housing prices based on key features.
  - The model is evaluated using metrics like R-squared and Mean Absolute Error to measure prediction accuracy.

- **Prediction Visualizations**:
  - **Scatter Plot**: Compares actual vs. predicted prices, allowing a visual assessment of model performance. A reference diagonal line shows ideal predictions.
  - **Correlation Heatmap**: Provides an overview of feature correlations, helping in understanding which features are influential.

## Data Management and Preprocessing

- **Data Loading**: Imports the Boston House Price dataset and organizes it in a structured Pandas DataFrame.
- **Feature Engineering**: Prepares data by separating input features (X) and target labels (Y), then splits them into training and test datasets.
- **Preprocessing Checks**: Validates the data by checking for missing values and assessing statistical distributions.

## How It Works

1. **Data Loading and Preprocessing**:
   - Loads the dataset, assigns feature names, and adds a target column for house prices.
   - Analyzes data structure, checks for null values, and performs correlation analysis.

2. **Model Training**:
   - **XGBoost Regressor**: Trains the model on the training dataset to learn the relationship between input features and target prices.
   - **Performance Metrics**: Calculates R-squared and Mean Absolute Error to evaluate model performance on both training and test sets.

3. **Visualization of Results**:
   - **Correlation Heatmap**: Highlights feature relationships, aiding in feature selection and model understanding.
   - **Scatter Plot for Predictions**: Plots actual vs. predicted prices for training and testing datasets, including a reference line for ideal prediction visualization.

## Results and Insights

The model's effectiveness is assessed through:
- **R-squared**: Measures the proportion of variance in the target variable explained by the model.
- **Mean Absolute Error**: Quantifies the average prediction error.
- **Scatter Plots**: Provides a visual assessment of prediction performance by plotting actual vs. predicted prices for training and test sets.
