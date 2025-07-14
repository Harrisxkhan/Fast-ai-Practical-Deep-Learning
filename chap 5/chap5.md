iN this video we built a Linear model, binary calssifier from scratch
We implemented a linear model that perform a binary calssification
Basically we tranined a model on titanic data, Where (0 = did not survive, 1 = survived)
First we loaded a titanic CSV and and started cleaning data
checked for missing values
Filled gap with most common values, thats called imputing missing values in cleaning data
Converted the cleaned dataframe into pytorch tensors
built a linease model, initlized wights, computed sums, like features + weights, appiled sigmoed for porbablity, with sigmoid it will give us values like 0 and 1, defined loss and ran gradient decent in pytorch
split data into tranin loss (Binary cross entropy loss.) ..
explanded the model into a tiny nuerl neyt one hidden layer, and applied relu, tranined the same way
Because linear model just learn simple straght patterens
Adn applied relu activated layer so that model can capture non linear patterns , mean complext patterns, not just straight line.