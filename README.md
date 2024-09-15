# Transaction Analysis

## Description

This project analyzes customer transactions using a dataset from Kaggle. The analysis includes data cleaning, visualization, and statistical analysis to derive insights from the transaction data.

## Installation

To set up this project, follow these steps:

1. **Clone the repository**:

    ```sh
    git clone https://github.com/prkshayush/transaction-analysis.git
    cd transaction-analysis
    ```

2. **Install the required packages**:
    Ensure you have Python installed. Then, install the necessary packages using pip:

    ```sh
    pip install kaggle pandas matplotlib seaborn
    ```

3. **Download the dataset**:
    Ensure you have the Kaggle API installed and configured. Then, download the dataset:

    ```python
    import kaggle
    !kaggle datasets download bkcoban/customer-transactions -f sample_dataset.csv
    ```

## Usage

To run the analysis, open the `transaction-analysis.ipynb` Jupyter Notebook and execute the cells in order. The notebook will guide you through the data loading, cleaning, visualization, and analysis steps.
