# cifar-10
This repo is for the classification of images in cifar-10 dataset.  
The dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class.   
There are 50000 training images and 10000 test images.  

Building the Neural Network :
Various models is been tried starting from a simple single layer , followed by complex layers containing Convolution layer and Maxpooling layers.  
Model accuracy , f1-score for each class is checked for in  model metrics.  
Best model gives a test accuracy of 0.82.   
This saved model is then tested on new images of each class. The accuracy for these new images is found to be 0.8.  
