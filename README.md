# **CODE-ALPHA-Machine-Learning-Intern-Task-02**

# Stock Price Prediction with LSTM

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data Preparation](#data-preparation)
- [Data Analysis](#data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Stock price prediction is an excellecnt task in the field of Ml/DS. This project uses LSTM, a type of deep learning model, to predict stock prices based on historical data. The LSTM model is designed to capture temporal dependencies in stock price movements.

## Getting Started

### Prerequisites

Before you begin, make sure you have the following installed:

- Python
- Jupyter Notebook (for running the code)
- Required libraries and packages (see the code for the list). Code is available in the `CODE_ALPHA_Task02_Stock_Price_Prediction.ipynb` file

### Installation

1. Clone the repository to your local machine:

   ```bash
   https://github.com/DS-Ali-Arshad/CODE-ALPHA-Machine-Learning-Intern-Task-02.git
   ```

2. Install the necessary Python packages using `pip`:

   ```bash
   pip install -r requirements.txt
   ```

## Data Preparation

The project uses historical stock price data from the KSE 100 index in Pakistan. The dataset is provided in the 'Dataset' folder.

## Data Analysis

The data is analyzed to understand its structure, missing values, and basic statistics. Visualizations are used to explore the data.

## Data Preprocessing

Data preprocessing steps include:
- Data type conversion
- Data sorting by date
- Handling duplicate records
- Scaling the data
- Creating datasets for training and testing

## Model Building

LSTM models are used for stock price prediction. The models are designed with multiple LSTM layers and dropout layers to prevent overfitting. The models are trained using the preprocessed data.

## Model Evaluation

The performance of the LSTM models is evaluated using root mean squared error (RMSE). Training and testing errors are compared to assess model accuracy.

## Results

The project provides predictions for stock prices based on the trained LSTM models. The results are rescaled to their original scale for better understanding and visualization, available in the `CODE_ALPHA_Task02_Stock_Price_Prediction.ipynb` file.

## Conclusion

Stock price prediction is a complex task, and the results may vary based on the dataset and model architecture. This project serves as a starting point for understanding and implementing LSTM-based stock price prediction.

## Contributing

If you would like to contribute to this project or have suggestions for improvement, please feel free to create an issue or a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
