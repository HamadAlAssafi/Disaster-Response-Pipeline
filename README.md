# Disaster Response Pipeline Project

### Summary of the Project

1. The project related to Data Science Nanodegree at Udacity
2. I have used ETL Pipeline to make the data ready to used in Machine Learning Model
3. I have used NLP and Machine Learning Pipelines to create model that classifiy each type of disaster to it is type, the algorthim that I used is (Random Forest Classifier)
4. I have deployed the model to website using (Flask), also I have created two visualization using pyplot library which are embedded in the web application
5. The data was gathered by FigureEight

### Files Description

1. App Folder

- It contains the (Flask) app that runs the model within web app
- Also it contains HTML files to visualize and make user inputs their message

2.  Data Folder

- It contains CSV files that have all the data that I used to build the model
- Also it contains Python file to make the ETL pipeline

3. Models Floder

- It contains the model itself as (PKL)
- Also it contains Python file to make the NLP and Machine Learning pipelines

4. README FILE

### Instructions:

1. Run the following commands in the project's root directory to set up your database and model.

   - To run ETL pipeline that cleans data and stores in database
     `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
   - To run ML pipeline that trains classifier and saves
     `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
   `python run.py`

3. Go to http://0.0.0.0:3001/
