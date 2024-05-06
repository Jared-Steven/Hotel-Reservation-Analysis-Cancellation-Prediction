# Hotel Reservation Analysis & Cancellation Prediction

## Overview

This project involves the analysis of hotel reservation data obtained from Kaggle. The dataset contains booking information for both a city hotel and a resort hotel, including details such as booking dates, length of stay, number of guests, and more. The primary objective is to perform exploratory data analysis (EDA) and build a machine learning model to predict hotel booking cancellations.

## Dataset

The dataset used in this project is sourced from Kaggle and can be found at the following link:
- [Hotel Booking Demand Dataset](https://www.kaggle.com/jessemostipak/hotel-booking-demand)

## Code Details

The code is provided in the Jupyter Notebook format (`Hotel_Reservation_Analysis_&_Cancellation_Prediction.ipynb`). It's developed using Python and utilizes various libraries such as Pandas, NumPy, Matplotlib, Plotly, Folium, and Scikit-learn.

### Dependencies

To run the code, ensure you have the following dependencies installed:
- `folium`
- `squarify`
- `sorted-months-weekdays`
- `sort_dataframeby_monthorweek`

These dependencies can be installed using pip, as demonstrated in the notebook.

### Code Workflow

The notebook follows a structured workflow:

1. Data Loading and Exploration:
   - Loading the dataset and initial exploration.
   - Checking for missing values and handling them.
   - Exploring key features such as meal preferences, special requests, etc.

2. Data Cleaning and Preprocessing:
   - Handling missing values by imputation.
   - Filtering out irrelevant data.
   - Encoding categorical variables for model training.

3. Exploratory Data Analysis (EDA):
   - Analyzing booking patterns, guest preferences, and market segments.
   - Visualizing trends in room prices, stay durations, and seasonal variations.

4. Machine Learning Model:
   - Splitting the data into training and testing sets.
   - Feature scaling for model training.
   - Building a Decision Tree Classifier for predicting booking cancellations.

5. Model Evaluation:
   - Evaluating model performance using accuracy, confusion matrix, and classification report.
   - Visualizing the decision tree model for interpretability.

## Usage

To run the notebook, follow these steps:
1. Install the required dependencies using pip.
2. Download the dataset from the provided Kaggle link.
3. Update the notebook with the correct file path to the dataset.
4. Execute each cell in the notebook sequentially to perform data analysis and model building.

## Conclusion

The analysis provides insights into hotel booking trends, guest preferences, and factors influencing booking cancellations. The machine learning model offers a predictive framework for anticipating cancellations, enabling hotel management to optimize operations and enhance customer satisfaction.

For detailed implementation and results, refer to the notebook.

