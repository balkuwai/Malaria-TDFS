# Malaria-TDFS

This is a collab notebook that uses the Malaria dataset provided in TensorFlow Datasets.

This dataset has an equal number of parasited and uninfected images which is something noteworthy as probaly a real life dataset/sample provided by a lab wouldn't have this high percentage of parasited images.  The images were provided by the National Library of Medicine which has 27,558 training images.

There are 2 deep learning models and both use a function to create the convolutional network and then followed by a set of fully connected dense layers:
- the first model is a series of fully connected dense layers
- the 2nd model introduces residual blocks to the same architecture in the 1st model

If you have any questions or suggestions to this model please don't hesitate to drop me a line.
