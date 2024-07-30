# House Price Prediction in Tehran

## Overview

This project aims to predict house prices in Tehran using a machine-learning approach. The dataset includes various features that might influence house prices, and the analysis is conducted using Python in a Jupyter Notebook.

## Files

- `housePrice.csv`: This file contains the dataset used for the project. It includes various features such as location, size, number of rooms, and other relevant attributes.
- `TehranPricePrediction.ipynb`: This Jupyter Notebook contains the code for data preprocessing, exploratory data analysis, model training, and evaluation.

## Requirements

To run the code in this project, you will need the following Python packages:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn


## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook TehranPricePrediction.ipynb
```

4. Run the cells in the notebook to see the data analysis, model training, and predictions.

## Project Structure

The project is structured as follows:

```
house-price-prediction/
│
├── housePrice.csv
├── TehranPricePrediction.ipynb
├── README.md
└── requirements.txt
```

## Data Description

The dataset `housePrice.csv` includes the following columns (example columns, adjust as per your dataset):

- `id`: Unique identifier for each house
- `location`: The neighbourhood or area of Tehran
- `size`: Size of the house in square meters
- `rooms`: Number of rooms
- `price`: The price of the house

## Model and Evaluation

In the Jupyter Notebook, we:

1. Load and preprocess the data
2. Conduct exploratory data analysis (EDA) to understand the data better
3. Train multiple machine learning models to predict house prices
4. Evaluate the models and select the best one based on performance metrics

## Contributing

If you wish to contribute to this project, please create a new branch and submit a pull request.

## License

This project is licensed under the MIT License.


