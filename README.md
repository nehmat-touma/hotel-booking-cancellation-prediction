# **Hotel Booking Demand Analysis**
## **Overview**
This project analyzes the "Hotel booking demand" dataset obtained from Kaggle. The dataset contains information about hotel reservations, including various characteristics such as booking status, average daily rate, lead time, and more.

## **Objective**
The primary objective is to predict whether a guest will cancel their reservation. The analysis involves descriptive analytics, machine learning, and feature selection.

## **Contents**
Dataset Description: Details about the dataset, its structure, and attributes.
Plots and Visualizations: Visual representations of data insights.
Methodology: Overview of the analytical approach, work division, and methodologies used.
Descriptive Analytics
The analysis includes:

- Heatmap depicting correlations between features.
- Distribution of canceled bookings.
- Guest distribution between City and Resort hotels.
- Monthly traffic of guests.
- Distribution of guests' countries of origin.
- Cancellations across months.
- Customer behavior analysis based on previous cancellations and guest history.
- Effect of lead time on cancellation.
- Effect of Average Daily Rate on repeated guests.
- Average Daily Rate per month.
- Effect of deposit type on cancellation.

## **Feature Engineering**
- Preprocessing
- Handling null values.
- Transformation of reservation date.
- Dropping unnecessary columns.
- Feature Selection
- Utilized Feature Importance based on ExtraTreesClassifier.
- Applied Recursive Feature Elimination (RFE) with Logistic Regression Estimator.

## **Machine Learning Models**
Implemented five machine learning algorithms:

1. Logistic Regression
2. K-Nearest Neighbors
3. Gradient Boosting Classifier
4. Random Forest Classifier
5. Support Vector Machine (SVM) Classifier
_Tuned hyperparameters for optimal model performance._

## **Results**
The **Random Forest Classifier** with Feature Importance and 15 features yielded the best results:

- F1 Score: 0.9433
- Accuracy: 0.948

## **Conclusion**
The project successfully predicts hotel reservation cancellations using machine learning. The final model achieved an F1 test score of 0.9355 and a test accuracy of 0.9414.

## **Dataset**
Hotel booking demand dataset from Kaggle https://www.kaggle.com/jessemostipak/hotel-booking-demand.
