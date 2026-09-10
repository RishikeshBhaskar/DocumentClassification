A machine learning project for classifying text documents into five categories:
Politics
Sport
Technology
Entertainment
Business

The model performs text cleaning, EDA, TF-IDF feature extraction, and compares several classification models.

## Features:
Text is converted into TF-IDF features using a maximum of 4,000 features.
Document length was also tested as an additional feature, but it performed worse and was not used in the final model.

## Models:
The project evaluates:
Gaussian Naive Bayes
Multinomial Naive Bayes
Bernoulli Naive Bayes
Random Forest
Gradient Boosting
Logistic Regression
Voting Classifier

The best individual model was Logistic Regression with an accuracy of 97.89%.
The final Voting Classifier achieved 97.42% accuracy on the test set.
