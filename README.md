# Kaggle diamonds price predictions
![](https://static.wikia.nocookie.net/ronroblox/images/0/00/Diamond.jpeg/revision/latest?cb=20210707175303)
## Objective
The goal of this project is getting the best price prediction having different characteristics of them.

## Process
* We got a dataset that explained different features in a diamond.
* The first step was exploring and analyzing the data. Some columns were categorical, so I transformed them into numeric so the model could get a better prediction.
* Once my dataset was clean and ready, I tried different algorithms and checked their results depending on their Root Mean Square Error, which is the metric that is used to check the quality of the prediction.
* After choosing an algorithm, I changed their hyperparameters to get a lower Root Mean Square Error.
* I saved the prediction and uploaded it to Kaggle to compare it with the data that is not known.

## Conclusion
The best predicting model I could find to get the lowest Root Mean Square Error was the 'ExtraTreesRegressor' algorithm. I could adjust my prediction to the unknown data stored in Kaggle to a Root Mean Square Error of 543, which was one of the lowest.