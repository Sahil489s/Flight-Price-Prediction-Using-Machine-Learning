# Flight-Price-Prediction-Using-Machine-Learning
## Overview
This project is designed to predict flight prices using machine learning techniques. By analyzing a dataset of flight information, such as airline, departure time, arrival time, and other key factors, this model aims to provide accurate predictions for the cost of flights.

## Key Features
- **Data Preprocessing**: Includes handling missing values, converting categorical data, and feature scaling.
- **Model Training**: Utilizes regression models to predict flight prices.
- **Evaluation Metrics**: Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score for assessing model performance.
## Dataset
The dataset used in this project consists of flight details that include:
- **Airline**: Name of the airline.
- **Source**: Starting location of the flight.
- **Destination**: Arrival location of the flight.
- **Date and Time**: Scheduled departure and arrival times.
- **Duration**: Total time taken by the flight.

Ensure to place the dataset file in the designated `data/` directory.

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook flight_price_prediction.ipynb
   ```
2. Run all the cells sequentially to see data exploration, model training, and prediction results.
3. Adjust model parameters or preprocessing steps to customize the prediction workflow.

## Model Details
- **Algorithms**: Uses models such as Linear Regression, Decision Tree, and Random Forest.
- **Feature Engineering**: Includes extraction of day, month, and hour from timestamp data and encoding categorical variables.

## Results
The best-performing model achieved an R-squared score of approximately 0.85 on the test set, indicating a reliable predictive capability.

## Future Work
- Experiment with more advanced models like XGBoost or ensemble techniques.
- Improve hyperparameter tuning to further optimize model performance.
- Deploy the model using a platform such as Flask or FastAPI for real-time prediction.

## Contributing
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

## Contact
For any questions or feedback, please contact:
- **Sahil Sharma**  
- [LinkedIn](https://linkedin.com/in/sahil-sharma489)  
- [GitHub](https://github.com/Sahil489s)
