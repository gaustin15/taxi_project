# taxi_project
predicting duration of nyc taxi trips

This is for a school project, in which we were assigned to use BigQuery to load nyc taxi trip data, and train a model to predict the trip durations.
Requirements were to join at least one other table the data, and to only use data from the year 2016 when training the model. 
The test data is from the year 2015, so I am expecting the results on that data to be worse than those shown in the model selection file. 

For these ipynb files to run, a google bigquery account needs to be set up.

the APMA......csv.zip file contains the 2015 test data

The predictions.csv.zip contains the test data joined with any other information used in the model, with the last column being the predicted trip duration, in seconds. The predictions.csv file is what would be obtained from running the Make_Predictions.ipynb notebook. 
