# Convolutional-neural-network-project

Convolutional Neural Networks:

Image recognition and classification. It is absolutely incredible how this world is changing and evolving. CNN is absolutely fascinating, few years back you would have to tag your friends on a Facebook picture post one by one, and now thanks to CNN it is done automatically.

Step 1) Convolution:
	Input Image (X) Feature Detector  = Feature Map

	ReLu layer. The reason why we are applying the rectifier is because we want decrease the linearity in our CNN., and that is because images themselves are nonlinear.

Step 2) Pooling or downsampling:

Max pooling Is used to assist in recognizing for instance a lion image no matter what the situation is, the lightening, the rotation etc. In pooling we are able to preserve the features, and moreover, we are reducing the number of parameters that are going through our final layer of the CNN and therefore are preventing overfitting.

Step 3) Flattening:

In this step we “flatten” all the pieces we received from the pooling step in preparation for being passed to the input layer of the NN

Step 4) Full connection:

Is a fully connected NN where all the features are processed and in the final layer which performs the voting towards the classes we are after. All this is trained through forward and backward propagation, and lots of iterations and epochs. Not only the weights are trained but also the feature detectors and adjusted in the gradient descent process, and in the end we get a CNN which can recognize images and can classify them.



The CNN code implementation:

1)	I start by importing the required libraries.
2)	Then in the data preprocessing phase. Since this time our dataset (training set and test set) will be images, I am doing feature scaling (which is compulsory for neural networks) using ImageDataGenerator and the rest are the transformations that will perform image augmentation to prevent over fitting. I then import the dataset and filling the parameters of the train_datagen object and I modified the numbers a lot in order to eventually get good results in a decent time.
3)	Following that, I pretty much implement the steps discussed earlier in the intuition section.





This is a 'basic' project to train the cnn to classify pictures of dogs and cats.

