# Jet Engine Thrust Prediction Using Artificial Neural Networks

This project presents a MATLAB-based artificial neural network study for jet engine thrust prediction. The model uses altitude, temperature, Mach number, and fuel flow as input variables to estimate engine thrust.

## Project Objective

The main objective of this study is to evaluate different feedforward backpropagation neural network topologies for jet engine thrust prediction and identify the best-performing model based on test MSE.

## Input and Output Variables

The neural network model uses the following input variables:

- Altitude
- Temperature
- Mach number
- Fuel flow

The output variable is:

- Thrust

## Methods Used

- MATLAB
- Artificial Neural Networks
- Feedforward Backpropagation Network
- Data normalization
- Training and test data split
- Neural network topology comparison
- Performance metric evaluation

## Model Development

A total of 12 neural network topologies were compared by changing:

- Training function
- Transfer function combination
- Hidden layer neuron number

For each topology, the hidden layer neuron number was scanned from 1 to 50. The best structure was selected based on the minimum test MSE.

## Performance Metrics

The models were evaluated using:

- MSE
- MAE
- R
- MAPE

## Key Results

The best model was obtained with:

- Training function: trainoss
- Transfer function combination: tansig - purelin
- Hidden layer neuron number: 1
- Test MSE: 27.7742
- Test R: 0.9978
- Test MAPE: 2.9420%

The results show that artificial neural networks can successfully model nonlinear jet engine thrust behavior using flight and engine operating parameters.

## Repository Content

```text
report/
├── jet_engine_thrust_prediction_ann_portfolio_full.pdf
└── jet_engine_thrust_prediction_ann_portfolio_full.docx
