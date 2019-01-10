# basket_prediction
Using past orders data, predict which previously purchased products will be in a user’s next order. 

# Notebooks:
 - Use *Extract_Features* notebook to extract all the relevant features for the user, items and user-item pairs
 - Use *Train_and_Test* notebook to train a gradient boosted decision tree on extracted features for given *n* weeks and make a prediction for *n+1th* week.
 
# Data
 - The data used for these notebooks have not been open sourced and hence cannot be shared. However, similar data for much many users and items are available [here](https://www.kaggle.com/c/instacart-market-basket-analysis/data).
 - The notebooks assume the following input data format: user_id, item_id, i_th_week, price_of_item, item_advertised_or_not
