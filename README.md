# New York City Taxi and Limousine Data Analysis

## Overview

This repository contains the code and documentation for analyzing New York City Taxi and Limousine data using Apache Spark. The project is divided into three main parts: Data Ingestion and Preparation, Business Questions Analysis, and Machine Learning for Fare Prediction.

## Contents

- `data_preparation.py`: Python script for data cleaning, preprocessing, and merging datasets.
- `business_questions_analysis.py`: Python script for analyzing business questions related to taxi trips.
- `machine_learning_fare_prediction.py`: Python script for taxi fare prediction using Spark ML.
- `data/`: Folder containing the raw and cleaned datasets.
- `results/`: Folder for storing analysis results and machine learning predictions.
- `README.md`: Documentation providing an overview of the project and instructions.

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/nyc-taxi-analysis.git
    cd nyc-taxi-analysis
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the scripts:

    - For data preparation:

        ```bash
        python data_preparation.py
        ```

    - For business questions analysis:

        ```bash
        python business_questions_analysis.py
        ```

    - For machine learning fare prediction:

        ```bash
        python machine_learning_fare_prediction.py
        ```

## Results

- Data cleaning and preparation results are stored in the `results/cleaned_data` directory.
- Business questions analysis results are saved in the `results/business_analysis` directory.
- Machine learning fare predictions for Q4 2022 are stored in the `results/machine_learning_predictions` directory.

Feel free to explore the code and adapt it to your specific requirements.

## References

- [New York City Taxi and Limousine Commission](https://www.nyc.gov/taxi)
- [Apache Spark Documentation](https://spark.apache.org/docs/latest/)
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/documentation.html)
