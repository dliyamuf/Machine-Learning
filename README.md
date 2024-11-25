# Model
The machine learning model comes in two features: crops classification and price prediction. The classification of crops using Artificial Neural Network (ANN) and the architecture of crops price prediction using Long-Short Term Memory (LSTM).
## Crops Classification
### Dataset
Because of limitation of local dataset, we use open access Indian crops dataset from [Kaggle](https://www.kaggle.com/datasets/siddharthss/crop-recommendation-dataset) to trained the model. The dataset contains 22 crops category as a label.

## Price Prediction
### Dataset
Because of limitation of local dataset, we collect crops price data of each crops category from [Indian Ministry of Agriculture](https://agmarknet.gov.in/) to trained the model. The dataset collected is range from 15 March 2021 until October 2024. We predict the crops price until the next three month from the time range trained model because it does not have public API access.

# Requirements
- Python
- Jupyter Notebook, we use Google Colab for this project
- Tensorflow 2.x
- Tensorflow.keras
- Pandas
- Matplotlib
- Numpy
- os
- zip

