# DottoreBayes
This is an algorithm based on Bayes' theorem, widely used for forecasting future data.

This simplified version accepts only Boolean data and still requires optimization.

### How to use

Use the "treinar" function to train your model with historical data; the first parameter expects the predictor data, and the second expects the results.

After training, the algorithm will return an object containing the learned information; you can use this with the "previsao" function to test against the data to be predicted: the first parameter expects the predictive data, and the second receives the learning object produced by "treinar".
