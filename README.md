# House-Price-Prediction
This project predicts house prices based on various features using a machine learning model. The dataset includes attributes like location, size, total area, and more. The model is built using Python and scikit-learn.

Table of Contents
Project Overview
Technologies Used
Dataset Description
Installation
Usage
Results
Contributing
License

Project Overview
House prices can be influenced by various factors such as location, size, number of bathrooms, and more. This project utilizes linear regression to analyze these factors and make predictions based on historical data.

Technologies Used
Python 3.x
Libraries:
  pandas
  numpy
  scikit-learn
  matplotlib (optional for visualizations)

Dataset Description
The dataset contains the following columns:

area_type: Type of area (e.g., Built-up Area, Plot Area)
availability: Availability status (Ready to move/Under construction)
location: Location of the property
size: Number of bedrooms (e.g., 2 BHK)
total_sqft: Total area in square feet
bath: Number of bathrooms
balcony: Number of balconies
price: Price of the property (target variable)
Null Value Handling:
size: Replaced null values with the most frequent category.
bath: Replaced null values with the median.
balcony: Replaced null values with the median.
