# LeNet5 for MNIST digits classification

Simple implementation of LeNet5 (a classic CNN architecture) for digits classification from the MNIST dataset.
This dataset comes from the author of LeNet5, Yann Le Cun considered to be the godfather of CNN.
You can get this dataset freely online from Yann Le Cun website. For this project the training dataset size was 48k examples and i used a train-cross-validation split of 80-20. The test set size is 28k from the Kaggle competition. If you are training for another application I recommend using the full dataset and maybe reduce the split size to 85-15 or 90-10.

This project was created for the Kaggle introductory competition and is very simple. This is my first version to answer quickly to the classification task with a >98% accuracy on the cross validation set. Only 5 epochs are necessary for acceptable results, however longer training will probably yield better result.

The implementation of the model was done using Keras API on Tensorflow 2. Data was loaded by using the pandas library and visualisation of predictions are implemented with matplotlib to check our model outputs.

I may enhance the model at a later time to improve training set accuracy and reduce variance by implementing a regularisation tool. At test time it is also possible to imagine implementing several data augmentation techniques and use different model to score higher in the competition. My goal here was to create a quick and effective solution with a low inference time.

I hope this notebook can help someone. Please do not hesitate to point out issues or possible improvements.
