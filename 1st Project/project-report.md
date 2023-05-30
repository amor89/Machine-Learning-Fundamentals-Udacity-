# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Amor Perez

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: I realized than the first submissions was with the data raw, without Data Cleaning and Feature Engineering. The changes needed to the output of the predictor to submit my results was to clean the data and create new features. For that reason, the performance of the second time was better than the first time. Other thing was to change the hyperparameters of the model, for example, the number of trials, scheduler, search, etc.
I had to clarify that I run the model in my machine for that reason I adapt the kaggle code. 

### What was the top ranked model that performed?
TODO: The top ranked model that performed was the model with the hyperparameters. 

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: The EDA was needed to add features based in the datetimes and also to change the type to categories for the variables "season" and "weather", tranforsming them into categoricals.  The additional features were created with the datetimes, for example, the hour, day, month, year, etc.

### How much better did your model preform after adding additional features and why do you think that is?
TODO: The model improve a lot after adding additional features, because the model can learn more about the data and the patterns.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: The model improve a lot after trying different hyper parameters, because the model was adapted, but the change wasn't as significative as after the EDA from the inicial model.

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: I would spend more time in the EDA and in the hyperparameters, because I think that the model can improve more with this changes.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
model	timelimit	presets	hp	score
0	initial	600	best_quality	None	1.84216
1	add_features	600	best_quality	EDA before and cleaning	0.64167
2	hpo	600	best_quality	num_trials: 20, scheduler : local, searcher: r...	0.49980

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](img\model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img\model_test_score.png)

## Summary
TODO: The better improvement in the model was after the implementation of the EDA. After when we change the hyperparameters, the model improve a little bit, but not as much as the EDA.
