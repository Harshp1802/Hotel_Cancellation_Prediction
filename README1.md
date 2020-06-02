# Exploratory Data Analysis and then predicting cancellations of bookings from a Hotel Bookings Dataset:

**Exploratory Data Analysis**: A statistical approach to analyze the dataset to summarize the essential information, generally, using visual methods. 
* Data Visualisation included:
  * Statistics: Mean, Standard Deviation, Count of various features of the dataset.
  * Barplot for the no. of Cancelled bookings for each hotel type.
  * Barplot for analyzing the month-wise Booking-cancellations
  * Barplot for the peak period of bookings (Month wise)
  * Month wise canceled Bookings
* Correlation between all the variables and the cancellation of the bookings.
* Data Processing:
  * Removed various columns which had enough number of NULL entries.
* Created dummy variables to be used in th prediction model.
* Basic Steps for the model:
  * Split into training and test sets
  * Feature Scaling
  * Trained and predicted using multiple models: Used LogisticRegression and KNearestNeighbors
  * Used sklearn library for the models.
* KNearestNeighbors algorithm stores all the training data and then classifies a new data point based on the similarities.
