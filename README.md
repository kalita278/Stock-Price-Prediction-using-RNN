# Stock-Price-Prediction-using-RNN

**PROJECT OBJECTIVE:** Build a RNN model to predict the opening stock price of google.

**DATA PREPROCESSING:**

Here, used Minmax scaler to scale the data and created a data structure to 60 timestamps and 1 output. Since RNN takes 3d input, converted the array into 3d array.

**MODEL BUILDING AND TRAINING THE MODEL:**

  Build the RNN model with 50 neurons and 4 LSTM layers. Here, used 'adam' and mean-squared-error' as optimizer and loss function.

  Used 100 epohs and 32 as batch size to train the model.
