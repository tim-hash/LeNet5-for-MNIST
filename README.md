# LeNet5 for MNIST digits classification

Simple implementation of LeNet5 (a classic CNN architecture) for digits classification from the MNIST
dataset. This dataset comes from the author of LeNet5, Yann Le Cun considered to be the godfather of CNN.
This project was created for the Kaggle introductory competition and is very simple. This is a first and simple version
to answer quickly to the classification task with a >98% accuracy on the cross validation set. Only 5 epochs are necessary
for acceptable results, however longer training will probably yield better result.
The implementation of the model was done using Keras API on tensorflow 2. Data was loaded by using the pandas library and visualisation of
predictions are implemented with matplotlib to check our model outputs.
I may enhance the model at a later time to improve training set accuracy and reduce varaince by implementing a regularisation
tool. At test time it is also possible to imagine implementing several data augmentation techniaues and use different model to
score higher in the competion. My goal here was to create a quick and effective solution with a low inference time.
I hope this notebook can help someone. Please do not hesitate to point out issues or possible improvements.
