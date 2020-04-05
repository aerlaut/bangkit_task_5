# AirBNB price prediction
We made a model to predict AirBNB price in 7 cities in the US based on  features such as
- Property type (Apartment, House, Condominium, etc.)
- The number of people that can be accommmodated
- Number of bedrooms, beds and bathrooms
- Cancellation policy
- City (Boston, Chicago, DC, LA, SF, NYC)
- Room type (Private room, shared room, entire home/apartment)

We used the publicly available data at Kaggle :
https://www.kaggle.com/stevezhenghp/airbnb-price-prediction

Data is also uploaded in available in this repo, with some columns truncated.

We worked collaboratively together using Google Collab. The model can be seen on this Collab: https://colab.research.google.com/drive/1SKaR_JIhz50oj1smiM5VOuQaoTqnhHAU

## Group members

The group members working in this group are :
- Christina ([chris-tinaa](github.com/chris-tinaa))
- Mutia Wahyuni ([mutiawhy](github.com/mutiawhy))
- Anugerah Erlaut ([aerlaut](github.com/aerlaut))

## Setup

We used Tensorflow to optimize a linear regression y = Ax + b. We used MSE as the loss function.

The model was trained with a learning rate of 0.001. After 5000 steps, the model achieved convergence.

## Results
Our model achieved a loss of 0.27 on the training set and the test set.

Upon sampling in the test data, the model predicted prices on average 35% more or less than the real price. With the current model, we have not reached our goal of predicting - on average - a maximum 20% more or less than the predicted price.