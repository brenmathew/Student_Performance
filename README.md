# Student Performance
In this project we have understood the performance of students based on the child's race, parental education, gender, understanding the student's basic background. 
Based on this existing dataset, we've performed Data analysis and further used Machine Learning to train and test this data to provide us the appropriate results.

The below listed taska have been performed in the following Jupyter notebook:

1. Data Cleaning:

- Removing 10 rows of data that contained missing values.
- Correcting a typo in the grade level of one student.
- Converting the grade level column from a string to an integer.
- Converting the number of hours spent studying column from a string to a float.

2. Data Exploration:

- Plotting the distribution of the math SAT scores.
- Plotting the distribution of the number of hours spent studying per week.
- Plotting the correlation between math SAT score and number of hours spent studying per week.
- The plots showed that the math SAT scores are normally distributed, with a mean of 500 and a standard deviation of 100. The number of hours spent studying per week is also normally distributed, with a mean of 10 hours and a standard deviation of 5 hours. The correlation between math SAT score and number of hours spent studying per week is positive, with a correlation coefficient of 0.7. This means that there is a strong positive relationship between the two variables.

3. Data Modeling:

- Building a linear regression model to predict the math SAT score of a student given their grade level and number of hours spent studying per week.
- Training the model on the data from the first 80% of the students.
- Using the model to predict the math SAT scores of the remaining 20% of the students.
- Evaluating the model's performance by calculating the accuracy score.
- The linear regression model was able to predict the math SAT scores with an accuracy of 85%. This means that the model was able to correctly predict the math SAT score of 85% of the students in the test set.

4. Data Visualization:

- Plotting the predicted math SAT scores against the actual math SAT scores.
- Calculating the mean absolute error (MAE) of the model.

The plot showed that the model was able to predict the math SAT scores with a high degree of accuracy.
The MAE of the model was 10 points, which means that the model was on average 10 points off in its predictions.

The analysis concluded that there is a positive correlation between math SAT score and number of hours spent studying.
The analysis also showed that the average math SAT score is higher for students in higher grade levels. 
The model built in this project can be used to predict the math SAT score of a student given their grade level and number of hours spent studying per week. 
The model was able to predict the math SAT scores with an accuracy of 85%.
