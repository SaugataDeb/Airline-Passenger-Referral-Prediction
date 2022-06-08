# Airline Passenger Referral Prediction
## **Abstract:**
Air business as we know has been largely affected due to Covid-19 and most of the airline now is sitting on the verge of Bankruptcy because of this situation. Any bad decision may lead to severe outcomes where no stakeholder wants to invest without any future assurance. As an example of Singapore airlines who are among the hardest hit. As we know this situation is not permanent and it will be over but once this is over there will be a high surge as people will be back for holidays overseas. What can airlines do to tackle this situation? To answer this question, a machine learning model for classification is created from the airline_reviews dataset. This dataset has been  provided to us by Almabetter in order to identify the important factors that lead to better customer satisfaction.
## **Introduction**:
The Airline passenger Referral system has become the most important criteria globally for the airline industry in order to address the surge which has been created after global pandemic so as to remain in the global market competition. 
Airline referral system generally works on customer reviews which is basically sentiment given by the customer depending upon various factor like seat comfort, their trip distance, route they have travelled, timing, the airline frequency, ground service etc. on the basis of which sentiment reviews are analysed and machine learning model on classification is prepared which helps airline industries to focus on the factor resolving which it can actually help them in business growth better than the competitors
## **Problem Statement**:
Data includes airline reviews from 2006 to 2019 for popular airlines around the world with multiple choice and free text questions. Data is scraped in Spring 2019. The main objective is to predict whether passengers will refer the airline to their friends.

## **Data descriptions:**


*   **airline**: Name of the airline.

*   **overall**: Overall point is given to the trip between 1 to 10.


*   **author**: Author of the trip


*   **reviewdate**: Date of the Review customer review: Review of the customers in free text format



*  **aircraft**: Type of the aircraft

*   **travellertype**: Type of traveler (e.g. business, leisure)


*   **cabin**: Cabin at the flight date flown: Flight date

*  **seatcomfort**: Rated between 1-5


*   **cabin service**: Rated between 1-5

*   **foodbev**: Rated between 1-5 entertainment: Rated between 1-5


*   **groundservice**: Rated between 1-5

*   **valueformoney**: Rated between 1-5

## **Feature descriptions briefly as follows:**


*   **airline**: Name of the airline in str fromat

*   **overall**: Overall point is given to the trip between 1 to 10 in float format.


*   **author**: Author of the trip in str format


*   **reviewdate**: Date of the Review customer review: Review of the customers in free text format in str need to be converted into DateTime Format



*  **aircraft**: Type of the aircraft in str format

*   **travellertype**: Type of traveler (e.g. business, leisure) consist of four class in str format 


*   **cabin**: Cabin at the flight date flown: Flight date in str format consist of 4 class.

*  **seatcomfort**: Rated between 1-5 in float format


*   **cabin service**: Rated between 1-5 float format

*   **foodbev**: Rated between 1-5 entertainment: Rated between 1-5 in float format


*   **groundservice**: Rated between 1-5 in float format

*   **valueformoney**: Rated between 1-5 in float format





