# AlphabetSoup_Challenge

For the AlphabetSoup Challenge I went ahead and made the input layer equal to the number of variables in the dataframe and for the 1st hidden layer I added 24 neurons and for my second hidden layer I added 12 neurons. I then trained the model with 100 epochs and used the relu activation function for both hidden layers and sigmoid activation function for the ouput layer. After evaluating the model using the test data, I obtained an accuracy score of 74% which did not meet the target predictive accuracy of 75%. In order to try and increase model performance, I tried lowering the number of neurons on my hidden layers to 10 and 5 consecutively and also changed the number of epochs to 50. This did not help the accurancy score and actually fell 1% to 73%. I then tried other approaches such as changing the activation functions on my hidden layers from relu to sigmoid and tanh but that did help either. I the decied to add an additional hiddel layer with 6 neurons but that still kept me at 74%. At this point I would probabaly choose the LogisticRegression model in order to solve the classfication problem as it helps with binary probabilities. 
