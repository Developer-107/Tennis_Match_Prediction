# Tennis Match Prediction using Neural Networks

This project predicts the winner of a tennis match using a neural network. The model is built with TensorFlow and trained on a dataset of ATP matches from 1968 to 2023.

Data
The data for this project was sourced from the tennis_atp repository on GitHub. It includes data on ATP matches from 1968 to 2023.

Model
The model is a sequential neural network built with TensorFlow. It has the following layers:

- Dense layer with 256 units and ReLU activation
- Dropout layer with a rate of 0.2
- Dense layer with 128 units and Leaky ReLU activation
- Dropout layer with a rate of 0.2
- Dense layer with 50 units and ReLU activation
- Dropout layer with a rate of 0.2
- Dense layer with 1 unit and sigmoid activation

The model is compiled with the Adam optimizer and binary cross-entropy loss function.

Results
The model achieved a test accuracy of 65.2%.

How to Use
To use this project, you will need to have Python and TensorFlow installed. You will also need to download the data from the [tennis_atp](https://github.com/JeffSackmann/tennis_atp) repository.

Once you have the data, you can run the notebook to train the model and make predictions.
