# hotel_bookings
Analysis of Demand for Hotel Booking and Prediction of Hotel Booking's Cancellation

## Overview of The Project:
This project uses the End-to-End Pipeline of Machine Learning to analyze the demand for Hotel Bookings and estimate and predict their Confirmed stays and Cancelled bookings.This is to help a Hotel's Reservation System to decrease the revenue loss and better allocate rooms for future guests rather than to waste the time and revenue by expecting guests with high risks cancellation.This project is trained and tested by few Machine Learning Models in order to compare their performance for understanding the accurate model with the accuracy score for prediction of Cancelled Bookings.

## Link of Dataset:

The dataset used in this project is the **Hotel Booking Demand Dataset**.

Kaggle Dataset:
https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

The dataset contains information about hotel bookings including:
(i)Lead time
(ii)Check-in Date
(iii)Check-out Date
(iv)Guest Type (Adults, Children, Babies)
(v)Market Segment
(vi)All the Booking Modifications
(vii)Previous Cancellations

The target variable is: **is_canceled**

** 0 => Booking is confirmed**
** 1 =? Booking is cancelled**

## Data Exploration

(i)Described the Data from the Dataset
(ii)Summary of Data Structure, Size,
(iii)Checked and Counted the Missing Values
(iv)Checked the Duplicate Records (Rows)
(v)Data Visualization of Cancelled Bookings

## Data Preprocessing

(i)Handled the Missing Values
(ii)Removed Duplicate Records
(iii)Removed the Columns which causes Data Leakage

## Feature Engineering

(i)Used One-Hot Encoding Method to convert Categorical Variables (Text Values) into Numerical Values 
(ii)Defined the Input Features and Target Variable
(iii)The Dataset was split into two sets: Training Sets and Testing Sets
(iv)Implemented the Feature Scaling by using StandardScaler

## Machine Learning Models

To Train and Test the Data, following Machine Learning Algorithms were implemented:

(i)Decision Tree
(ii)K-Nearest Neighbors (KNN)
(iii)Logistic Regression
(iv)Naive Bayes
(v)Random Forest
(vi)Support Vector Machine (SVM)

## Model Evaluation

THe Machine Learning Models were evaluated using:

(i)Accuracy Score
(ii)Confusion Matrix
(iii)Classification Report
(iv)Feature Importance Analysis

## Model Selection

The **Random Forest Model** obtained the best and highest in terms of accuracy and performance for this Dataset. Its accuracy is 85.15%

Here, some of the most important influence factors for Booking Cancellations are:

(i)Lead Time
(ii)Country
(iii)Agent

## Technologies Used

(i)Jupyter Notebook
(ii)Scikit-Learn
(iii)Seaborn
(iv)Matplotlib
(v)Pandas
(vi)NumPy

## Conclusion

In Conclusion, this project shows and demonstrates how the Machine Learning Models can be implemented to predict the Hotel Bookings's Cancellation and by this prediction, Hotel's Reservation System can know beforehand about the possibility of Booking Cancellation in future and can manage revenue and room allocation much better.
