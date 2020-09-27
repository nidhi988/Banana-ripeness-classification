
Banana ripeness classification with deep learning network with deployment using flask framework.

Using pretrained model MobilenetV2 and fine tuning it.
It consists of 255 images with three classes ripe, overripe and green.

Model is trained and then convert using tensorflowjs_converter with following command:
$tensorflowjs_converter --input_format=keras ./keras_model.h5 ./tfjs_model



References:


https://towardsdatascience.com/keras-transfer-learning-for-beginners-6c9b8b7143e

https://hackernoon.com/classifying-images-using-tensorflow-js-keras-58431c4df04

