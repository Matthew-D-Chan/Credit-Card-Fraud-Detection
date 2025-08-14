# Credit-Card-Fraud-Detection

# Kaggle Dataset Used: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
- Get more context of the dataset from here!

# Tools Used:
- NumPy, Pandas
- Matplotlib
- Scikit-Learn
- TensorFlow

# Summary
- Imported dataset from Kaggle (over 280,000+ rows of data)
- Preprocessed data; Used RobustScaler and sigmoid function to make data easier to read for machine learning model
- Machine learning models: Logistic Regression vs. Shallow Neural Network. Neural network had greater recall, lower precision. Logistic Regression had the opposite. Shallow neural network had higher F-1, and let significantly less fraudulent transactions through (22%, compared to Logistic regressions 47%)
