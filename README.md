Hi all,

I could not quite wrap my head around CNN's, so I decided to build one from scratch using an object oriented approach in Java, without the use of any libraries(Pytorch, TF, etc). 

First I wrote the classes for processing data, including the Image and DataReader class. The actual network uses an abstract Layer class, and then is extended by a Convolution Layer, Max Pooling Layer, and a Fully Connected Layer. To make this all usable, I built the Network Builder and Neural Network classes. 

I trained the model on the MNIST dataset and got a success rate of about 90% in three epochs. 

To run this code, download the MNIST dataset as a CSV from here:
https://pjreddie.com/projects/mnist-in-csv/
And then replace the filepath variables accordingly in the main function.

This code is heavily inspired by the youtube series below:
https://youtu.be/3MMonOWGe0M

