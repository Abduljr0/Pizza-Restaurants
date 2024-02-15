# Flask Pizza Restaurants API

This is a Flask-based API for managing pizza restaurants and their pizzas. It allows users to perform CRUD operations on restaurants and associate pizzas with them.

## Setup

1. **Clone the Repository:**

   ```bash
   git clone <repository_url>
   cd <repository_name>

## Install dependencies

pipenv install
npm install --prefix client

## Run Flask API

python app.py

## Run React Frontend

npm start --prefix client

# Routes

- **GET /restaurants**: Retrieve a list of all restaurants.
- **GET /restaurants/:id**: Retrieve details of a specific restaurant by ID.
- **DELETE /restaurants/:id**: Delete a restaurant by ID.
- **GET /pizzas**: Retrieve a list of all available pizzas.
- **POST /restaurant_pizzas**: Create a new association between a pizza and a restaurant.

# Models

- **Restaurant**: Represents a pizza restaurant with attributes like ID, name, and address.
- **Pizza**: Represents a type of pizza with attributes like ID, name, and ingredients.
- **RestaurantPizza**: Represents the association between a restaurant and a pizza with attributes like ID, restaurant ID, pizza ID, and price.

# Validation

- **Price Validation**: The price of a restaurant pizza must be between 1 and 30.

# Testing

- **Run Tests**:

  You can run tests to ensure the API endpoints are functioning correctly:

  ```bash
  pytest -x

Authored by [Abdiqani Adan ](https://github.com/Abduljr0)
license MIT
