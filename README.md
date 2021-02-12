## Metis_project3: predicting flight delay
### Description:
Being stranded at the airport is one of those horrible experiences (tiredness, frustration, and boredom) we all want to avoid (I once got stuck at the airport overnight, and I never booked with the same airline again). Moreover, if we are traveling on a tight business schedule, we would want to have more control over our schedule. This project is trying to build a model that predicts flight delay so travelers could better plan their trips.

![ ](https://github.com/sarazong/Metis_project3/blob/main/images/flight_delay.jpg)

### Features:
- Date 
- Airlines
- Origin airport
- Destination airport
- Scheduled departure
- Scheduled arrival
- Airtime
- Distance
- Incoming fligths per airport per day
- Interactions of incoming flights and scheduled arrival

### Target:
Arrival delay >= 15mins

### Data Used:
Flight performance data from [link](https://www.transtats.bts.gov/DL_SelectField.asp?Table_ID=236&DB_Short_Name=On-Time)

### Tools Used:
- numpy
- pandas
- Matplotlib
- scikitlearn

### Possible impacts of your project:
Travelers could better plan their trips using the model to predict whether their flights would result in delay or not.
