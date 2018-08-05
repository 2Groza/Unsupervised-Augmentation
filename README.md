# Unsupervised-Augmentation
I want to use unsupervised method to do data augmentation. I believe such methods are pretty useful when facing small data sets using deep learning methods.


In my former work of unsupervised star-galaxy classification and the PROSTRATE12 challenge, I use this method to get better performence, especially in the test set. In another word, this method is kind of data augmentation method that can lead to  less overfitting.

The key here is that when we train our model with training data. Sometimes we use too much parameters that can not be fitted by the limited training data. The task in fact is finding a subspace, or manifold we are interested in from the whole space. However, when the dimension of images is, like 1000*1000, while we only have, for instance, 10,000 images as the training set, we always find it hard to train our model. The reason is that if we want to draw a picture of an extremely high dimension space, we can not only watch its few projections.
