# Airbnb_price_category_prediction

# Problem Definition
- Design a model to determine an appropriate listing price for a new listing on Airbnb. Instead of predicting the actual listing price using regression, the objective is to predict which pricing bin or range is appropriate for a new listing

- Input: summary and image (7627) for a training dataset.

- Output: price (7627).

# Function
text preprocessing -> tokenization and vectorization each text ->training the model -> classification and prediction.

# Challenges
We have a Uncleaned and untranslated Unbalanced data set so maybe will take some time to preprocess it and train it.

# Model impact
Predicting the actual price class beginner, plus, premium and Type

# The ideal solution
Using Dropout with Drop rate of 0.3
