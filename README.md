# Charity-Funding-Predictor

Overview: The ourpose of this analysis is to ascertain whether or not charity funding will be successful.
Data Preprocessing:
  Targets: IS_SUCCESSFUL
  Features: CLASSIFICATION, APPLICATION_TYPE
  Neither: EIN, NAME were removed
Compiling, Training, and Evaluating the Model:
  Neurons, layers, activation functions: 
    Neurons: 80/30, 80/30/20, 80/30/50
    Layers: 2/3/3
    Activation Functions: relu/selu
    Epochs: 100/250/1000
  Able to achieve target model performance: No
  Steps to increase accuracy: Different neurons, layers, activation types, increased epochs
