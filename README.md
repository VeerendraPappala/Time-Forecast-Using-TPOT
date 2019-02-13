# Time-Forecast-Using-TPOT

Automated machine learning doesn’t replace the data scientist, (at least not yet) but it might be able to help you find good models faster. TPOT bills itself as your Data Science Assistant.

## About TPOT
TPOT is meant to be an assistant that gives you ideas on how to solve a particular machine learning problem by exploring pipeline configurations that you might have never considered, then leaves the fine-tuning to more constrained parameter tuning techniques such as grid search.

## An example of tpot learning pipeline:
![tpot](https://user-images.githubusercontent.com/45025357/52726728-c3268100-2fd9-11e9-9532-bb85d2c7a79b.png)



TPOT is built on the scikit learn library and follows the scikit learn API closely. It can be used for regression and classification tasks and has special implementations for medical research.

## How does TPOT work:

![tpot-2](https://user-images.githubusercontent.com/45025357/52726768-d2a5ca00-2fd9-11e9-8c2c-9fd82719659b.png)


## Data: 
The data set was about predicting engineers of Daimler’s Mercedes-Benz cars speed of testing system, the purpose is to reduce the time that cars spend on testing, with over three hundreds of features. This data set contains an anonymized set of variables, each representing a custom feature in a Mercedes car.
The target feature is labeled “y” and represents the time (in seconds) that the car took to pass testing for each variable. 

### Everything was coded in Google Colab, because of its GPU. 
