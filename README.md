# House Rent Prediction Using LSTM Model

Predicting house rent is a challenging yet rewarding task, and this project employs Long Short-Term Memory (LSTM) model to forecast rental prices. The dataset includes features such as location, square footage, number of bedrooms, etc., and the target variable is the rental price.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Model Building](#model-building)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to predict house rent prices using a specialized LSTM model. LSTM is a type of recurrent neural network (RNN) capable of handling sequential and time-series data effectively. The dataset is preprocessed to accommodate LSTM's input requirements, and the model is trained and evaluated to forecast house rent values.

## Prerequisites

To run this project, ensure you have Python and the following libraries installed:

- pandas
- numpy
- scikit-learn
- TensorFlow
- matplotlib
- plotly
- jupyter

You can install them using the following command:

```bash
pip install pandas numpy scikit-learn tensorflow matplotlib seaborn jupyter
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Mohshaikh23/House-Rent-Prediction.git
cd house-rent-prediction
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

## Usage

The Jupyter Notebook in this repository contains the code for data preprocessing, LSTM model building, and evaluation. Open the notebook and follow the step-by-step instructions to run the code and observe the results.

## Model Building

The project utilizes TensorFlow to build an LSTM model suitable for sequential data like house features over time. The dataset is split into training and testing sets. The LSTM model is trained using the training data, and its performance is evaluated on the testing data.

## Results

The trained LSTM model's performance is evaluated using metrics like Mean Squared Error (MSE) and Root Mean Squared Error (RMSE). The predictions are visualized using line plots to compare the model's predictions with the actual house rent prices.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you find any issues or have suggestions for improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

