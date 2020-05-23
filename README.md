# Predicting-Bitcoin-Price-Variations

## Description
The project focuses on prediciting the price varaitions of the cryptocurrency bitcoin. We use Bayesian Regression to perform the prediction.

## Dataset

The orignal raw data can be found from the following link http://api.bitcoincharts.com/v1/csv/. The original dataset consists of three attributes i.e 
* time in epoch
* price in USD per bitcoin
* bitcoin amount in transaction (buy/sell)

However, for this project we were given a processed data which consists of only first two attributes. The dataset used in this project is available in the data folder.

## Implementation

To predict the future price variation, we implement a Bayesian Regression model based on the reference paper[1]. The steps performed in the implementation are as follows:
* Computing price variations for train2 using train1 as input.
* Compute the linear regresion parameters (w0,w1,w2,w3).
* Use linear regression model and Bayesian Regression Estimates to predict the price variations.
* Compute the means squared error for test dataset.

## Results
![alt text](https://github.com/kdave97/Predicting-Bitcoin-Price-Variations/blob/master/results.JPG)

## References
1) Shah, Devavrat & Zhang, Kang. (2014). Bayesian regression and Bitcoin. 2014 52nd Annual Allerton Conference on Communication, Control, and Computing, Allerton 2014. 10.1109/ALLERTON.2014.7028484. 

---- A more detailed explanation about the project is explained in Project-Bitcoin-Bayesian.Regression.pdf -----

