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

Linear regression means a conru=ineus values

logistcci reagression means , category, or yes or no

A long tail distribution means most items have small values, but a few items have very large values, which creates a “long tail” on the right side of the graph.

So the full process is:
🗂️ You start with a DataFrame (from pandas)
→ It has text like "male", "female", "S", "Q", etc.

🔢 Convert text to numbers
→ Using pd.get_dummies() to get 1s and 0s

📦 Convert numbers to PyTorch tensors
→ Using tensor(...) so that PyTorch can understand and work with them

🧠 Give tensors to the model
→ Now it can multiply weights, calculate errors, learn, and update!

( generlly a python error names)
indentaion error means= spacing error
type error means =data dtpe error
attributeerror = fucntoinor a property with (.)
nameerror = you used a varible that is not defined
Vlaueerror = the value is wrong even if the type is correct.


Sigmoid is an activation function that squashes number into 0 and 1, so the model could predcittyhe ptobablity, 0 = died, 1 = survived


We coulld use a framework, that will do all the heavy lifting for us.   


---
we cleaned the titanic data, ysing pandas etc, imputing value etc, then we applied gradeint decent and trained it eetc.
