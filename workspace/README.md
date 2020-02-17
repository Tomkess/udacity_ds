# Disaster Response Pipeline Project

### Summary
The project is part of the Udacity nanodegree program. The goal of the project is to provide an application that will categorize the messages into 36 groups. The workflow is as follows - ETL extracting the data and putting it into SQlite database, ML pipeline fitting the machine learning model using GridSearch functionality and App visualizing the results.

### Screenshots

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/
