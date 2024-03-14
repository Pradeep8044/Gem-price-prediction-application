# Gemstone Price Prediction Application

This application predicts the price of gemstones based on various attributes such as carat, depth, table, dimensions (x, y, z), cut, color, and clarity. It utilizes a machine learning model trained on a dataset of gemstone attributes and corresponding prices.

## Features

- Predicts the price of gemstones based on user-provided attributes.
- Provides a simple web interface for inputting gemstone attributes and viewing the predicted price.
- Supports both manual input through a web form and API-based prediction.

## Getting Started

To use this application locally, follow these steps:

1. Clone this repository to your local machine:


2. Install the required dependencies by running:


3. Run the Flask application:


4. Access the application in your web browser at `http://localhost:8000`.

## Usage

- Input the attributes of the gemstone (carat, depth, table, dimensions, cut, color, clarity) into the provided form fields.
- Click the "Submit" button to predict the price of the gemstone.
- View the predicted price displayed on the web page.

## API Usage

- Send a POST request to `/predictAPI` endpoint with gemstone attributes in JSON format.
- Receive the predicted price in the response.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

