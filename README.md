# Retrain-pre-trained-classifier
To classify objects/images with Good accuracy is a very difficult task if we are having very small dataset of images. But this problem can be solved by retaining the pretained models(Models that are already trained for classification purpose with very big datasets).
In this, use the CNN layers of pretained model but make new Dense layers for classification.
The new Dense layer will be according to our requirements and would be trained on our small image dataset.
CNN layer is only there for extracting the features out of the images and those features are going to to be used as the input for Newly connected Dense Layers.
