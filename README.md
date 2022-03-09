# project-1. Individual Implementation Project


This project reads through a datbase from a popular anime rating website and trys to predict what the rating will be based on the other data provided. The code first reads in the database and transforms it to a dataframe. From their it goes through the datafram looking for any nonexisting or null data, and it will remove that row. Next it will print out a graph to visualize the data and then move on to making it into a pipeline and fitting it. 

The code will then create 2 pipelines, one using the KNN model and another useing random forest. It fits and tests both and finds out which one better predicts each test. In the end, Random forest did about 30% better than KNN. Then I ran it through a gridsearch and found the best parameters.