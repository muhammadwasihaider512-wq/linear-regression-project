# Linear Regression Project

## Project Overview
This project implements Linear Regression on two different datasets using Python and Scikit-learn. It includes data preprocessing, model training, performance evaluation, and user interfaces using Gradio and Flask.

## Project 1: House Price Prediction
- **Dataset:** House Price Dataset
- **Algorithm:** Linear Regression
- **Purpose:** To predict house prices using property features.
- **Features:** Overall Quality, Living Area, Garage Cars, and Total Basement Area.
- **Evaluation Metrics:** MAE, MSE, RMSE, and R² Score.
- **User Interfaces:** Gradio and Flask.

## Project 2: Auto MPG Prediction
- **Dataset:** Auto MPG Dataset
- **Algorithm:** Linear Regression
- **Purpose:** To predict vehicle fuel efficiency in miles per gallon (MPG).
- **Features:** Cylinders, Displacement, Horsepower, Weight, Acceleration, Model Year, and Origin.
- **Preprocessing:** Missing numerical values are handled using median imputation.
- **User Interfaces:** Gradio and Flask.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Gradio
- Flask

## Installation
Install the required Python libraries using:

```bash
pip install pandas numpy scikit-learn matplotlib gradio flask
```

## How to Run
1. Download or clone this repository.
2. Install the required libraries.
3. Keep each dataset in the appropriate folder with the correct filename.
4. Open the relevant Jupyter Notebook in Jupyter Notebook.
5. Run the notebook cells in order.
6. Alternatively, run the Python scripts if available.
7. Use the Gradio or Flask interface to enter input values and obtain predictions.

## Repository Files
- `House Price.ipynb` — House price regression notebook.
- `auto-mpg.ipynb` — Auto MPG regression notebook.
- `House price dataset.csv` — House price dataset.
- `auto-mpg.csv` — Auto MPG dataset.

## Conclusion
This project demonstrates how Linear Regression can be applied to two different prediction problems: house price prediction and vehicle fuel-efficiency prediction. It also demonstrates the use of Gradio and Flask to create user interfaces for machine-learning models.
