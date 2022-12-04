# Project 1: 

## Description

The dataset is an extraction of HR DBs from several sources.Load the dataset into Python using Pandas and start your 
The task is to determine whether a person can make a salary over $50K a year or not depends on the other attributes.

    Target Attribute: income

### Excluded from the task:
-   Delete the column "fnlwgt" from the dataset. It is not required for this project
   

### Targets to reach:
1. Build ML Model(s) to classify a person whether can make over $50K a year or not
2. Start by writing a notebook 
   1. Explore the data
   2. Clean the data
   3. Build a model(s)
   4. Save the model(s) into a binary file(s) (pickle or joblib)
   5. Use the saved model(s) to predict a new record
   6. Save the scores and models' parameters into a SQLite DB.


3. Start writing a python program
   1. Functional oriented or object oriented
   2. you need to split your program in several python files (modules). Not to make the application in only one single file
   3. Use logging to trace your program 
   4. When using the program for prediction, send an email to any target email address with the predicted result (only for people outside WBS-location due to proxy issues)



___
## Delivery:
- The project is an individual work
- Well documented functions and classes
- A Markdown file describing your solution 
  - which model did you use and why
  - how to use your model? how to run it ?
- If you did some comparing between models, attach the summary file  
- Format: Zip file with everything. The name of the zip file is [first_name]_[last_name]_P1.zip
- You will get the information later where and when to upload the solution. Do not upload it till you get the information.

___
## Hints:
- The data are not clean, there are some missing values
- The dataset has several categiorical columns, such "education", you need to LabelEncode these columns
- Try to solve the project with one classification model first of all, then empower your solution by the next model(s). DO NOT Try everything from the first shot, you may not reach anything at all

- KEEP IT SIMPLE AND STUPID (KISS)...> this is the start. Don't think how to make the best solution. Try to make a stupid working solution, then optimize it.
- Just for the time management, you need to finish the project by Wednesday.