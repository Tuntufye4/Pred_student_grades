# Pred_student_grades

Machine learning model trained to predict the final grade of a student.

## Dataset info

This dataset contains various information about students like grades, studytime, health, internet access, gender, age and other details.
More information about the dataset can be found here :[student_grade_dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance)

## Method

Linear regression algorithm was used to train this model. Algorithm was imported from a Python library Scikit-learn.

Install Scikit-learn:

```
pip install scikit-learn

```

## Model Description

80% of the dataset is used to train the model and 20% is used for testing. The features used to predict final grade are first grade, second grade, studytime, failures and absences. The accuracy of the model is 84%.
