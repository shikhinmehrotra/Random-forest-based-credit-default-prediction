# Random-forest-based-credit-default-prediction
This project uses random forests to predict whether a customer defaults on their credit payment or not.

# Data set
The data set consists of 30,000 entries of customer's default status as well as 24 features including their personal details, financial details, earning capability etc.

# Data preparation and model building
The data is split into training and test data. Then, a random forest model is built using SkLearn's RandomForestClassifier() class using default parameters. This  preliminary model gives an accuracy of 82.7%.

# Hyperparameter tuning
Using SkLearn's GridSearchCV() class, several available hyperparameters such as max_depth, n_estimators,max_features, min_samples_leaf and min_samples_split. The most optimal hyperparameters found using GridSearchCV() are used to train the model and an accuracy of 82.7% is achieved. Therefore no significant improvement is found over the default parameters.
