# Regression_Project
**Problem Statement**

The train transportation system is not well developed in Kenya so people have to rely on the bus or shuttle service and hence the travel time increases automatically. Here the problem statement is regarding the prediction of the demand of transportation by bus or shuttle to various cities from Nairobi so that the only transporatation system that is well developed can be utilized optimally.

**Data Description**
The data contains 51645 rows × 10 columns. As same ride was booked my mutiple persons after counting the bookings for same rides the data rows were reduced to 6249 rows

ride_id	: ID of the ride 
seat_number	: seat number booked or assigned
payment_method	
payment_receipt	
travel_date	: Date of travelling
travel_time	: Time of travel
travel_from	: city of origin
travel_to	: Nairobi
car_type	: Bus or shuttle
max_capacity : Maximum capacity of the medium of travel

**Exploratory Data Analysis**

More number of bookings were made from the city Kissi to Nairobi in comparision to other cities. This may be due to greater economic dependence of kissi city on Nairobi or better human capital present in the kissi city.

In the month of december the bookings were the highest i.e. around 10000 which may be due to christmas or the New year.

Most tickets were booked for the wednesday. It may be due to the long journey hours and people after reaching to Nairobi in 1 or 2 days like to rest on saturdays and sundays and startoff their work on Monday.

Mbita has the farthest distance from Nairobi which is 401 kms.

**Approach:-**

EDA 

Feature Selection

Splitting Dataset into train and test set.

Choosing Models

Model Training.

Model Evaluation.

**Conclusion**

The gradient Boost Regressor and Random Forest Regressor have out performed the Multinomial Linear Regression. The prediction when done on adding the weekday variable to the data has shown high relaibility by showing high r2 score values. Hence, given the dataset and algorithms used the accuracy of regression increases exponentially when the weekdays are included as the independent variables while if we move on only with the month variable single handedly or go to the higher dimensions like quater the model does not perform well. Hence, the prediction here can be made weekwise for any given month in the year.
