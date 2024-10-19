# CODSOFT
First Task:
I recently completed a project using the Titanic dataset to predict survival outcomes based on various features. 
Here's a brief overview of what I accomplished:

Data Processing:
I handled missing values in the 'Age' column and dropped the 'Cabin' column to simplify the dataset.
I encoded categorical features like 'Sex' and 'Embarked' using one-hot encoding to prepare for modeling.

Model Building:
I selected relevant features for my model, including 'Pclass', 'Sex_male', 'Age', 'SibSp', 'Parch', and 'Fare'.
The target variable I focused on was 'Survived'.
I split the data into training and test sets using train_test_split.
I utilized Logistic Regression as my classification model.

Model Evaluation:
I evaluated the model using accuracy score and a classification report.
The model achieved an accuracy of approximately 81% on the test set!
I printed a detailed classification report showing precision, recall, 
and F1-score for both classes (survived and not survived).

Visualization:
I created a visualization showing survival rates by gender using Seaborn's countplot, 
highlighting the impact of gender on survival outcomes.
