# House Price Prediction Using Deep Learning

This project is a regression model designed to predict house prices. It utilizes an autoencoder for feature extraction and a 5-layer deep learning Convolutional Neural Network (CNN) to generate price predictions based on the extracted features.

## Project Structure
- **Feature Extraction**: An autoencoder is used to reduce dimensionality and extract important features from the input data.
- **Deep Learning Model**: The extracted features are fed into a 5-layer CNN, which is trained to perform regression and predict house prices accurately.

## Requirements

The project requires the following Python libraries:
- `pandas`
- `scikit-learn`
- `torch`
- `scipy`
- `matplotlib`

These libraries are specified in the `requirements.txt` file.

## Installation

1. **Clone the repository**:
   ```bash
   git clone <https://github.com/Joanmascastella/House-Price-Predictor>
   cd <house-price-predictor>

2. **Install Requirements**:

    Use the requirements.txt file to install all necessary libraries:
    
    ```bash
       pip install -r requirements.txt