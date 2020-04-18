# Sparkify
![sparkify](/assets/sparkify.jpg)
## Table of Contents

- [Motivation](#motivation)
- [Insights](#insights)
- [Requirements](#requirements)
- [Links](#links)
- [Author](#author)

## Motivation <a name="motivation"></a>

In this project, I followed this process: 
-   Data exploration to know more about data features and stats. 
-   Define Churn and label data based on churn definition
-   Apply some feature engineering to apply some innovation and customizations to the generated model.
- Data transformation and splitting
- Model training, refinement and Evaluation

to analyze Sparkify(virtual music streaming service) data, in the way to achieve the goal of the project which is predicting which group of users are expected to churn - either downgrading from premium to free or cancel their subscriptions altogether in the future to take decision based on it, by sending offers or trying to make them still with our service.

## Insights <a name="insights"></a>

In this notebook, we implemented a model trying to predict customer churn. We removed rows with no userId, converted timestamp to a human-readable format, converted gender to a binary numeric column. features engineered to be suitable for our model.

- These selected models:   
    - logistic regression   
    - Deciesion Tree   
    - Gradient Boosted Trees (GBM)   
    - Random Forest   

 used to compare and select **GBM** as the final model implemented for predicting the final result. We used cross-validation and grid search to fine-tune our model. We achieved about 0.91 F1-score on validation set which is about 35% improvement compared to our naive logistic regression baseline model.

## Requirements <a name="requirements"></a>
You can find all the required libraries used in this project in ```requirements.txt``` .

## Links <a name="links"></a>
- Blog Post   
[How did I predict customer churn before it knocked on my door?](https://medium.com/@MahmoudAI/how-did-i-predict-customer-churn-before-it-knocked-on-my-door-958ade92232b?sk=e0b367d5516770e2c62cbcbacff3e878)

## Author
Mahmoud Ahmed
- [Github](https://devmahmoud10.github.io/portfolio/)
