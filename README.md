# FoodHub Order Analysis

## Part of MIT IDSS's "Data Science and Machine Learning: Making Data-Driven Decisions" program


### Context

This project involves analyzing the data of a hypothetical food-ordering app called "FoodHub". The app allows the restaurants to receive
a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant.
The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person,
he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after
delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants.

### Objective

The goal of the project is to analyze FoodHub's data for a given period of time, in order to get a fair idea about the demand of different restaurants, as this may help them in enhancing their
customer experience.

### Data Dictionary

- `order_id`: Unique ID of the order
- `customer_id`: ID of the customer who ordered the food
- `restaurant_name`: Name of the restaurant
- `cuisine_type`: Cuisine ordered by the customer
- `cost`: Cost of the order
- `day_of_the_week`: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
- `rating`: Rating given by the customer out of 5
- `food_preparation_time`: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's - pick-up confirmation.
- `delivery_time`: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information

### Techniques applied

Data cleaning and exploratory data analysis (histograms, boxplots, etc.)  

### Dependecies 

- numpy
- pandas
- matplotlib.pyplot
- seaborn as sns

### Using the code

Please make sure to save the Jupyter Notebook (*.ipynb*) file and the dataset in the same directory.
