# ** Overview ** 

I am trying to make a model that tries to predict how many people in the five boroughs of New York City can afford to buy property here. So this project will use some sort of classification model that aims to do a binary classification, 'Can Afford' and 'Can't Afford' 

# ** Business  Understanding: ** 

 Because im sourcing the data myself, im using both the Census bureau data and a database with all of the data appended into one central dataframe. This dataframe should show the complexity of the listings by borough, bedroom numbers and also monthly morgatage prices / income. 

 # ** Data Understanding and Analysis: ** 
In the dataframe we have over 30,000 entries with about 10 columns with data. once it was one hot encoded we had over 18 columns with categorical data. So we're going to take this new version of the data and make a Logistic regression model, KNN model and a Decesion Tree model. 

# ** Results: ** 

When we ran all of our models the one that ran the accurately predicted the affordibility of the listings available to new yorkers, we found that the logistic regression model was the best at prediction and had the least amount of false positives. 

# ** Conclusions: **
As I assumed it turns out less than 1/3 of all new yorkers cannot afford the listings available, and the ones that can are concentrated in the borough of Manhattan, simply because they have a higher income than compared to the rest of the new yorkers situated in the other boroughs. 
 
