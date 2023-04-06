# Oberoi REIT Stock Trend Prediction using LSTM

This project aims to predict the trend of the Oberoi REIT stock using LSTM (Long Short-Term Memory) neural network. The dataset was taken from Yahoo Finance for a period of 5 years (2018-2023) and was split into training and test sets with a proportion of 80% and 20% respectively. The project was built using Google Colab and implemented using the following libraries:

1) numpy
2) pandas
3) matplotlib
4) scikit-learn
5) keras

## Dataset

The dataset consists of daily opening prices of the Oberoi REIT stock for the period of 5 years (2018-2023). The data was preprocessed by scaling it using MinMaxScaler to bring all the values in the range of 0 to 1.

## Model Architecture
The LSTM neural network was used to predict the trend of the Oberoi REIT stock. The model consists of 3 LSTM layers, followed by a dropout layer and a dense layer with a single output. The input shape of the model is (timesteps, features), where timesteps is the number of time steps in a sequence and features is the number of features in the input data.

## Training and Testing
The dataset was split into training and test sets with a proportion of 80% and 20% respectively. The training set was used to train the model and the test set was used to evaluate the performance of the model. The model was trained using the Adam optimizer and the mean squared error loss function.

## Results
The predicted trend of the Oberoi REIT stock was plotted against the actual trend to visualize the performance of the model.

## Conclusion
This project demonstrates the use of LSTM neural network to predict the trend of the Oberoi REIT stock. The model achieved a good accuracy on the test set, indicating its potential use for real-world applications. The project can be further extended by incorporating more features into the input data and optimizing the model hyperparameters.
