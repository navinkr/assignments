As part of assignment "Create a toy model of environments" i have made a prediction model which predicts raninfall.

Root Directory = RainFallPrediction

Main file =Assignment_rainfall_prediction.ipynb  

https://github.com/navinkr/assignments/blob/master/RainFallPrediction/Assignment_rainfall_prediction.ipynb

In order to execute python file plese specify value of following paths . Actual path has been removed from code for security reasons.
pipe_del_file=""
output_model_file=""
training_set=""
test_set=""
future_set=""
path_Canbera =r''
path_Melbourne =r''
path_Queensland =r''


Data Direcotries

1.RainFallPrediction\data\data\Canbera

2.RainFallPrediction\data\data\Melbourne

3.RainFallPrediction\data\data\Queensland

Output Directories =data/output

Generated Output/Input Files

input_pipe_del.csv ---- Pipe delimeted file which is disussed in Task section

training_output.csv --- Training file which has been created by merging data from different sources

training_set.csv ---- Formatted training file in CSV , data is shuffeled in this file

test_data.csv --- Test file for prediction

test_data_future.csv -- A file has been created in case we want to test data on seprate data other than test data , just for testing purpose

output_Gradient Boosting.csv --File generated after predicting value from test_data.csv using Gradient Boosting algorithm

output_Random Forest.csv --File generated after predicting value from test_data.csv using Random forest algorithm

output_Ridge.csv --File generated after predicting value from test_data.csv using Ridge regression algorithm

output_OLS.csv --File generated after predicting value from test_data.csv using Ordinary least square algorithm
