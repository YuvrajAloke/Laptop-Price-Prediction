

# Laptop Price Prediction

This project focuses on predicting laptop prices using machine learning models. The analysis involves exploring a dataset of laptops, processing the data, and building a regression model to predict prices based on various laptop features, such as brand, processor, RAM, and storage.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Data Description](#data-description)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

The goal of this project is to develop a machine learning model that can accurately predict the price of a laptop based on its specifications. The dataset includes key features such as laptop brand, processor type, RAM, storage capacity, and screen size. By analyzing these features, we aim to uncover the most significant factors influencing laptop prices and use them to build a predictive model. This tool can be useful for consumers, retailers, or analysts looking to estimate the market value of different laptop models.

## Project Structure

The repository consists of the following files:

- **laptop_price.csv**: This file contains the raw laptop dataset, including various technical specifications and their corresponding prices.
- **Laptop Price Prediction.ipynb**: This Jupyter notebook contains the Python code used to process the data, perform feature engineering, and build machine learning models for price prediction.

## Data Description

The laptop dataset contains multiple features related to laptop specifications. Some of the key columns include:

- **Brand**: The manufacturer of the laptop (e.g., Dell, HP, Lenovo).
- **Processor**: Type of processor (e.g., Intel i5, Ryzen 5).
- **RAM**: Size of the RAM in GB.
- **Storage**: The type and size of storage (e.g., 256GB SSD, 1TB HDD).
- **Screen Size**: Size of the laptop screen in inches.
- **Price**: The target variable, representing the price of the laptop.

## Usage

To run the project and predict laptop prices:

1. Clone this repository:
   ```bash
   git clone https://github.com/CRYODRAKON2/Laptop-Price-Prediction.git
   cd laptop-price-prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook and execute the cells to preprocess the data, train the model, and make predictions:
   ```bash
   jupyter notebook notebooks/Laptop Price Prediction.ipynb
   ```

4. Alternatively, you can load the pre-trained model and use it for predictions directly.

Key sections in the notebook:
- *Data Cleaning*: Handling missing or inconsistent data, converting data types.
- *Exploratory Data Analysis (EDA)*: Visualizing relationships between features like brand, processor, RAM, and laptop price.
- *Model Training*: Building and training regression models to predict laptop prices based on their features.

## Results

The trained machine learning model was able to predict laptop prices with an accuracy of `85%`. The most influential factors identified by the model include brand, processor type, RAM, and storage size.

Some of the key insights from the analysis:
- **Brand and processor** are strong predictors of laptop prices, with premium brands and high-end processors leading to higher prices.
- Laptops with larger RAM and storage capacities tend to be priced higher, though the impact varies depending on the brand and model.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
