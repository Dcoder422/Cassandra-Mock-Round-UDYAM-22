
# Machine Learning based Prediction of No. of Rental Bikes at each hour

Rental Bikes have entered many Urban Cities for enhancing the Mobility Comfort. Yet Accessibility and Availability of Rental Bikes at the Correct Time evolves as a Major Concern. These factors are often affected by the Atmospheric Conditions of the Area. Hence we were provided with a Dataset which entails Atmospheric Conditions of Urban Cities, based on this Data we had to predict the Number of Rental Bikes at each hour so that Supply and Demand go hand in hand.

Cassandra is a Data Science event of UDYAM, organised by Electronics Engineering Society IIT(BHU) Varanasi

This was a Mock Round before the Final Event and our first  Data Science Competition.

19th March 2022 to 26 March 2022
## 🔗 Links
[kaggle competion link here](https://www.kaggle.com/competitions/cassandra-mock-round)

Teamname : BinaryBeasts

## Techniques Used

- Data Exploration using Matplotlib kde plot and bar plot
- Used box plot for identifying outliers and then removed them
- Feature Engineering : Encoding Categorical Features
- Performed Target Encoding for "hour","Season" and "holiday" features
- One Hot Encoding for Working Day
- Catboost was used as predictive model and was hypertuned


