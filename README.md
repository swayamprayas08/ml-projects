# Machine Learning Projects

I've always been interested in how data can be used to understand real-world problems and make better predictions. I created these projects to explore different applications of machine learning and to get hands-on experience with the complete process, from working with raw data to preprocessing, feature engineering, model building, and evaluation.

The three projects cover different types of machine learning problems: detecting fraudulent transactions, understanding customer purchasing behaviour, and forecasting financial markets.

## Projects

### Credit Card Fraud Detection

Fraud detection is a good example of a machine learning problem where accuracy alone isn't enough. With fraudulent transactions making up only a very small fraction of the dataset, the model needs to identify the minority class without simply predicting every transaction as legitimate.

I explored the dataset, handled the severe class imbalance using SMOTE, applied PCA for dimensionality reduction, and compared Logistic Regression with Random Forest to understand how different models perform on this problem.

### Black Friday Sales Prediction

The Black Friday dataset contains information about customers, products, demographics, and purchases, making it an interesting regression problem for understanding customer purchasing behaviour.

I worked on preprocessing the different types of features, handling missing values and categorical variables, and compared Linear Regression, Decision Tree, and Random Forest models to predict customer purchase amounts.

### HDFC Bank Stock Forecasting

Financial markets provide an interesting application of time-series machine learning, where historical market behaviour can be used to study and forecast future movements. For this project, I worked with approximately five years of HDFC Bank historical market data.

I built a time-series forecasting pipeline using technical features such as moving averages, daily returns, volatility, and volume changes. I then used a 60-day historical window to train an LSTM model for next-day return prediction and compared its performance against a simple naive forecasting baseline.

## What I Learned

Working on these projects gave me exposure to different sides of machine learning rather than focusing on a single type of problem. Across the projects, I worked with:

- Data cleaning and exploratory analysis
- Feature engineering
- Handling imbalanced datasets
- Dimensionality reduction
- Categorical data preprocessing
- Regression and classification
- Time-series forecasting
- Neural networks and LSTMs
- Model evaluation and comparison

More importantly, these projects helped me understand that choosing and evaluating a model is just as important as building one. Comparing models against appropriate baselines and understanding where they fail has been one of the most useful parts of working on these projects.
