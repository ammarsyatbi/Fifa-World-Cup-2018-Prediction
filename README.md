# Fifa-World-Cup-2018-Prediction

### Using MLP Classifier to predict world cup finals

Predicting world cup finals based on sofifa dataset and past result.

## Library used ##

- pandas
- matplotlib
- sklearn
- numpy
- scipy
- pylab

**All the dataset located in /dataset folder. I list the filename so its easy for me to grab and visualize each of the data*

### Preparing data

From the data that i've got, I try to find the one that is relevant which is in my opinion is 
the sofifa stat and the label is obviously the result since that is what we want to predict. However, for multilabel prediction, the data prepared is slightly different

The data is prepared by getting the stat of the team and the opponent stat. This stats will be the input to the model and predict how many can the team score. 

### Analysis
Several analysis has been done to find out top scorer for home, away and overall (spoiler: belgium).