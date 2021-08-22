# About the DataSet
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others. So this dataset is for some of the passengers of Titanic like their names, personal details, booking details and whether  they survive or not. 

# Dataset Details
1. Passenger_ID : Unique ID of the Passenger.
2. Survived : Wether the passenger Survived or not.
3. Pclass : Pclass of the passenger.
4. Name : Name of the passenger.
5. Sex : sex of the passenger.
6. Age : Age of the passenger.
7. Ticket : Ticket no. of the passenger.
8. Fare : Fare paid by the passenger.
9. Cabin : Cabin of the passenger.

# Objective
We have to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

# Building Model
First we have import some libraries like numpy, pandas, seaborn, matplotlib.pyplot and sklearn.

Now import the dataset into a variable and have a look at the data using .head() meathod.

Using seabon build some countplot to see the various trends.

Check for null values using .isnull()meathod and if found fill them with either mean or mode which is more suitable.

Drop some not necessary columns like passenger_Id, Name and Ticket.

Now using test_train_split form sklearn.model_selection and logistic regression from sklearn.linear_model build model to predict “what sorts of people were more likely to survive".

Check the accuracy score and confusion_matrix of the model by importing accuracy_score., confusion_matrix from sklearn. 

# Output
Got the accuracy score of the model 80%. 
