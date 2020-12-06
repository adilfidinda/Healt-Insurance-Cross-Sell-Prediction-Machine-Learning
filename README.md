# Healt Insurance Cross Sell Prediction

## Problem
Company that provide health insurance for their customers want to expand their services by providing vehicle insurance for their customers. This company want to see the tendency of customers who have been given health insurance to be interested in vehicle insurance services

## Goals
Build a model to predict the potential customers that will be interested in vehicle insurance. This can help the company to be able to develop a communication strategy with customers who might be interested

## About Data

![alt text](images/cross_sell.JPG)

## Exploratory Data Analysis
- Customers are in the age range of 20 - 85 years
- There are customers who have a driving license and some are not
- Premium payments for health insurance range from 2630 - 540165
- The length of time the customer uses insurance services at the company is in the range of 10 days - 299 days

![alt text](images/outliers.JPG)

- There are many outliers on the premium that must be paid annually. This can happen because each customer uses insurance with a different category / service

![alt text](images/response.JPG)

- A total of ~ 88% responded not interested (Data imbalanced)

![alt text](images/response_by_age_group.JPG)

- Adult and Eldery 1 is the most age group who response yes

![alt text](images/age_group_and_premi.JPG)

- Adult and Eldery 1 have more customers who pay with a higher premium who response yes. This company doesn't need to worry because pretty much of high premium customers are interested in buying insurance which this brings profit to the company

![alt text](images/response_by_gender.JPG)

- This company have more dominant male customer who response yes

![alt text](images/response_by_driving_license.JPG)

- Customers who already have a driving license tend to be interested in vehicle insurance services

![alt text](images/response_by_vehicle_age.JPG)

- Customers who have a vehicle age of 1 - 2 years tend to be interested in vehicle insurance services

![alt text](images/response_by_Previously_Insured.JPG)

- Customers who don't have vehicle insurance before are more potential to response yes

![alt text](images/response_by_vehicle_damage.JPG)

- Customers who have previously experienced damage to their vehicles tend to receive vehicle insurance services

![alt text](images/response_by_premi_group.JPG)

- Customers who have premi range between 50.000 - 150.000 in healt insurance tend to be interested in vehicle insurance services

![alt text](images/response_by_vintage_group.JPG)

- Customers who associated with a company in 100 - 200 months are more potential to response yes

## Recommendation
- Targeting customers who :
    - don't have vehicle insurance before but have driving license
    - Adult and Eldery 1
    - Experienced damage because they will be more preserving their assets
    - Low to medium premium customers because of their income makes them more entrusted with insurance so they no longer need to worry about thinking the amount of costs to be borne, because the insurance company will cover it based on the applicable policy
    - Customer who associated with this company between 100 - more than 200 months
    
 - Targeting millennials customers because they should be considered a first step in a long relationship
 
 ## Machine Learning
![alt text](images/evaluation_matrix.JPG)

In this project, number of False Negative (FN) is need to be concern because of people who are actually attracted are predicted not, the risk is missed opportunities. So, it will focus on FN as low as possible. Even though the FP value is high, this can at least attract some customers to buy the policy even though the costs and efforts incurred are also greater.
