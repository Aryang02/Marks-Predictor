## End to End Machine Learning Project

### Project Description:
- This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.

### Data Source:
- Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977

### Dataset Information:
- The data consists of 1000 rows and 8 columns.

Columns:
- Categorical:
  - gender : sex of students -> (Male/female)
  - race/ethnicity : ethnicity of students -> (Group A, B,C, D,E)
  - parental level of education : parents' final education ->(bachelor's degree,some college,master's degree,associate's degree,high school)
  - lunch : having lunch before test (standard or free/reduced)
  - test preparation course : complete or not complete before test

-Numerical:
  - math score
  - reading score
  - writing score

### Models:
The following models have been trained:
- Random Forest
- Decision Tree
- Gradient Boosting 
- Linear Regression
- K-Neighbours Classifier
- XGBClassifier
- Catboosting Classifier
- AdaBoost Classifier

The best model is chosen from these models based on their r2 score

The predictions are made by the selected best model

### Setup:
Follow these steps to run:
In the terminal run,
- activate the environment,\n
    conda activate venv/
- install the requirements, 
    pip install -r requirements.txt
- run the app using the command, 
    python app.py