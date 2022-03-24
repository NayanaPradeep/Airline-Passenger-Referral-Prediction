# Airline-Passenger-Referral-Prediction
In this project, I have built various predictive models to find whether the reviewer recommends travelling by a particular airline. The goal is to find the model that fits best into the dataset 'data_airline_reviews.xlsx'


# PROBLEM STATEMENT

Data includes airline reviews from 2006 to 2019 for popular airlines around the world with multiple choice and free text questions. Data is scraped in Spring 2019. The main objective is to predict whether passengers will refer the airline to their friends.

Feature descriptions briefly as follows:

*   airline: Name of the airline
*   overall: Overall point is given to the trip between 1 to 10.
*   author: Author of the trip
*   reviewdate: Date of the Review 
*   customer review: Review of the customers in  free text format
*   aircraft: Type of the aircraft
*   travellertype: Type of traveler (e.g. business, leisure)
*   cabin: Cabin at the flight 
*   date flown: Flight date
*   seatcomfort: Rated between 1-5
*   cabin service: Rated between 1-5
*   foodbev: Rated between 1-5 
*   entertainment: Rated between 1-5
*   groundservice: Rated between 1-5
*   valueformoney: Rated between 1-5
*   recommended: Binary, target variable

# CONCLUSION

**Support Vector Machine** being the model with highest accuracy rate by a very small margin, works best among the experimented models for the given dataset.
