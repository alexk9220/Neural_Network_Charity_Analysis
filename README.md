# Neural_Network_Charity_Analysis

## Overview of the analysis
Using my knowledge of neural networks and machine learning models I needed to create a working model that would show a high accuracy score (over 75%).

## Results


## Data Preprocessing

* What variable(s) are considered the target(s) for your model?
In my model the target was  "IsSuccessful" column and its values.

* What variable(s) are considered to be the features for your model?
All the other columns were my features for this model 

### Original Accuracy Score 


<img width="477" alt="Screen Shot 2021-04-06 at 4 27 56 AM" src="https://user-images.githubusercontent.com/73204192/113684879-a9ea5e00-9693-11eb-8d4d-1e3a4e2c996d.png">


## Compiling, Training, and Evaluating the Model

Trying to optimize my model I have dropped added another hidden layer and used a different activation function for it - "tanh". I have also tried increasing the number of neurons per layer and the ammount of epochs. While it did look promising - none of that was successful and my model's accuracy score only dropped. 

<img width="882" alt="Screen Shot 2021-04-06 at 5 01 37 AM" src="https://user-images.githubusercontent.com/73204192/113686565-6133a480-9695-11eb-8ea9-33fc0e4b182a.png">

## Summary
My deep learning model originally had an accuracy score of 69% - I was unable to increase it. I do believe that using some other activation or optimization function might help, also dropping one other column or some columns might be helpful.
