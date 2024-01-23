# Advanced Linear Regression
> Surprise Housing, a housing company based in the United States, is tasked with creating a model to predict house prices based on available independent variables. The management plans to utilize this model to gain insights into the precise relationship between prices and these variables, enabling strategic adjustments to focus on areas with high return potential. Moreover, the model will provide valuable insights for the management to comprehend the pricing dynamics of a new market.

> Model Objective:
The company aims to determine: -

Which factors play a significant role in forecasting the housing price?

How effectively do these variables characterize the housing price?

>Business Goal

Your task is to develop a model for predicting house prices using the available independent variables. The management will utilize this model to gain insights into how prices vary with these variables, enabling strategic adjustments and a focus on areas with high return potential. Moreover, the model serves as a valuable tool for management to comprehend the pricing dynamics of a new market.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem Statement
Surprise Housing, a housing company based in the United States, is tasked with creating a model to predict house prices based on available independent variables. The management plans to utilize this model to gain insights into the precise relationship between prices and these variables, enabling strategic adjustments to focus on areas with high return potential. Moreover, the model will provide valuable insights for the management to comprehend the pricing dynamics of a new market.

The company aims to determine: -

Which factors play a significant role in forecasting the housing price?

How effectively do these variables characterize the housing price?

### Business Goal
Your task is to develop a model for predicting house prices using the available independent variables. The management will utilize this model to gain insights into how prices vary with these variables, enabling strategic adjustments and a focus on areas with high return potential. Moreover, the model serves as a valuable tool for management to comprehend the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- After constructing the model, we opt for lasso regression. Lasso proves advantageous by shrinking the coefficients of variables, facilitating feature elimination and simplifying the model. This decision is made considering the similarity in r2_score for both regression models. Additionally, lasso is effective in addressing multicollinearity issues.


### Evaluation Summary

- alpha value:
    - 0.0001
- r2_score
    - train: 0.9407
    - test: 0.8572

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.7.3
- Pandas - version 1.3.4
- numpy - version 1.21.5
- matplotlib - version 3.1.3
- seaborn - version 0.12.2
- sklearn - version 1.0.2
- statsmodel - version 0.13.2



<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@girishsatyam] - feel free to connect with me.


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
