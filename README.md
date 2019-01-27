

## Disaster Response Pipeline Project

###Libraries used :

nltk 3.3.0
numpy 1.15.2
pandas 0.23.4
scikit-learn 0.20.0
sqlalchemy 1.2.12


###This project has following files


workspace/data/process_data.py:

It is a data cleaning pipeline that:
It loads the messages and categories datasets
It merges the two datasets
It cleans the data
It stores it in a SQLite database

workspace/model/train_classifier.py:

It is a machine learning pipeline .
It loads data from the SQLite database
It splits the dataset into training and test sets
It bilds a text processing and machine learning pipeline
It trains and tunes a model using GridSearchCV
It outputs results on the test set
It exports the final model as a pickle file
