# F-M-Detection

The F stands for Face and M stands for Mask , The face mask detection project , this project was made using the following libraries:
1.Tensorflow
2.Keras
3.MobileVnet2
4.Os
5.argparse
6.imutils
7.sklearn

The mask detection code is build and trained which gave 99.65 % of accuracy,The tensorflow and keras are the main libraries used to train the model with datasets containing with masks and without masks images.The tensorflow  and keras allows us to 
Data augmentation
Loading the MobilNetV2 classifier (we will fine-tune this model with pre-trained ImageNet weights)
Building a new fully-connected (FC) head
Pre-processing
Loading image data

We will use sklearn to binarizing class labels, segmenting our dataset, and printing a classification report.
My imutils paths implementation will help us to find and list images in our dataset. And we’ll use matplotlib to plot our training curves.
The argparser library helps me to input in the terminal with the commands .
