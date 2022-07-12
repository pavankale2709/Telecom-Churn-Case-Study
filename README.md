# Telecom Churn Case Study
> In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- For many incumbent operators, retaining high profitable customers is the number one business goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn.
- In this competition, your goal is to build a machine learning model that is able to predict churning customers based on the features provided for their usage.
- The main goal of the case study is to build ML models to predict churn. The predictive model that you’re going to build will the following purposes:
	* It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.
	* It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.
	* Even though overall accuracy will be your primary evaluation metric, you should also mention other metrics like precision, recall, etc. for the different models that can be used for evaluation purposes based on different business objectives. For example, in this problem statement, one business goal can be to build an ML model that identifies customers who'll definitely churn with more accuracy as compared to the ones who'll not churn. Make sure you mention which metric can be used in such scenarios.
	* Recommend strategies to manage customer churn based on your observations.

## Conclusions
- Most important variables that govern the customer churn are:
	* total_ic_mou_8, total_og_mou_8,  roam_og_mou_8
	* arpu_8
	* max_rech_amt_8, total_rech_amt_8
	* fb_user_8 



## Technologies Used
- library - numpy
- library - pandas
- library - matplotlib
- library - seaborn
- library - sklearn
- library - statsmodels
- library - xgboost


## Contact
Created by [@pavankale2709] - feel free to contact me!

