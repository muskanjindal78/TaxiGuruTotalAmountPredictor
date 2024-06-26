# Taxi Fare Guru: Total Amount Prediction Challenge

**Dataset Description**
Develop predictive models to estimate the total amount paid by travelers for taxi rides.

**Dataset Overview**
This dataset presents an opportunity to construct predictive models aimed at estimating the total amount paid by travelers for taxi journeys. With access to a training set containing the target variable 'total_amount' along with various informative features, participants are challenged to create accurate predictive models.

**Data Files**
The dataset is composed of the following files:

**train.csv**: The training set, which includes the target variable 'total_amount' and accompanying feature attributes.

**test.csv**: The test set, containing similar feature attributes but without the target variable 'total_amount,' as it is the variable to be predicted.

**sample_submission.csv**: A sample submission file provided in the correct format for competition submissions.

**Columns Description**

The dataset comprises various columns, each offering valuable insights into taxi rides. Notably:

**total_amount**: The total amount paid by the traveler for the taxi ride.

**VendorID**: An identifier for taxi vendors.

**tpep_pickup_datetime** and **tpep_dropoff_datetime**: Timestamps indicating pickup and dropoff times.

**passenger_count**: The number of passengers during the ride.

**trip_distance**: The distance traveled during the trip.

**RatecodeID**: Rate code for the ride.

**store_and_fwd_flag**: A flag indicating whether the trip data was stored and forwarded.

**PULocationID** and **DOLocationID**: Pickup and dropoff location identifiers.

**payment_type**: Payment type used for the ride.

Other columns are self-explanatory and contribute to the modeling process.

**Submissions are evaluated on R2 score**

## Prediction Scores (Highest to lowest)


**Random Forest** - 0.94027

**Bagging Random Forest** - 0.93904

**Bagging Regressor** - 0.93904

**Decision Tree Regressor** - 0.89311

**Decision Tree** - 0.89001

**KNN** - 0.27786

**Linear Regression** - -0.70935
