# Digital Twin for Transport Planning

This repository contains the implementation and results of traffic prediction using various Recurrent Neural Network (RNN) models, including LSTM, GRU, RNN, and Bi-RNN, on a digital twin dataset for transport planning.

## Repository Structure

- **src/**  
  Contains the Python notebook with the code to run the digital twin dataset for transport prediction. The notebook implements four different models:
  - Long Short-Term Memory (LSTM)
  - Gated Recurrent Units (GRU)
  - Simple Recurrent Neural Network (RNN)
  - Bidirectional Recurrent Neural Network (Bi-RNN)
  
  The dataset used includes time series data for traffic prediction, with input features such as time, date, day of the week, and counts of different vehicle types.

- **results/**  
  Contains the generated results of the models in image format:
  - `Error_distribution.png`: Displays the error distribution across models.
  - `Learning_curves.png`: Learning curves for each model during training.
  - `Traffic Prediction Combined.png`: Combined traffic prediction results for all models.
  - `Traffic Prediction with Bi-RNN.png`: Prediction results using the Bi-RNN model.
  - `Traffic Prediction with GRU.png`: Prediction results using the GRU model.
  - `Traffic Prediction with LSTM.png`: Prediction results using the LSTM model.
  - `Traffic Prediction with RNN.png`: Prediction results using the RNN model.

## How to Run

1. Navigate to the `src/` folder.
2. Open the Python notebook in your preferred environment.
3. Follow the instructions in the notebook to preprocess the data and train the models.
4. After training, you can view the results in the `results/` folder.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- Pandas
- Numpy

Install the required packages using:

```bash
pip install -r requirements.txt
