# Flight Price Prediction
![Flight](https://github.com/kyawkhaung/flight-price-prediction/blob/main/Flight.jpg)

### Problem Statement
As you all know, flight ticket prices can be something hard to guess. Today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travellers saying that flight ticket prices are so unpredictable. Huh! Here we take on the challenge! As data scientists, we are gonna prove that given the right data anything can be predicted. Here you will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities. Data is downloaded from [Machine Hack](https://www.machinehack.com/hackathons/predict_the_flight_ticket_price_hackathon/overview) site. 

Size of training set: 10683 <br> 
Size of test set: 2671 <br>

<b>DATASET FEATURES:</b><br/>
<b>Airline:</b> The name of the airline.<br/> 
<b>Date_of_Journey:</b> The date of the journey <br/>
<b>Source:</b> The source from which the service begins.<br/>
<b>Destination:</b> The destination where the service ends. <br/>
<b>Route:</b> The route taken by the flight to reach the destination.<br/>
<b>Dep_Time:</b> The time when the journey starts from the source.<br/>
<b>Arrival_Time:</b> Time of arrival at the destination.<br/>
<b>Duration:</b> Total duration of the flight.<br/>
<b>Total_Stops:</b> Total stops between the source and destination. <br/>
<b>Additional_Info:</b> Additional information about the flight Price: The price of the ticket

### Motivation
I bet that everyone is wondering about next vacation - how to spend your money. My family is always having conversation on when and where our next vacation should be. we may have different ideas about where to go for family vacatiion, we all have agreed that ticket price will outrageouly be expensive to recover their financial loss from this hibernating period in covid-19. My curiosity of flight ticket price lead me to work on this project to find out what the price would be when we will no longer have to worry about covid-19 and travel restriction is no longer imposed at everywhere. Of course, ticket price prediction may not make sense if you are ouside India although I hope that you may have appreciation on how powerful machine learning models are to perform such a task.

### Libraries used in the project
1. Jupyter
2. Pandas
3. Numpy
4. Seaborn
5. Sklearn
6. Lasso and Ridge
7. Elastic Net
8. XGboost
9. Random Forest
10. Ensembling Models

### Sections
Following topics will be explored and investigated. 
1. Import Libraries and Load Data
2. Feature Engineering and Data Cleansing
3. Data Exploration
4. Model Building and Tuning
5. Prediction with Test Data
6. Export Model for web application use
