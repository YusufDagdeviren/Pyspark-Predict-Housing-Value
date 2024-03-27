# Tubitak Spark Proje - Yusuf Dagdeviren

This repository contains the code for a machine learning project using PySpark, which is part of the Tubitak Data Intensive Applications program. The project involves analyzing housing data and predicting median house values using a linear regression model.

## Project Overview

The project is structured as follows:

1. **Data Loading**: The housing dataset is loaded into a Spark DataFrame.
2. **Data Exploration**: The dataset is explored to understand its structure and to identify any missing or outlier values.
3. **Data Preprocessing**: Missing values are filled, categorical variables are one-hot encoded, and unnecessary features are dropped to prepare the data for machine learning.
4. **Model Training**: A linear regression model is trained on the preprocessed data.
5. **Model Evaluation**: The performance of the model is evaluated using Mean Absolute Error (MAE) and R-squared (R2) metrics.
6. **Prediction Visualization**: The actual vs. predicted values are visualized to assess the model's performance.

## Getting Started

To run the project, you will need to have PySpark installed in your environment. You can then clone this repository and run the Jupyter notebook file `Yusuf_Dagdeviren_Odev_4.ipynb`.

### Prerequisites

- Python 3.8 or higher
- PySpark

### Running the Project

1. Clone the repository to your local machine.
2. Open the `Yusuf_Dagdeviren_Odev_4.ipynb` file in Jupyter Notebook.
3. Run the cells in the notebook to execute the project.

## Project Structure

The main Jupyter notebook file `Yusuf_Dagdeviren_Odev_4.ipynb` contains the entire code for the project. It is organized into sections for data loading, exploration, preprocessing, model training, evaluation, and prediction visualization.

## Score Results
The model's performance was evaluated using Mean Absolute Error (MAE) and R-squared (R2) metrics. The results are as follows:  
- Training MAE: 52893.286336
- Training R2: 0.600788
- Testing MAE: 52964.474375
- Testing R2: 0.603208

These scores indicate that the model has a reasonable level of accuracy, with the R2 score suggesting that approximately 60% of the variance in the median house values can be explained by the model's features.

