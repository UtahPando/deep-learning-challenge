# deep-learning-challenge
Module 21 Challenge

# Neural Network Model Analysis 
The purpose of this analysis is to summarize the results of my neural-network modeling and optimizations

Answer all 6 questions in the results section (10)
Summarize the overall results of your model (4)
Describe how you could use a different model to solve the same problem, and explain why you would use that model (6)

# Summary 
Overall, the results of my deep-learning model were a bit of a disappointment, as I was not ever able to get all the way to 75% accuracy despite the various optimization methods I attempted.  With more time, I would play more with features and looking at correlations among them.
# Results

## Data Preprocessing
- <b>What variable(s) are the target(s) for your model?</b>
In the initial modeling, I used the IS_SUCCESSFUL variable as the target of my model

- <b>What variable(s) are the features for your model?</b>
In the initial modeling, I used the all the other variable as features target of my model with transformations for categorical variables and binning of less-frequent values of the CLASSIFICATION and APPLICATION_TYPE variables

- <b>What variable(s) should be removed from the input data because they are neither targets nor features?</b>
EIN and NAME were rremoved because they were neither targets nor features

## Compiling, Training, and Evaluating the Model

- <b>How many neurons, layers, and activation functions did you select for your neural network model, and why?</b>
In the first iteration, I used two layers in an attempt to capture more nuance in the data.  As part of my optimization, I added a third layer but without much improvement to accuracy
- <b>Were you able to achieve the target model performance?</b>
Across my different optimization attempts, all fell short of fully meeting the 75% accuracy target
- <b>What steps did you take in your attempts to increase model 
performance?</b>
In my attempts at increasing performance, I did the following:
    * Binned INCOME_AMT variable to create a single one for 
    * Dropped STATUS and SPECIAL_CONSIDERATIONS variables
    * Tried with different activation methods and added a third hidded layer
