# Introduction
The problem I'm trying to solve is a competition on Kaggle.com. We get the training set containing features such as age, sex, pclass etc., we build a classification model on this data and then predict the outcome of the testing set. This is a supervised machine learning problem because we get the features *and* the results of the training set.
The outcome for each person is a binary classification whether that person survived or not.

# Feature explanation
* PassengerId - represents one's id
* Pclass - represents one's ticket class (contains one of the three numbers - 1 for the 1st class, 2 for the 2nd class and 3 for the 3rd class)
* Name - represents one's name (a string value containing the name, last name and the title (such as Mr, Miss, Mrs etc))
* Sex - represents one's sex (two values - either 'male' or 'female')
* Age - represents one's age (a float or int value (float if the age was estimated or when the person was younger than 1 year old))
* SibSp - represents the number of one's siblings/spouses aboard (an int value)
* Parch - represents the number of one's parents/children aboard (an int value)
* Ticket - represents one's ticket number (a string containing digits and/or letters)
* Fare - repressents one's fare (a float value)
* Cabin - represents one's cabin number (a string containing a letter and a number)
* Embarked - represents one's port of embarkation (3 different values - C (Cherbourg), Q (Queenstown), S (Southampton))

# Score
The best achieved score on kaggle was 78.2%.