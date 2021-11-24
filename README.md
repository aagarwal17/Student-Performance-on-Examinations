Introduction:

The purpose of an examination is to understand the ability and learning of a student; thus, through careful analysis of patterns between parental level of education, gender, race, reading scores, writing scores, math scores, and other factors from the Kaggle dataset named 'StudentPerformance.csv', one can understand which aspects have the largest impact on test outcomes as well as what are the best ways to improve student scores for the future. Furthermore, the improvement of test scores would benefit the economy at a national level by creating equality, leading to major GDP growth, and building a modern society. Correlated with improved test scores is a stronger education system, which for the learner, creates more employment opportunities, secures a higher income, develops problem-solving skills, provides a prosperous and happy life, and educates them to give back to the community.

Prediction of student academic performance in mathematics, reading, and writing based on various demographic and socioeconomic statistics can be performed through creation of various data science models such as linear regression, logistic regression, and k-NN. A model with good RMSE, MSE and MSAE scores signifies the model predicts student’s performance well, making the data useful in identifying methods to improve student performance for the future. The early detection of students who are vulnerable to suffering academic failure (through use of these models) can subsequently be used to design new teaching/mentoring strategies for an overall strengthening education system and society.

Goal:

The goal of this project is to use various supervised learning techniques including linear regression and logistic regression to ultimately predict student’s performance on examinations based on multiple socioeconomic and demographic statistics such as gender, race/ethnicity, parental level of education, and provided test scores. The dataset, provided by Royce Kimmons, has such data for 1000 students and includes both features—gender, race/ethnicity, parental level of education, test preparation course, lunch—and dependent variables/targets—scores in reading, writing, and mathematics. Unfortunately, not all essential and useful pieces of data, such as hours spent studying, are provided by this dataset, so I can only perform analysis of the effects these features have on performance. The model will be fit with a Linear Regression model (because we are interested in the factors that influence performance). However, prediction of student performance will also be performed through creation of various types of graphs and other models such as Linear Least Squares Regression and Logistic Regression. Through analysis of these models, we will also be able to determine the effectiveness of test preparation courses and the effect food/lunch has on performance. For each model, I will use different hyperparameters and preprocessing techniques to optimize performance.

Questions to Try to Answer:
1. What effect does having or not having lunch place on student performance?
2. Is there substantial differences seen between males and females in regards to examination performance?
3. Does the parent's level of education impact the success of the student?
4. Does one's race serve as a benefit or hindrance (or neither) to their performance on examinations?
5. Will taking a test preparation score have a positive impact on student's examination scores?
6. Can we predict student performance by creating models with the provided dataset?
7. Can we predict one's gender by creating models with the provided dataset?
8. Are their high correlations between any of the features/target variables?
